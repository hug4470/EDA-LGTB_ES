(Presentación en canva: https://www.canva.com/design/DAGTui2esqQ/Amo6gst5-cROGhHXFTS60g/edit)
# Análisis de Agresiones LGTBIfóbicas en España (2014-2023)
Este repositorio contiene nuestro análisis exploratorio de datos (EDA) enfocado en los delitos de odio contra el colectivo LGTBIQ+ registrados en España entre 2014 y 2023. Nuestro objetivo es estudiar la evolución de estos delitos a lo largo del tiempo y su distribución en las distintas comunidades autónomas, prestando especial atención a los subgrupos más vulnerables del colectivo.

## Objetivos del Proyecto
- Identificar tendencias temporales: Analizamos cómo han evolucionado las agresiones LGTBIfóbicas en España desde 2014 hasta 2023.
- Análisis regional: Examinamos las diferencias en la incidencia de estos delitos entre las comunidades autónomas.
- Estudio de subgrupos: Investigamos qué subgrupos dentro del colectivo LGTBIQ+ han sido más afectados por estas agresiones.
- Evaluación del impacto legislativo: Exploramos posibles correlaciones entre cambios en la legislación y la evolución de los delitos de odio.

## Dataset
El análisis se basa en un conjunto de datos que incluye:

1. Registros de delitos de odio por comunidades autónomas desde 2014 hasta 2023.
2. Desglose por subgrupos del colectivo LGTBIQ+, tales como orientación sexual, identidad de género, entre otros.
3. Totales nacionales de incidentes para cada año.

## Metodología
Nuestro análisis se llevó a cabo siguiendo los siguientes pasos:

1. Extracción de datos:
  - Hemos extraído los datasets relacionados con los delitos de odio desde el Ministerio del Interior de España, así como de fuentes secundarias relacionadas con estadísticas LGTBIQ+ en España. Los datos         utilizados cubren el período de 2014 a 2023 y están desglosados por comunidades autónomas.
  - También utilizamos datos complementarios de diversas organizaciones que documentan agresiones por subgrupos del colectivo, como el observatorio madrileño contra la LGTBIfobia.
  - Parte de los datos fue obtenida mediante web scraping, utilizando Selenium para automatizar la extracción de información.

2. Preparación de los datos:
  - Limpiamos y normalizamos los datos para asegurar consistencia, utilizando técnicas de preprocesamiento con Pandas.
  - Realizamos verificaciones para identificar y tratar valores nulos o inconsistentes.
  - Generamos nuevos datasets a raíz de los iniciales, como uno que promedia el total anual de agresiones por año y comunidad autónoma por cada millón de habitantes.

3. Análisis de datos:
  - Para visualizar la evolución temporal de los delitos, creamos gráficos que muestran el número total de agresiones a nivel nacional en este período y su evolución.
  - También analizamos a nivel autonómico las agresiones medias desde 2014 a 2023, y específicamente en 2023, para ver su evolución individual.
  - Calculamos medias anuales y utilizamos mapas interactivos con Folium para visualizar la distribución geográfica de los delitos.
  - Se analizó la correlación entre variables, como la orientación sexual, identidad de género y otras categorías dentro del colectivo LGTBIQ+, para identificar qué subgrupos son más vulnerables.

## Hipótesis de Trabajo
Partimos de las siguientes hipótesis:

1. Incremento de agresiones: Las agresiones contra el colectivo LGTBIQ+ han aumentado en España durante el período estudiado.
2. Variabilidad regional: Existen diferencias significativas en la incidencia de estos delitos entre las comunidades autónomas.
3. Subgrupos más vulnerables: Algunos subgrupos dentro del colectivo son más propensos a sufrir agresiones. ¿Afecta la invisibilidad?
4. Impacto legislativo: Las modificaciones en la legislación pueden haber influido en la variación de los delitos de odio.

## Herramientas Utilizadas
Para llevar a cabo este análisis, hemos utilizado las siguientes herramientas:

1. Python para el procesamiento y análisis de los datos.
2. Pandas para la manipulación y limpieza de los datos.
3. Matplotlib y Seaborn para la visualización de los resultados.
4. Folium para la creación de mapas interactivos que permiten explorar la distribución geográfica de los delitos.
5. Selenium para la extracción de datos mediante web scraping.

## Conclusiones
El análisis de los delitos de odio contra el colectivo LGTBIQ+ en España durante el período 2014-2023 nos ha permitido obtener varios hallazgos importantes:

1. Aumento significativo de agresiones: Observamos un incremento constante en el número de delitos de odio contra personas LGTBIQ+ a lo largo del período analizado, particularmente en los últimos años. Este aumento es más notable a partir de 2020, coincidiendo con la implementación de leyes más visibles para la protección de los derechos del colectivo. Sin embargo, este crecimiento podría también estar asociado a una mayor concienciación y denuncia por parte de las víctimas.

2. Variabilidad por comunidades autónomas: Existen diferencias significativas entre las comunidades autónomas. Las regiones con más densidad poblacional, como Madrid y Cataluña, reportan un mayor número de incidentes, lo cual es consistente con la mayor visibilidad del colectivo en estas zonas. Sin embargo, otras comunidades autónomas como País Vasco y Canarias también muestran cifras altas.

3. Subgrupos más afectados: Dentro del colectivo LGTBIQ+, los subgrupos más afectados por las agresiones son las personas que se identifican como trans y aquellas con una orientación sexual no normativa, como gays y lesbianas. Este hallazgo refuerza la vulnerabilidad específica que enfrentan ciertos subgrupos, en especial las personas trans, quienes sufren discriminación tanto por su identidad de género como por su expresión de género.

4. Impacto de la legislación: A pesar de la adopción de leyes que protegen los derechos del colectivo LGTBIQ+, no observamos una disminución generalizada en el número de incidentes. Sin embargo, los datos sugieren que en comunidades con una implementación más robusta de políticas inclusivas (por ejemplo, Madrid), el aumento de delitos de odio ha sido menos pronunciado en comparación con otras regiones. Este resultado sugiere que si bien la legislación es crucial, la aplicación efectiva de dichas leyes y la educación social también juegan un papel determinante.

5. Mayor riesgo en ciertos años: Los años 2021 y 2022 son particularmente preocupantes debido a picos en las agresiones registradas. Esto puede estar relacionado con un mayor activismo y visibilidad del colectivo, así como con una polarización social que se ha observado en esos años.

6. Efecto de la visibilidad mediática: Finalmente, es posible que la visibilidad en medios de comunicación y la representación del colectivo LGTBIQ+ en el debate público hayan influido en los datos. En los años en que se discutieron temas relacionados con la ley trans y otros derechos, se observó un aumento notable de las agresiones, lo que puede indicar una reacción adversa a los avances sociales.

En conclusión, estos resultados nos permiten no solo visibilizar las agresiones que enfrenta el colectivo LGTBIQ+, sino también subrayar la importancia de políticas públicas que combinen legislación y educación para reducir los delitos de odio. Asimismo, este análisis subraya la necesidad de un enfoque más específico para proteger a los subgrupos más vulnerables dentro del colectivo.
