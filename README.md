#Analise Exploratória dos Dados no GEODA

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


|               	| Régressão Simples 	| Regressão "Espacial Error"  	|Regressão "Espacial Error"  	
|---------------	|-------------------	|-----------------------------	|-----------------------------	|
| constante 	|        	|                   	|
| IVS _INF  	|       	|                     	|
| IVS_CPH
|IVS_REN    	|                   	|                             	|
|DENS_HAB  	|                   	|                             	|
|LANBDA 	|                   	|                             	|
<!--stackedit_data:
eyJoaXN0b3J5IjpbOTc3MzQ0MTYyLC0xNTQ4NjgxODEsLTExNj
c4MjAyODEsMTQwOTk4NzAwMCwtNDQ2NzcyODA4LDE3NjcyNDk0
MTgsLTE0NjM4NDAwODBdfQ==
-->