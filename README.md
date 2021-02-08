# Análise Exploratória dos Dados
## Tratamento dos Dados 
[Pré-Processamento dos dados](https://github.com/ErisonBarros/BR104_OCUP_FAIXA_DOMINIO/blob/master/Profiling_BR104_An%C3%A1lise_Explorat%C3%B3ria.ipynb) 

<img src="https://i.ibb.co/9ty9S5J/thumbnail-mid-1-DKN0-P84sq-RZl-kq0-HPb-Bl-Vs-WPMW97m5o.jpg" alt="thumbnail-mid-1-DKN0-P84sq-RZl-kq0-HPb-Bl-Vs-WPMW97m5o" border="0">

## **Interpretação do IVS**

<img src="https://i.ibb.co/3y5534q/Faixas-de-vulnerabilidade-social-6.jpg" alt="Faixas-de-vulnerabilidade-social-6" border="0">


[Mapa Dinamicico ](https://www.google.com/maps/d/u/0/edit?mid=1DKN0P84sqRZl_kq0HPbBlVsWPMW97m5o&usp=sharing)

#Analise Exploratória dos Dados Espacial " GEODA"
### Localização das Ocupações 

<img src="https://i.ibb.co/9vNYk7X/OCUP-BR104-DATASET-01.png" alt="OCUP-BR104-DATASET-01" border="0">
<img src="https://i.ibb.co/HT6RBGv/OCUP-BR104-DATASET-01-01.png" alt="OCUP-BR104-DATASET-01-01" border="0">
<img src="https://i.ibb.co/VJJvPJT/OCUP-BR104-DATASET-01-03.png" alt="OCUP-BR104-DATASET-01-03" border="0">
<img src="https://i.ibb.co/NLF7bVs/OCUP-BR104-DATASET-01-3.png" alt="OCUP-BR104-DATASET-01-3" border="0">
<img src="https://i.ibb.co/SX6sxnq/OCUP-BR104-DATASET-01.png" alt="OCUP-BR104-DATASET-01" border="0">
<img src="https://i.ibb.co/v1L0tfc/OCUP-BR104-DATASET-01-Lisa-Scatter-Plot-Frame.png" alt="OCUP-BR104-DATASET-01-Lisa-Scatter-Plot-Frame" border="0">
<img src="https://i.ibb.co/mhST6G8/OCUP-BR104-DATASET-013.png" alt="OCUP-BR104-DATASET-013" border="0">


Resultados:



**Variável Dependente:** Ocupação Irregular em 2010
**Váriaveis Indeoendentes**:

<img src="https://i.ibb.co/bRZNfFw/Escolhas-das-Variaveis.jpg" alt="Escolhas-das-Variaveis" border="0">

## Resultados do Modelo:

[Modelo Clássico:](https://raw.githubusercontent.com/ErisonBarros/BR104_OCUP_FAIXA_DOMINIO/master/Resultado%20da%20Regress%C3%A3o%20Classica.txt)
[Modelo Espacial Lag](https://raw.githubusercontent.com/ErisonBarros/BR104_OCUP_FAIXA_DOMINIO/master/Resultado%20Espacial%20Lag.txt)
[Modelo Espacial Erro](https://raw.githubusercontent.com/ErisonBarros/BR104_OCUP_FAIXA_DOMINIO/master/Resultado%20Espacial_Erro.txt)

**COMPARAÇÃO DE RESULTADOS**

|               	| Régressão Simples 	| Regressão "Espacial Error"  	|
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
eyJoaXN0b3J5IjpbLTcwOTYyOTQ0MSwtMTQ0MzM1MTcyOCwtMT
UwODcyNzcwOSwxNzg5ODExOTAzLC0xNzA3NDM4OTU1LDEwMzIx
NDIyMTUsLTIwNjY3MDI1OTEsLTE1NDg2ODE4MSwtMTE2NzgyMD
I4MSwxNDA5OTg3MDAwLC00NDY3NzI4MDgsMTc2NzI0OTQxOCwt
MTQ2Mzg0MDA4MF19
-->