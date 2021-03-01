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

# Análise de Regressão Logística no Studio
Call:
glm(formula = ocup_2010 ~ IVS_REN_10 + Dens_hab + IVS_INF_10 + 
    VTN_MED, family = binomial(link = "logit"), data = dados_1)

Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
-2.0195  -0.9879   0.2994   0.8543   1.3876  

Coefficients:
              Estimate Std. Error z value Pr(>|z|)    
(Intercept) -1.141e+01  1.208e+00  -9.446  < 2e-16 ***
IVS_REN_10   2.571e+01  2.505e+00  10.263  < 2e-16 ***
Dens_hab     1.199e+02  1.341e+01   8.946  < 2e-16 ***
IVS_INF_10  -1.246e+01  4.223e+00  -2.950 0.003177 ** 
VTN_MED      6.001e-04  1.702e-04   3.526 0.000423 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

(Dispersion parameter for binomial family taken to be 1)

    Null deviance: 1542.7  on 1216  degrees of freedom
Residual deviance: 1145.9  on 1212  degrees of freedom
  (28 observations deleted due to missingness)
AIC: 1155.9




# Pré- Processamento no GEODA
Resultados:

**Variável Dependente:** Ocupação Irregular em 2010
**Variáveis Independentes**:

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
eyJoaXN0b3J5IjpbLTQyODY5NjIyNCwtMTE1NTgyNzg2MSwtMT
E4MzM1NTcyMCw4OTM2OTY1ODYsMTU1NDM4NjMxOCwxMTQyNDcw
MTAyLDIxMzA4ODk4NTEsLTcwOTYyOTQ0MSwtMTQ0MzM1MTcyOC
wtMTUwODcyNzcwOSwxNzg5ODExOTAzLC0xNzA3NDM4OTU1LDEw
MzIxNDIyMTUsLTIwNjY3MDI1OTEsLTE1NDg2ODE4MSwtMTE2Nz
gyMDI4MSwxNDA5OTg3MDAwLC00NDY3NzI4MDgsMTc2NzI0OTQx
OCwtMTQ2Mzg0MDA4MF19
-->