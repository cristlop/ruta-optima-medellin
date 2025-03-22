**Ruta Óptima para la Reducción de Accidentes en Medellín**

**Descripción del Proyecto**

Este proyecto busca aplicar algoritmos de búsqueda informada, específicamente A*, para encontrar rutas óptimas en la ciudad de Medellín que minimicen el riesgo de accidentes de tránsito. A partir de datos históricos de siniestralidad, se genera un grafo representativo del territorio, ponderando zonas según la gravedad y frecuencia de los accidentes.

**Objetivo**

Diseñar un sistema capaz de sugerir rutas más seguras entre dos puntos de Medellín, considerando la cantidad y severidad de accidentes ocurridos en diferentes zonas de la ciudad. El objetivo es ayudar a ciudadanos, tomadores de decisiones y plataformas de movilidad a reducir la exposición al riesgo vial.

**Archivos del Repositorio**

* Proyecto_final_ruta_optima.ipynb: Notebook principal con el desarrollo completo del proyecto.
* Ruta óptima para la reducción de accidentes en Medellín.pdf: Documento final del proyecto escrito.
* Presentación Proyecto final - ruta optima.pptx: Presentación final del proyecto.
* requirements.txt: Archivo con todas las dependencias necesarias para ejecutar el notebook.

**Requisitos**

Este proyecto fue desarrollado en Google Colab, pero también puede ejecutarse localmente si se instalan las siguientes dependencias:

<br>pandas
<br>numpy
<br>matplotlib
<br>seaborn
<br>scikit-learn
<br>scipy

**Para instalar todo de forma rápida:**
<br>pip install -r requirements.txt

**Estructura del Proyecto**

1. Carga y preparación del dataset
2. Conversión de gravedad de accidentes a costos numéricos
3. Clusterización con K-Means para reducción de nodos
4. Construcción de grafo con KDTree
5. Implementación del algoritmo A* con heurística Manhattan
6. Cálculo de la ruta óptima entre origen y destino
7. Visualización e interpretación de resultados
8. Cómo ejecutar el proyecto

**Cómo ejecutar el proyecto**

1. Descarga o clona el repositorio:
git clone https://github.com/cristlop/ruta-optima-medellin.git
cd ruta-optima-medellin

2. Instala las dependencias:
<br>pip install -r requirements.txt

3. Abre y ejecuta el archivo Proyecto_final_ruta_optima.ipynb en Jupyter Notebook o Google Colab.

**Ejemplo de resultados**

* Ruta óptima encontrada:
[(6.26127, -75.56396), (6.25788, -75.56154), (6.25334, -75.56236), (6.24953, -75.56027), (6.24668, -75.55908)]
* Costo total de la ruta: 8.31 (ponderado por gravedad de accidentes)
La ruta evita zonas con alta siniestralidad como La Candelaria, cumpliendo el objetivo de minimizar el riesgo.

**Referencias**

* Portal de Datos Abiertos del Distrito de Medellín. (s.f.). Base de datos de accidentes de tránsito. https://medata.gov.co/node/16692
* Norvig, P., & Russell, S. (2020). Artificial Intelligence: A Modern Approach (4ta ed.). Pearson.
* Scikit-learn documentation: https://scikit-learn.org/stable/
* KDTree (scipy.spatial): https://docs.scipy.org/doc/scipy/reference/generated/scipy.spatial.KDTree.html

**Autor**
<br>Cristian López Chaverra
