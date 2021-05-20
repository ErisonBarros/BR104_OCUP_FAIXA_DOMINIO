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




.
	 



<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0Mjc1MjgxMjUsLTEyNzg5MjgxMzUsMT
Y0Mjk0OTc1NCwxMTMxNTU5NTAxLC0yMTIxMjkwNzkyXX0=
-->