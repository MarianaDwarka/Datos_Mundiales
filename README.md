# Datos_Mundiales

### Introducción
 El contexto del proyecto se enmarca en el análisis de datos globales a través de una base de datos llamada `world`, que incluye información sobre ciudades, países e idiomas. Este proyecto se desarrollará en tres partes principales: creación y carga de la base de datos, conexión y consulta de la base de datos utilizando Python, y visualización de los resultados obtenidos.

El problema o área de interés que se abordará en este proyecto de analytics es la integración y análisis de datos globales que permitan extraer conclusiones significativas sobre demografía, economía y diversidad lingüística. 
Al tener una base de datos estructurada y realizar consultas específicas, se busca obtener una visión detallada y comprensiva de estos aspectos a nivel mundial.

### Descripción del Proyecto

El proyecto "Datos Mundiales" se desarrollará en tres partes principales:

1. La primera parte se enfocará en la creación y carga de la base de datos. La base de datos, denominada `world`, consta de tres tablas: `city`, `country` y `countrylanguage`. La creación de la base de datos incluirá la definición de los esquemas y las relaciones entre las tablas. Se implementará en dos entornos distintos: en la nube utilizando Azure SQL Server y de manera local utilizando MySQL Workbench. Una vez creadas las tablas, se procederá a importar los datos correspondientes.
2.  En la segunda parte del proyecto, se establecerá una conexión con la base de datos utilizando Python. Para conectarse con Azure SQL Server, se empleará la biblioteca `sqlalchemy`, mientras que para MySQL se utilizará `mysql-connector-python`. Desde Python, se realizarán consultas SQL para responder a preguntas específicas sobre los datos, también se contestarán las mismas preguntas utilizando DataFrames de Pandas. Entre las consultas posibles se incluyen los nombres y las áreas de superficie de los cinco países más grandes del mundo, la población total de todos los países de cada continente, el nombre de las ciudades y la población de todos los países de Europa, etc.
3. La tercera parte del proyecto se centrará en la visualización de los datos. Se crearán visualizaciones en Python, se utilizarán bibliotecas como `matplotlib` y `seaborn`, creando gráficos que representen los datos obtenidos de las consultas. Por ejemplo, se podrán generar gráficos de barras para mostrar la población de cada continente o gráficos de pastel para representar el número de países por continente 

El proyecto "Datos Mundiales" abarcará desde la creación y carga de una base de datos hasta la realización de consultas y la visualización de los resultados mediante diversas herramientas.



### Conclusiones

Los resultados obtenidos del análisis de datos proporcionaron una visión detallada de diversos aspectos globales. Se observó que Asia es el continente con la mayor población, reflejando una gran densidad en regiones como China e India. Las ciudades europeas más pobladas, como Moscow, Londres, Berlín, Madrid, fueron identificadas, destacando su importancia en la distribución urbana.

Se actualizaron datos demográficos significativos, como la población de China, lo que subraya la importancia de mantener información precisa para el análisis. También se identificaron los países con más ciudades, destacando la urbanización en Estados Unidos y China, y se evaluó la diversidad lingüística, revelando la riqueza cultural de naciones como India y Canadá.

Las visualizaciones generadas, como gráficos de barras y pasteles, permitieron una representación clara de los datos, ayudando a interpretar los resultados de manera efectiva. Estas visualizaciones mostraron, por ejemplo, la densidad poblacional por continente y los idiomas más hablados en el mundo.

En conclusión, el proyecto logró sus objetivos al crear una base de datos, realizar consultas específicas y generar visualizaciones informativas. Los hallazgos obtenidos tienen implicaciones significativas para la comprensión de las dinámicas globales y pueden informar decisiones en áreas como la planificación urbana, la formulación de estrategias de mercado y la promoción de la diversidad cultural.

