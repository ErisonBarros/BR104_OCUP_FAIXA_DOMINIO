https://www.google.com/maps/d/u/0/edit?mid=1DKN0P84sqRZl_kq0HPbBlVsWPMW97m5o&usp=sharing




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
eyJoaXN0b3J5IjpbLTE3MDc0Mzg5NTUsMTAzMjE0MjIxNSwtMj
A2NjcwMjU5MSwtMTU0ODY4MTgxLC0xMTY3ODIwMjgxLDE0MDk5
ODcwMDAsLTQ0Njc3MjgwOCwxNzY3MjQ5NDE4LC0xNDYzODQwMD
gwXX0=
-->