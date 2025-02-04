# **Análisis de Multas por Incumplimiento del RGPD** 📊
Este proyecto analiza las multas impuestas por incumplimiento del RGPD (Reglamento General de Protección de Datos) para evaluar si estas sanciones han sido efectivas en reducir la reincidencia de infracciones. Se han utilizado técnicas de análisis de datos, visualización y modelado predictivo para explorar patrones en las sanciones aplicadas.

## 📂 Estructura del Proyecto
GDPR_fines.xlsx → Base de datos original con las multas recopiladas.

Sectores.xlsx → Clasificación de las empresas según su sector de actividad.

Proyecto.ipynb → Notebook en Jupyter con el análisis de datos y generación de gráficos.

Proyecto.pbix → Archivo de Power BI con visualizaciones interactivas.

Informe.pdf → Documento con los resultados y hallazgos del análisis.

Presentacion_sprint10.pdf → Presentación utilizada para exponer los resultados.
[Presentación interactiva](https://www.canva.com/design/DAGeC0rGGJE/UZ7lZGbsPQfvMt_C7iVncQ/edit?utm_content=DAGeC0rGGJE&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

Proyecto(PowerBI).pdf → Capturas y explicación del dashboard en Power BI.

README.md → Este archivo, que describe el proyecto.

## 📝 Objetivo del Estudio
Determinar si las multas impuestas bajo el RGPD han sido efectivas en reducir la reincidencia de infracciones y evaluar la relación entre los montos de las sanciones, los sectores afectados y el tipo de incumplimientos más frecuentes.

## 🔍 Metodología
Obtención de Datos

La base de datos se extrajo de Enforcement Tracker mediante web scraping con Octoparse.
Se procesaron 2,483 registros desde 2018 hasta 2024.
Limpieza y Transformación

Se rellenaron valores faltantes con "Desconocido" cuando correspondía.
Se tradujeron y abreviaron las categorías de incumplimiento.
Se creó una nueva columna para clasificar cada empresa por sector.
Análisis Exploratorio de Datos (EDA)

Identificación de empresas reincidentes.
Análisis de distribución de multas por sector, país y tipo de incumplimiento.
Comparación entre empresas con mayores y menores sanciones.
Evaluación del impacto financiero de las multas en grandes corporaciones vs. pequeñas empresas.
Visualización de Datos

Python: Manipulación de datos
Power BI: Dashboard interactivo con análisis por país, sector y reincidencia.
Flourish: Creación de gráficos interactivos para análisis comparativos.

## 📊 Hallazgos Clave
Solo el 9% de las empresas sancionadas han reincidido, lo que indica que en la mayoría de los casos las multas han sido efectivas.
Empresas de telecomunicaciones y tecnología son las más reincidentes, mientras que sectores como banca y seguros muestran menor reincidencia.
El monto de la multa no siempre es un factor disuasorio: algunas grandes empresas parecen asumir las sanciones como un costo operativo.
Los países con mayor cantidad de sanciones no siempre son los que han impuesto las multas más altas.

## 🏆 Conclusiones y Recomendaciones
Las multas han sido efectivas en reducir infracciones en la mayoría de los casos, pero no en sectores altamente dependientes de datos personales.
Sería útil una regulación más estricta con sanciones progresivas para empresas reincidentes.
Es necesario complementar las multas con auditorías y medidas de cumplimiento más exigentes.


## 🤝 Contribuciones
¡Cualquier sugerencia o contribución es bienvenida! Si encuentras errores o tienes ideas para mejorar el análisis, no dudes en abrir un issue o enviar un pull request.
