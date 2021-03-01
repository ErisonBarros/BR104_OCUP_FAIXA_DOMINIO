# Análise Exploratória dos Dados

Realizou-se uma analise exploratória dos dados da ocorrência de ocupações irregulares sobre a faixa de domínio da BR-104. Usando os dados os dados IVS de 
2010 e associado a valor de terra nua disponibilizados pelo INCRA, para verificar o comportamento do fenômeno.

## Tratamento dos Dados 
[Pré-Processamento dos dados](https://colab.research.google.com/drive/1Tpocqpfj9O6F-5chcz2Z7EyjYUd-jVpe?usp=sharing) 

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
<img src="https://i.ibb.co/bRZNfFw/Escolhas-das-Variaveis.jpg" alt="Escolhas-das-Variaveis" border="0">



## Resultados do Modelo:

[Modelo Clássico:](https://raw.githubusercontent.com/ErisonBarros/BR104_OCUP_FAIXA_DOMINIO/master/Resultado%20da%20Regress%C3%A3o%20Classica.txt)
[Modelo Espacial Lag](https://raw.githubusercontent.com/ErisonBarros/BR104_OCUP_FAIXA_DOMINIO/master/Resultado%20Espacial%20Lag.txt)
[Modelo Espacial Erro](https://raw.githubusercontent.com/ErisonBarros/BR104_OCUP_FAIXA_DOMINIO/master/Resultado%20Espacial_Erro.txt)

**COMPARAÇÃO DE RESULTADOS**

|               	| Regressão Simples 	| Regressão "Espacial Error"  	|
|---------------	|-------------------	|-----------------------------	|
| logLikelihood 	|  -336.765           	| 1738.647513                     	|
| Akaike Info   	|683.53           	| -3467.3                      	|
| Criterion     	|                   	|                             	|

**Comparação de coeficientes padronizados**

|               	| Régressão Simples 	| Regressão "Espacial Error"  	|
|---------------	|-------------------	|-----------------------------	|
| constante 	|        	|                   	|
| IVS _INF  	|       	|                     	|
| IVS_CPH
|IVS_REN    	|                   	|                             	|
|DENS_HAB  	|                   	|                             	|
|LANBDA 	|                   	|                             	|

**Regressão Spatial Error:   Autocorrelação dos Resíduos**
Space > Univariate Local Moran’s I > ERRS_RESIDU

### Regressão “Spatial Lag”

|               	| Régressão Simples 	| Regressão "Espacial Error"  	|Regressão "Espacial Error"  	
|---------------	|-------------------	|-----------------------------	|-----------------------------	|
| logLikelihood	|    XXXXX    	|        XXXXX           	|XXXXX
| Akaike Info	|       XXX	|        XXXXX             	|     XXXXX
| Criterion|                        XXXXXX     	|XXXXX



**Comparação de coeficientes padronizados**

|               	| Régressão Simples 	| Regressão "Espacial Error"  	|Regressão "Espacial Error"  	
|---------------	|-------------------	|-----------------------------	|-----------------------------	|
| constante 	|    XXXXX    	|        XXXXX           	|XXXXX
| IVS _INF  	|       XXX	|        XXXXX             	|     XXXXX
| IVS_CPH | XX|                        XXXXXX     	|XXXXX
|IVS_REN    	|          XXXXX    	|         XXXXX                    	|XXXXXX
|DENS_HAB  	|    XXXXX               	|       XXXXX                      	|XXXXX
|LANBDA 	|        XXXXX           	|           XXXXX                  	| ZZZZZ

## Conclusões 
Verificações 
 - [ ] List item
 - [ ] List item
 - [ ] List item
 - [ ] List item


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTc4NTAwODM5OSwxMDEzOTg1MTgzLDc0ND
A5MzU4OCwtNjM1MzcyOTI1LC0xNjAwNjQ1NzEyLC0xNzA3MjM1
ODU2LC0xODI1NTIyMjQxLC0xMTU1ODI3ODYxLC0xMTgzMzU1Nz
IwLDg5MzY5NjU4NiwxNTU0Mzg2MzE4LDExNDI0NzAxMDIsMjEz
MDg4OTg1MSwtNzA5NjI5NDQxLC0xNDQzMzUxNzI4LC0xNTA4Nz
I3NzA5LDE3ODk4MTE5MDMsLTE3MDc0Mzg5NTUsMTAzMjE0MjIx
NSwtMjA2NjcwMjU5MV19
-->