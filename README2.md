# <font color='blue'>ANALISES ESPAÇO TEMPORAL</font>

# <font color='Green'> Introdução</font>

A análise do comportamento das  ocupações irregulares sobre a BR-104 , levando em consideração a localização no espaço e no tempo permite relacionar os processo  socioeconômicos e de infra-estruturas com as ocupações irregulares com o ambiente.
	Para isso utilizaremos as técnicas de modelagem de Modelagem Espaço-temporal.
	Os eventos de ocupações irregulares sobre a faixa de domínio de rodovia influenciam substancialmente na segurança da via , na expansão urbana. Para lidar com as ocupações cada vez mais disseminadas, precisamos de estimativas precisas das chances de ocorrência de ocupações em  regiões  heterogêneas.
	As estimativas de risco de ocupações  são fundamentais para prevenir e combater estas ocupações. Para tanto, desenvolvemos um modelo de probabilidade anual para as ocupações  irregulares sobre a via com base na relação histórica entre  o uso/ocupação do solo, Evolução do índice de vulnerabilidade social, assim como o valor da terra nua podem ajudar a entender este fenômeno. 
	
# <font color='Green'> Metodologia </font>

Para isso usamos os dados do Índices de Vulnerabilidade Social (IVS) disponibilizado por município, disponível e  dados geoespaciais vetoriais rasterisamos e normalizamos os pixeis baseado nesta tabela abaixo.  

```markdown
| Intervalo     	| Pixel 	|
|---------------	|-------	|
| 0,100 - 0,199 	| 1     	|
| 0,200 - 0,299 	| 2     	|
| 0,300 - 0,399 	| 3     	|
| 0,400 - 0,499 	| 4     	|
| 0,500 - 0,599 	| 5     	|
| 0,600 - 0,699 	| 6     	|
| 0,700 - 0,799 	| 7     	|
| 0,800 - 0,899 	| 8     	|
```
As variáveis Analisadas de forma raster:
 > Percentual de DPPs com abastecimento de água da rede geral.					
> Percentual de DPPs com banheiro de uso exclusivo dos moradores ou sanitário e esgotamento sanitário via rede geral de esgoto ou pluvial.		
> Percentual de DPPs com lixo coletado por serviço de limpeza.					
> Rendimento nominal mensal dos Responsáveis por Domicílio					
> Percentual de Domicílios particulares precários					
> Percentual de domicílios particulares com banheiro ou sanitário sem esgotamento sanitário via rede geral de esgoto, pluvial ou fossa séptica	
> Percentual de DPPs sem banheiro					
> Percentual de DPPs com lixo não coletado					
> Percentual de DPPs alugados					
> Percentual de DPPs com mais 4 moradores					
> Percentual de responsáveis por DPPs sem rendimento nominal mensal					
> Percentual de responsáveis por DPPs com rendimento nominal mensal de até 3 salários mínimos					
> Percentual Chefe de Familia Alfabetizado					
> Percentual Pessoas alfabetizadas					
> Renda per capita (apenas dos responsáveis pela família)					
> Distância das ocupações até o eixo da BR-104

# Normalização dos Dados

### Distância das ocupações até o eixo da BR-104
* pixel 1 = distancias de 0 a 500m
* pixel 2 = distancias de 501 a 1000m
* pixel 3 = distâncias acima de 1000m


| Sigla_Variavel 	|            	| Descrição                                                                                                                                    	|   	|   	|   	|   	|   	|
|----------------	|------------	|----------------------------------------------------------------------------------------------------------------------------------------------	|---	|---	|---	|---	|---	|
| 2000           	| 2010       	|                                                                                                                                              	|   	|   	|   	|   	|   	|
| P_AGUA_00      	| P_AGUA_10  	| Percentual de DPPs com abastecimento de água da rede geral.                                                                                  	|   	|   	|   	|   	|   	|
| P_ESG_00       	| P_ESG_10   	| Percentual de DPPs com banheiro de uso exclusivo dos moradores ou sanitário e esgotamento sanitário via rede geral de esgoto ou pluvial.     	|   	|   	|   	|   	|   	|
| P_LIXO_00      	| P_LIXO_10  	| Percentual de DPPs com lixo coletado por serviço de limpeza.                                                                                 	|   	|   	|   	|   	|   	|
| RNMPr_00       	| RNMPr_10   	| Rendimento nominal mensal dos Responsáveis por Domicílio                                                                                     	|   	|   	|   	|   	|   	|
| V1_00          	| V1_10      	| Percentual de Domicílios particulares precários                                                                                              	|   	|   	|   	|   	|   	|
| -              	| -          	| Percentual de domicílios particulares sem abastecimento de água da rede geral                                                                	|   	|   	|   	|   	|   	|
| V3_00          	| V3_10      	| Percentual de domicílios particulares com banheiro ou sanitário sem esgotamento sanitário via rede geral de esgoto, pluvial ou fossa séptica 	|   	|   	|   	|   	|   	|
| V4_00          	| V4_10      	| Percentual de DPPs sem banheiro                                                                                                              	|   	|   	|   	|   	|   	|
| V5_00          	| V5_10      	| Percentual de DPPs com lixo não coletado                                                                                                     	|   	|   	|   	|   	|   	|
| -              	| -          	| Percentual de DPPs sem energia elétrica                                                                                                      	|   	|   	|   	|   	|   	|
| V7_00          	| V7_10      	| Percentual de DPPs alugados                                                                                                                  	|   	|   	|   	|   	|   	|
| V8_00          	| V8_10      	| Percentual de DPPs com mais 4 moradores                                                                                                      	|   	|   	|   	|   	|   	|
| V21_00         	| V21_10     	| Percentual de responsáveis por DPPs sem rendimento nominal mensal                                                                            	|   	|   	|   	|   	|   	|
| V22_00         	| V22_10     	| Percentual de responsáveis por DPPs com rendimento nominal mensal de até 3 salários mínimos                                                  	|   	|   	|   	|   	|   	|
| P_ALFAC_00     	| P_ALFAC_10 	| Percentual Chefe de Familia Alfabetizado                                                                                                     	|   	|   	|   	|   	|   	|
| P_ALFAP_00     	| P_ALFAP_10 	| Percentual Pessoas alfabetizadas                                                                                                             	|   	|   	|   	|   	|   	|
| -              	| -          	| Pessoas de raça branca                                                                                                                       	|   	|   	|   	|   	|   	|
| -              	| -          	| Pessoas de raça preta                                                                                                                        	|   	|   	|   	|   	|   	|
| -              	| -          	| Pessoas de raça Amarela                                                                                                                      	|   	|   	|   	|   	|   	|
| -              	| -          	| Pessoas de raça Parda                                                                                                                        	|   	|   	|   	|   	|   	|
| -              	| -          	| Pessoas de raça Indígena                                                                                                                     	|   	|   	|   	|   	|   	|
| -              	| -          	| Percentual de Rendimento até 1/8 Salário Mínimo (954,00)                                                                                     	|   	|   	|   	|   	|   	|
| -              	| -          	| Percentual de Rendimento de 1/8 a 1/4 Salário Mínimo (954,00)                                                                                	|   	|   	|   	|   	|   	|
| -              	| -          	| Percentual de Rendimento de 1/4 a 1/2 Salário Mínimo (954,00)                                                                                	|   	|   	|   	|   	|   	|
| -              	| -          	| Percentual de Rendimento de 1/2 a 1 Salário Mínimo (954,00)                                                                                  	|   	|   	|   	|   	|   	|
| -              	| -          	| Percentual de Rendimento de 1 a 2 Salários Mínimos (954,00)                                                                                  	|   	|   	|   	|   	|   	|
| -              	| -          	| Percentual de Rendimento de 2 a 3 Salários Mínimos (954,00)                                                                                  	|   	|   	|   	|   	|   	|
| -              	| -          	| Percentual de Rendimento de 3 a 5 Salários Mínimos (954,00)                                                                                  	|   	|   	|   	|   	|   	|
| -              	| -          	| Percentual de Rendimento 5 a 10 Salários Mínimos (954,00)                                                                                    	|   	|   	|   	|   	|   	|
| -              	| -          	| Percentual de Rendimento 10 ou mais Salários Mínimos (954,00)                                                                                	|   	|   	|   	|   	|   	|
| -              	| -          	| Percentual sem rendimento                                                                                                                    	|   	|   	|   	|   	|   	|
| RPC_00         	| RPC_10     	| Renda per capita (apenas dos responsáveis pela família)                                                                                      	|   	|   	|   	|   	|   	|

# Analise do Uso e Ocupação do Solo

Análise da ocupação e do  uso do solo foi realizado pelo Qgis com o Uso do Plugin Molusce como pode ser visto pela Tela  do Programa.

<img src="https://i.ibb.co/b6VfDXP/Uso-2000.png" alt="Uso-2000" border="0">



<img src="https://i.ibb.co/XYKTcvZ/Rplot01-caterorias.png" alt="Rplot01-caterorias" border="0">










<!--stackedit_data:
eyJoaXN0b3J5IjpbNzM3NTk2NjM5LDkyMDY4NzM2OSwtOTc1ND
QxNjk3LDE1MjA5ODA3MjEsNjY1NDM1MTc1LC0xOTA3NDM0MDAz
LC0xMjc4OTI4MTM1LDE2NDI5NDk3NTQsMTEzMTU1OTUwMSwtMj
EyMTI5MDc5Ml19
-->