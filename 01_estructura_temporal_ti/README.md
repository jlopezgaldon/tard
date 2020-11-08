## README

### Estructura temporal (subyacente) de los tipos de interés

#### Planteamiento

El estudio de la estructura subyacente de los tipos de interés es reiterativa en la literatura financiera. Cabe citar, entre otros, el clásico artículo de Fama y Bliss de 1987 (The Information in Long-Maturity Forward Rates,The American Economic Review, Vol. 77, No. 4 ), el de Litterman y Scheinkman (Common factors affecting bond returns, Journal of fixed income, 1991) o, ya más recientes, el de Diebold, Piazzesi y Rudebusch (Modeling Bond Yields in Finance and Macroeconomics, American Economic Review 95.2, 2005), o el de Diebold y Li (Forecasting the term structure of government bond yields, Journal of Econometrics, 130.2, 2006). Puede consultarse también el paper de 2014 de Moody’s Analytics Principal Component Analysis for Yield Curve Modelling (Enlaces a un sitio externo.) o el white paper de 2009 de Novosyolov y Satchkov, Global Term Structure Modeling Using Principal Component Analysis (Enlaces a un sitio externo.).

El objetivo que perseguimos en el presente trabajo es, simplemente, efectuar una comprobación empírica mediante la aplicación del ACP a un conjunto de 978 observaciones de los rendimientos de 10 bonos norteamericanos a distintos plazos entre el 2 de enero de 1995 y el 30 de septiembre de 1998. No pretendemos nada más que verificar si, tal y como plantean los estudios teóricos, puede establecerse una estructura subyecente que sintetice y agrupe los distintos plazos en virtud de sus características comunes. Para ello, deberá trabajar con el archivo ACPTIUSD.csvVista previa del documento, disponible en la plataforma, del que deberá utilizar las 949 primeras observaciones (denominadas observaciones activas) y las 9 primeras variables (las variables activas); uno de los objetivos será emplear las observaciones 950 a 978 (llamadas observaciones suplementarias) para predecir el valor del bono a 10 años (IRS.10Y, variable suplementaria). Aparte de cubrir este objetivo, queremos asimismo tener respuesta a las siguientes preguntas:

1. ¿Tiene sentido llevar a cabo, en este caso, un análisis de componentes principales? Para justificarlo, deberá llevar a cabo las pruebas que estime oportunas, como, por ejemplo el análisis de la matriz de correlaciones, el del determinante de dicha matriz, la prueba de esfericidad de Bartlett, el KMO o el MSA;

2. ¿Cuántos componentes permitirían explicar, adecuadamente, la estructura subycente de los tipos de interés aquí analizados? Justifique su respuesta empleando, por ejemplo, las pruebas de la varianza explicada o del gráfico de sedimentación;


3. Finalmente, ¿tiene sentido llevar a cabo una rotación de las variables subyacentes? Para responder, lleva a cabo una rotación Varimax, por ejemplo.

Por último, deberá elaborar las oportunas conclusiones.

### Structure

- README.md <- The top-level README for developers.

- data

	- 01_raw <- Immutable input data


- html <- html of the rmd.

- rmd <- r markdowns.



