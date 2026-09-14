# CDBD - Ciencia de Datos y Tecnologías Big Data #


## Entorno de trabajo: Google Colab

Este curso se imparte íntegramente sobre **Google Colab**, por lo que no es necesario instalar Python, Docker ni ningún entorno local. Solo hace falta una cuenta de Google y conexión a internet.

### 1. Requisitos previos
1. Disponer de una cuenta de Google (Gmail o cuenta corporativa/educativa con Google habilitado).
2. Acceso a este repositorio de GitHub, donde se irán publicando los notebooks (`.ipynb`) de cada clase a medida que se impartan.

### 2. Abrir los notebooks en Colab
Hay dos formas de abrir un notebook del repositorio directamente en Colab:

1. **Desde GitHub:** entra en el notebook (`.ipynb`) dentro de este repositorio y sustituye `github.com` por `githubtocolab.com` en la URL del navegador. Esto abre automáticamente el notebook en Google Colab.
2. **Desde Colab:** entra en [colab.research.google.com](https://colab.research.google.com), ve a `Archivo > Abrir cuaderno > GitHub`, pega la URL de este repositorio y selecciona el notebook de la clase correspondiente.

**Repositorio:** https://github.com/nahumcda/cda_2026

#### Notebooks del curso

| Clase | Notebook | Abrir en Colab |
|---|---|---|
| Clase 1 - Introducción a Python | [`01_Introduccion_python.ipynb`](https://github.com/nahumcda/cda_2026/blob/main/clases/01_Introduccion_python.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nahumcda/cda_2026/blob/main/clases/01_Introduccion_python.ipynb) |
| Clase 2 - Tratamiento de datos | [`02_numpy_pandas.ipynb`](https://github.com/nahumcda/cda_2026/blob/main/clases/02_numpy_pandas.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nahumcda/cda_2026/blob/main/clases/02_numpy_pandas.ipynb) |
| Clase 3 y 4 - EDA | [`03_04_EDA vino.ipynb`](https://github.com/nahumcda/cda_2026/blob/main/clases/03_04_EDA%20vino.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nahumcda/cda_2026/blob/main/clases/03_04_EDA%20vino.ipynb) |
| Ejercicios EDA (Spotify) | [`03_04_EDA spotify ejercicios.ipynb`](https://github.com/nahumcda/cda_2026/blob/main/clases/03_04_EDA%20spotify%20ejercicios.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nahumcda/cda_2026/blob/main/clases/03_04_EDA%20spotify%20ejercicios.ipynb) |

> Ajusta la rama (`main`) en los enlaces anteriores si publicas el repositorio con otro nombre de rama por defecto.

### 3. Guardar tu propia copia
Antes de empezar a trabajar sobre un notebook, guarda una copia en tu Google Drive con `Archivo > Guardar una copia en Drive`, para poder editarlo y conservar tus cambios sin modificar el original del repositorio.

### 4. Instalación de librerías adicionales
Colab ya incluye preinstaladas la mayoría de librerías que se usarán en el curso (NumPy, Pandas, Matplotlib, etc.). Si algún notebook requiere una librería adicional, se indicará al inicio del mismo mediante una celda de código con `!pip install <libreria>`.

### 5. Acceso a los datos
Si un ejercicio necesita ficheros de datos, el propio notebook incluirá las instrucciones para descargarlos (por ejemplo, con `!wget` o `!curl` desde el repositorio) o para montar Google Drive (`from google.colab import drive`).

## Temario de clase

### Clase 1 - Introducción a Python
#### 1. Introducción a Python 
##### 1.1 Hola Mundo
##### 1.2 Funciones básicas
##### 1.3 Funciones básicas con parámetros
#### 2. Introducción a Jupyter 
##### 2.1 Funcionamiento básico
##### 2.2 Markdown
#### 3. Python Básico
##### 3.1 Tipos de objetos 
###### 3.1.1 Atributos
###### 3.1.2 Métodos
##### 3.2 Tipos básicos
##### 3.3 Estructuras simples de datos
###### 3.3.1 Listas - List
###### 3.3.2 Tuplas 
###### 3.3.3 Diccionarios - Dict
###### 3.3.4 Conjuntos - Set
##### 3.4 Estructuras mutables e inmutables
##### 3.5 Estructuras lógicas
###### 3.5.1 If Else
###### 3.5.2 While
###### 3.5.3 For
#### 4. Funciones
##### 4.1 Funciones Avanzadas
##### 4.1 Funciones Lambda
#### 5. Imports
#### 6. Compresion de listas, conjuntos y cadenas 

### Clase 2 - Tratamiento de datos
#### 1. Algebra lineal con Numpy
#### 2. Análisis de datos tabulares con Pandas

### Clase 3 - EDA 1
#### 1. Introducción al Analisis Exploratorio de datos - EDA (Exploratory Data Analysis)
#### 2. Introducción a la metodología CRISP-DM 
#### 3. Realización EDA - 1ª parte

### Clase 4 - EDA 2
#### 1. Realización EDA - 2ª parte


## Bibliografia
### CRISP-DM
* crisp_dm_methodology [https://www.sv-europe.com/crisp-dm-methodology/]
* crisp_dm_overview [https://www.ibm.com/support/knowledgecenter/en/SS3RA7_15.0.0/com.ibm.spss.crispdm.help/crisp_overview.htm]
* https://www.kdnuggets.com/polls/2014/analytics-data-mining-data-science-methodology.html
* https://www.datasciencecentral.com/profiles/blogs/crisp-dm-a-standard-methodology-to-ensure-a-good-outcome

## Datos de contacto
* Nahum de la Ballina Tamargo - nahumcda@gmail.com
