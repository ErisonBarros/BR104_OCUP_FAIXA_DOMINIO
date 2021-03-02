# Análise Exploratória dos Dados

Realizou-se uma analise exploratória dos dados da ocorrência de ocupações irregulares sobre a faixa de domínio da BR-104. Usando os dados os dados IVS de 
2010 e associado a valor de terra nua disponibilizados pelo INCRA, para verificar o comportamento do fenômeno.

## Tratamento dos Dados 
[Pré-Processamento dos dados]
(https://colab.research.google.com/drive/1Tpocqpfj9O6F-5chcz2Z7EyjYUd-jVpe?usp=sharing) 
<img src="https://i.ibb.co/9ty9S5J/thumbnail-mid-1-DKN0-P84sq-RZl-kq0-HPb-Bl-Vs-WPMW97m5o.jpg" alt="thumbnail-mid-1-DKN0-P84sq-RZl-kq0-HPb-Bl-Vs-WPMW97m5o" border="0">
<iframe src="https://www.google.com/maps/d/u/0/embed?mid=1DKN0P84sqRZl_kq0HPbBlVsWPMW97m5o" width="640" height="480"></iframe>

[Mapa Dinamicico ](https://www.google.com/maps/d/u/0/edit?mid=1DKN0P84sqRZl_kq0HPbBlVsWPMW97m5o&usp=sharing)

## **Interpretação do IVS**

<img src="https://i.ibb.co/3y5534q/Faixas-de-vulnerabilidade-social-6.jpg" alt="Faixas-de-vulnerabilidade-social-6" border="0">

#Analise Exploratória dos Dados Espacial " GEODA"
### Localização das Ocupações 

<img src="https://i.ibb.co/9vNYk7X/OCUP-BR104-DATASET-01.png" alt="OCUP-BR104-DATASET-01" border="0">
<img src="https://i.ibb.co/HT6RBGv/OCUP-BR104-DATASET-01-01.png" alt="OCUP-BR104-DATASET-01-01" border="0">
<img src="https://i.ibb.co/VJJvPJT/OCUP-BR104-DATASET-01-03.png" alt="OCUP-BR104-DATASET-01-03" border="0">
<img src="https://i.ibb.co/NLF7bVs/OCUP-BR104-DATASET-01-3.png" alt="OCUP-BR104-DATASET-01-3" border="0">
<img src="https://i.ibb.co/SX6sxnq/OCUP-BR104-DATASET-01.png" alt="OCUP-BR104-DATASET-01" border="0">
<img src="https://i.ibb.co/v1L0tfc/OCUP-BR104-DATASET-01-Lisa-Scatter-Plot-Frame.png" alt="OCUP-BR104-DATASET-01-Lisa-Scatter-Plot-Frame" border="0">
<img src="https://i.ibb.co/mhST6G8/OCUP-BR104-DATASET-013.png" alt="OCUP-BR104-DATASET-013" border="0">

## Analise de Correlação entre as variáveis 

<img src="https://i.ibb.co/wN0T2jM/correla-o.jpg" alt="correla-o" border="0">
https://i.ibb.co/wN0T2jM/correla-o.jpg

### Estatísticas Descritivas da variável
```markdown
| ocup_2010 	| IVS_REN_10     	| Dens_hab       	| IVS_INF_10        	| Pop_Total      	| URB_RURAL      	| VTN_MED       	|              	|
|-----------	|----------------	|----------------	|-------------------	|----------------	|----------------	|---------------	|--------------	|
|           	| Min.   :0.0000 	| Min.   :0.0000 	| Min.   :0.0000000 	| Min.   :0.0000 	| Min.   : 22679 	| Min.   :0.000 	| Min.   :2395 	|
|           	| 1st Qu.:0.0000 	| 1st Qu.:0.3570 	| 1st Qu.:0.0003992 	| 1st Qu.:0.1050 	| 1st Qu.: 24903 	| 1st Qu.:0.000 	| 1st Qu.:5105 	|
|           	| Median :1.0000 	| Median :0.3570 	| Median :0.0053653 	| Median :0.1050 	| Median :314912 	| Median :1.000 	| Median :5105 	|
|           	| Mean   :0.6554 	| Mean   :0.4076 	| Mean   :0.0059538 	| Mean   :0.1428 	| Mean   :178470 	| Mean   :0.747 	| Mean   :4701 	|
|           	| 3rd Qu.:1.0000 	| 3rd Qu.:0.5210 	| 3rd Qu.:0.0097318 	| 3rd Qu.:0.2090 	| 3rd Qu.:314912 	| 3rd Qu.:1.000 	| 3rd Qu.:5105 	|
|           	| Max.   :1.0000 	| Max.   :0.6370 	| Max.   :0.0188397 	| Max.   :0.3810 	| Max.   :314912 	| Max.   :1.000 	| Max.   :8363 	|
```
Pelo comportamento do fenômeno como ocupação e não ocupação, usamos a regressão logística para verificarmos o comportamento das variaveis.

# Análise de Regressão Logística
<img src="https://i.ibb.co/4M4Z1M3/resultados-regress-o-logistica.jpg" alt="resultados-regress-o-logistica" border="0">

<img src="https://i.ibb.co/bdGMSgJ/resultado-logistica.jpg" alt="resultado-logistica" border="0">

<img src="https://i.ibb.co/Prqj6DM/resultados-regress-o-logistica2.jpg" alt="resultados-regress-o-logistica2" border="0">

# Pré- Processamento no GEODA
Resultados:
<img src="https://i.ibb.co/yFkx68K/Analise-de-Regress-o.jpg" alt="Analise-de-Regress-o" border="0">

## Resultados do Modelo:

[Modelo Clássico:](https://raw.githubusercontent.com/ErisonBarros/BR104_OCUP_FAIXA_DOMINIO/master/Resultados%20da%20Regress%C3%A3o%20final.txt)
<img src="https://i.ibb.co/wgDyG5W/Capturar.jpg" alt="Capturar" border="0">
**HETEROCEDASTICIDADE (Breusch-Pagan, Koenker-Basset e Teste White)**
Hipótese Nula: Variância é constante (Homocedasticidade), hipótese nula foi rejeitada
**AUTOCORRELAÇÃO ESPACIAL**  
Índice de Moran
Como salvamos os resíduos e valores previstos na tabela, podemos elaborar  mapas e gráficos a partir destas informações.
HISTOGRAMA DOS RESÍDUOS (OLS_RESIDU)
<img src="https://i.ibb.co/tHsWkXw/Histograma-do-Residuo.png" alt="Histograma-do-Residuo" border="0">
[Modelo Espacial Lag](https://raw.githubusercontent.com/ErisonBarros/BR104_OCUP_FAIXA_DOMINIO/master/Resultados%20da%20Regress%C3%A3o%20Spatal%20Lag.txt)
<img src="https://i.ibb.co/b22f7Rm/Spatial-Lag.jpg" alt="Spatial-Lag" border="0">

[Modelo Espacial Erro](https://raw.githubusercontent.com/ErisonBarros/BR104_OCUP_FAIXA_DOMINIO/master/Resultados%20da%20Regress%C3%A3o%20Spatal%20Erro.txt)
<img src="https://i.ibb.co/86c03GG/Spatial-Erro.jpg" alt="Spatial-Erro" border="0">

**COMPARAÇÃO DE RESULTADOS**

|               	| Regressão Simples 	| Regressão "Espacial Error"  	|
|---------------	|-------------------	|-----------------------------	|
| logLikelihood 	|  -274.077         	| 1372.915120                  	|
| Akaike Info   	|560.154           	| -2739.83                     	|
| Schwarz criterionCriterion     	|      590.779           	|  -2724.52                           	|


**Regressão Spatial Error:   Autocorrelação dos Resíduos**
Space > Univariate Local Moran’s I > ERRS_RESIDU

### Regressão “Spatial Lag”

|               	| Regressão Simples 	| Regressão "Espacial Error"  	|Regressão "Espacial Lag"  	
|---------------	|-------------------	|-----------------------------	|-----------------------------	|
| logLikelihood	|    -274.077    	|       1372.915120         	|1372.78
| Akaike InfoCriterion	|      560.154   	|       -2739.83              	|     -2737.56

## Conclusões 
Verificações 
 - [ ] Verificamos que a densidades populacional, densidade de Domicílios tem uma forte relação com as ocupações irregulares.
 <img src="https://i.ibb.co/8bXKYSk/Densidade-Dom-cilios.png" alt="Densidade-Dom-cilios" border="0">

 - [ ] List item
 - [ ] List item
 - [ ] List item


<!--stackedit_data:
eyJoaXN0b3J5IjpbMTMwNjg4MTY4OCwxNjAxNDE0NTMsMTI5NT
IyNzcyMywxMzc0NDgxOTk0LDk3NTQwNDMyNywxMjQ3NjEzMTIy
LDEwNjk5Nzc1NDIsMTE3MTA3ODMzNywyMDYxNTU4NjQ5LC03OD
UwMDgzOTksMTAxMzk4NTE4Myw3NDQwOTM1ODgsLTYzNTM3Mjky
NSwtMTYwMDY0NTcxMiwtMTcwNzIzNTg1NiwtMTgyNTUyMjI0MS
wtMTE1NTgyNzg2MSwtMTE4MzM1NTcyMCw4OTM2OTY1ODYsMTU1
NDM4NjMxOF19
-->