# Datos_Mundiales

### Introducción
 El contexto del proyecto se enmarca en el análisis de datos globales a través de una base de datos llamada `world`, que incluye información sobre ciudades, países e idiomas. Este proyecto se desarrollará en tres partes principales: creación y carga de la base de datos, conexión y consulta de la base de datos utilizando Python, y visualización de los resultados obtenidos.

El problema o área de interés que se abordará en este proyecto de analytics es la integración y análisis de datos globales que permitan extraer conclusiones significativas sobre demografía, economía y diversidad lingüística. 
Al tener una base de datos estructurada y realizar consultas específicas, se busca obtener una visión detallada y comprensiva de estos aspectos a nivel mundial.

### Objetivos del Proyecto

El proyecto persigue varios objetivos específicos. 
En primer lugar, se busca crear una base de datos que contenga información relevante sobre ciudades, países e idiomas. Esto incluirá la definición de los esquemas de las tablas y la importación de datos en un entorno de nube (Azure SQL Server) y un entorno local (MySQL Workbench).

En segundo lugar, el objetivo es establecer una conexión eficiente con la base de datos utilizando Python y realizar consultas SQL que respondan a preguntas específicas sobre los datos. Para conectar y manipular los datos desde Python, se emplearon las bibliotecas `sqlalchemy` para Azure SQL Server y `mysql-connector-python` para MySQL Workbench. Adicionalmente, se utilizaron DataFrames de Pandas para realizar manipulaciones y análisis de datos. Las técnicas de análisis incluyeron consultas SQL para extraer datos relevantes y el uso de Pandas para analizar estos datos.

Finalmente, el tercer objetivo es crear visualizaciones efectivas de los datos utilizando bibliotecas como `matplotlib` y `seaborn`. Estas visualizaciones ayudarán a representar de manera clara y comprensible los resultados obtenidos de las consultas, facilitando la interpretación y el análisis de los datos.


### Conclusiones

Los resultados obtenidos del análisis de datos proporcionaron una visión detallada de diversos aspectos globales. Se observó que Asia es el continente con la mayor población, reflejando una gran densidad en regiones como China e India. Las ciudades europeas más pobladas, como Moscow, Londres, Berlín, Madrid, fueron identificadas, destacando su importancia en la distribución urbana.

Se actualizaron datos demográficos significativos, como la población de China, lo que subraya la importancia de mantener información precisa para el análisis. También se identificaron los países con más ciudades, destacando la urbanización en Estados Unidos y China, y se evaluó la diversidad lingüística, revelando la riqueza cultural de naciones como India y Canadá.

Las visualizaciones generadas, como gráficos de barras y pasteles, permitieron una representación clara de los datos, ayudando a interpretar los resultados de manera efectiva. Estas visualizaciones mostraron, por ejemplo, la densidad poblacional por continente y los idiomas más hablados en el mundo.

En conclusión, el proyecto logró sus objetivos al crear una base de datos, realizar consultas específicas y generar visualizaciones informativas. Los hallazgos obtenidos tienen implicaciones significativas para la comprensión de las dinámicas globales y pueden informar decisiones en áreas como la planificación urbana, la formulación de estrategias de mercado y la promoción de la diversidad cultural.

