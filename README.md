# Visualización de datos

## Estudio de técnicas de visualización de datos (PEC2)


## Definir cada técnica de visualización de forma general.

Sankey diagrams es un diagrama de flujo específico.  
Lleva el nombre de quien lo usó en una publicación de 1898 sobre la máquina de vapor.  
Se usa para visualizar la transferencia o flujo que entra y sale en las entidades (nodos) de un sistema.  
En producción materiales, energía y residuos.  
Otros aspectos como la economía circular.  
Ejemplos:  
La herramienta web de eurostat para análisis de eficiencia energética.  
Sistema de análisis de flujo financiero.  

Icon chart usa íconos e imágenes para representar los datos.  
Se origina cuando puntos de datos aburridos se necesita sean más convincentes un gráfico atractivo.  
Usa series de íconos repetidos en una sola línea o en cuadrícula haciendo los datos más memorables.  
Ejemplos:  
Los sitios que permiten calificar productos (Amazon) usan pictogramas para mostrar resultados.  
Resultados de encuestas, datos demográficos.  

Hexagon Binning maneja el problema de muchos puntos que se sobreponen.  
Se describió por primera vez en 1987 en las técnicas de matriz scatterplot para N grande.  
Este, traza la densidad distribuida en hexágonos en lugar de puntos.  
Ejemplos:  
Hexágonos para agrupar una superficie 2d como un plano.  

## Describir el tipo de datos que se pueden representar con cada técnica.

Sankey diagrams funciona para evaluar la fuerza de la relación entre variables cualitativas o datos jerárquicos.  
Y concurren otros valores que se pueden sumar.  
Los flujos deben estar en los datos, y cada fila tiene una columna de origen y una de destino.  
Muestran cantidades conservadas dentro de los límites de un sistema definido.  

Icon chart representa datos cuantitativos.  
Los íconos en la línea o cuadrícula representan cierto número de unidades (generalmente 1, 10 o 100).  
Muestran la magnitud de una estadística, una fracción o proporción de un porcentaje.  
Puede usarse para agregar impacto visual a datos simples.  

Hexagon Binning se usa en datos muy densos con dos variables cuantitativas y una variable cualitativa simple.  
Los hexágonos se traducen en una agregación de datos más eficiente.  
El número de puntos por hexágono es N grande.  
Permite quitar la función geográfica cuando tenemos longitud y latitud.  

En la técnica sankey diagram uso los datos de pronóstico de energía y cambio climático de 2050.  
De Tom Counsell.  
Licencia de Gobierno Abierto V3.  A través de Mike Bostok.  
Usa 3 columnas y 68 registros de pronóstico.  

En el icon chart usa datos de indicadores agro ambientales para dominio de patrones de ganado.  
Licencia Creative Commons Attribution Non Commercial 3.0.  Del FAOSTAT Food And Agriculture Organization of the United Nations.  
Usa 5 columnas y 24 registros de patrones. Y 8 íconos svg.  

El hexagon binning agrega datos de población del censo de EE.UU.  
En función de regiones geográficas definidas por el área del código postal.  
Es del SuperDataScience Team.  No especifica licencia.  
Usa 3 columnas y 41mil registros detalles con código postal.  

## Comentar brevemente las tres representaciones indicando qué se representa y qué o qué aspectos muestra o demuestra cada representación.

El sankey diagram muestra cómo se convierte o transmite la energía antes de consumirse o perderse.  
Los suministros están a la izquierda y las demandas a la derecha en rectángulos.  
Se rastrea visualmente como fluye las unidades de energía a través del sistema.  
Los enlaces tienen un ancho proporcional a las unidades.  

Así ayuda a la elección de cómo producir reduciendo las emisiones, empujando al cambio físico técnico de lo que se logra.  
Por ejemplo, se puede optar por construir aerogeneradores a centrales nucleares que pierden 787.1 teravatios hora de generación térmica.  

El icon chart muestra la proporción de las principales especies de ganado y la densidad de ganado en el área de tierras agrícolas andinas.  
Con cobertura de 3 países, para el período histórico de 2018 y 2019.  
Está codificado el número con íconos de categoría de animales, cada uno equivale a 100mil unidades.  
Apilado horizontalmente.  

En el gráfico se observa más ganado, cerdos y pollos en Colombia, pero el Perú produce más ovejas.  
El máximo de colores se ha limitado al recomendado por la herramienta.  

El hexagon binning muestra la suma de salarios totales sin tener demasiadas marcas por la cantidad de detalles.  
Con los datos de longitud y latitud se construye contenedores hexagonales que recrea el área de EE.UU.  

Los Ángeles, San Francisco y Nueva York tienen salarios más representativos y se puede ver el código postal subyacente.  
Aquí, el color más oscuro para lo más representativo.  
Una sola categoría no es necesario poner leyenda.  

## Enlaces

Github  
https://github.com/jayuquina/visualizacion_datos_pec2.git  

Sankey Diagrams  
[https://public.flourish.studio/visualisation/9260674/](https://public.flourish.studio/visualisation/9260674/)  

Icon Chart  
[https://public.flourish.studio/visualisation/9308156/](https://public.flourish.studio/visualisation/9308156/)  

Hexagon Binning  
[https://public.tableau.com/views/Pec2_hexbins/Sheet1?:language=es-ES&:display_count=n&:origin=viz_share_link](https://public.tableau.com/views/Pec2_hexbins/Sheet1?:language=es-ES&:display_count=n&:origin=viz_share_link)  

## Bibliografía

How to Make Animated Sankey Charts. 2019. Clark D. https://flourish.studio/blog/animating-sankey-visualisations/.  
What is a Pictogram and When Should I Use It? 2022. Venngage. https://venngage.com/blog/pictogram/.  
HexBin Plot using R. 2016. Carlo M. https://powerbi.tips/2016/09/hexbin-plot-using-r/.  
Sankey Diagram. 2018. Bostock M. https://observablehq.com/@d3/sankey.  
Livestock Patterns. 2022. FAOSTAT. https://www.fao.org/faostat/en/#data/EK.  
Tableau Custom Charts series: Download Supplemental Materials. 2018. SuperDataScience Team. https://www.superdatascience.com/pages/yt-tableau-custom-charts-series.  
