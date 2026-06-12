# project-connectatel
**Proyecto S7 - Análisis del comportamiento de usuarios de ConnectaTel**
**Objetivo del proyecto**
El objetivo de este proyecto es analizar el comportamiento de los clientes de ConnectaTel para identificar diferencias en los patrones de uso entre los planes Básico y Premium. A partir del análisis exploratorio de datos, se busca obtener información que ayude a comprender el consumo de los usuarios y apoyar la toma de decisiones del negocio.

**Datasets utilizados**
El análisis se realizó utilizando los siguientes conjuntos de datos:
users.csv: información demográfica y del plan contratado por cada usuario.
usage.csv: registros del uso de servicios, incluyendo llamadas y mensajes.

**Herramientas y tecnologías utilizadas**
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

**Etapas del análisis realizadas**
1. Carga y exploración inicial de los datos
Importación de los datasets.
Revisión de la estructura y tipos de datos.
Identificación de valores faltantes.
2. Limpieza y preparación de datos
Conversión de variables al tipo de dato adecuado.
Reemplazo de valores inválidos (?, -999, fechas fuera de rango).
Evaluación del mecanismo de ausencia de datos (MAR).
Tratamiento de valores faltantes según el contexto del negocio.
3. Análisis exploratorio de datos (EDA)
Análisis descriptivo de variables numéricas y categóricas.
Estudio de la distribución de edades y tipos de plan.
Comparación del comportamiento de los usuarios según el plan contratado.
Identificación y evaluación de valores atípicos mediante el método IQR.
4. Visualización de datos
Histogramas.
Diagramas de caja (boxplots).
Comparaciones entre planes Básico y Premium.
5. Conclusiones
-se encontraron varias columnas con valores nulos, sentinels y valores atipicos
-se hicieron segmentos por uso y edades,donde las personas en el rango de adultas son las que mas usan los planes telefonicos y el uso tendio a ser moderado.
**Interpretación de los principales hallazgos.**
Recomendaciones basadas en los resultados obtenidos.
-Los valores faltantes en duration y length corresponden a la naturaleza de los registros y se clasificaron como MAR (Missing At Random).
-Los valores atípicos identificados representan comportamientos reales de usuarios de alto consumo y se mantuvieron en el análisis.
-Se observaron diferencias en los patrones de uso entre los planes Básico y Premium.
**Cómo ejecutar el notebook**
Opción 1: Google Colab
Descarga el archivo S7 Version-Estudiante-Project-ConnectaTel.ipynb.
Ingresa a Google Colab.
Selecciona Archivo > Subir notebook.
Carga el archivo del proyecto.
Sube también los datasets necesarios al entorno de trabajo.
Ejecuta las celdas en orden.
Opción 2: Jupyter Notebook
Clona este repositorio:
git clone <URL_DEL_REPOSITORIO>
Instala las dependencias necesarias:
pip install pandas numpy matplotlib seaborn jupyter
Abre Jupyter Notebook:
jupyter notebook
Ejecuta el archivo S7 Version-Estudiante-Project-ConnectaTel.ipynb.

**Guía de reproducción**
Para reproducir el análisis:
Descarga o clona el repositorio.
Asegúrate de contar con los datasets utilizados en el proyecto.
Verifica que las rutas de los archivos coincidan con tu entorno local o de Colab.
Ejecuta el notebook desde la primera celda hasta la última sin omitir pasos.
Revisa las visualizaciones y conclusiones generadas para replicar los resultados obtenidos.

**Autor**
Carlos Olaya
Analista de Datos en formación – TripleTen
