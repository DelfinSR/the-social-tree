# The Social Tree - El Árbol Social

[![Version](https://img.shields.io/badge/version-1.0.0-green.svg)](https://github.com/antoniommff/the-social-tree/releases)
[![Python](https://img.shields.io/badge/python-3.12.X-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/jupyter-notebook-orange.svg)](https://jupyter.org/)


## Content table

- [About - Acerca de](#about)
- [Usage - Uso](#usage)
- [Documentation - Documentación](#documentation)
- [Contact - Contacto](#contact)



<a name="about"></a>
## About - Acerca de

[EN]
**In this project conducted in collaboration with [Delfín Santana](https://github.com/DelfinSR), we have performed a study of *relational metrics* for a dataset in the form of a graph that can be used to train a relational machine learning model**.

Using the programming language *Python* and leveraging libraries such as *[scikit-learn](https://scikit-learn.org/stable/)*, we extracted relational features from a graph with over 20,000 *Facebook* pages to determine which group each belonged to. The groups the pages could belong to are: 'politicians', 'government organizations', 'TV shows', and 'companies'.

After training and evaluating several models with various combinations of metrics and hyperparameters, **we concluded that a classification tree algorithm (*CART*) is the most suitable for this machine learning task**. On the other hand, **using the [node2vec](https://snap.stanford.edu/node2vec/) library, we managed to train a classification algorithm using a *Knn* model with an accuracy of over 90%**, even greater than the previously mentioned.

In the following sections, we explain how to run the *Jupyter* notebooks with the code and summarize what you will find in the study document.

[ES]
**En este proyecto realizado en conjunto con [Delfín Santana](https://github.com/DelfinSR) hemos realizado un estudio de métricas relacionales para un conjunto de datos en forma de grafo que sirvan para entrenar a un modelo de aprendizaje automático relacional**. 

Usando el lenguaje de programación *Python* y ayudándonos de librerías como *[scikit-learn](https://scikit-learn.org/stable/)*, hemos obtenido características relacionales de un grafo con más de 20,000 páginas de *Facebook* para averiguar a qué grupo pertenecía cada una de ellas. Los grupos a los que podía pertenecer las páginas eran los siguientes: politicos, organizaciones gubernamentales, programas de televisión y empresas. 

Tras entrenar y evaluar varios modelos con varias combinaciones de métrica e hiperparámetros, **hemos concluído que un algoritmo de árboles de clasificación (*CART*) es el más adecuado para esta tarea de aprendizaje automático**. Por otro lado, **usando la librería [node2vec](https://snap.stanford.edu/node2vec/), conseguimos entrenar un algoritmo de clasificación usando un nodelo *Knn* con una precisión de más del 90%**, incluso mayor que la anteriormente mencionada. 

En los siguientes apartados explicamos cómo ejecutar los cuadernos de *Jupyter* con el código y resumimos qué podrás encontrar en documento del estudio realizado.



<a name="usage"></a>
# Usage - Uso

0. Download necessary programmes and libraries - Descargar programas y librerías necesarias:

[EN]
To start our project and experiment with the trained models, we recommend following these steps:
First, we recommend using the version of `Python 3.12.8` or higher, which is the one we have used for all notebooks. Also, you must install the latest version of `Jupyter notebook` to run the notebooks with the code, and `Conda`, which will be necessary to run *Jupyter* and some libraries such as *numpy*. Finally, the following libraries used throughout the code will have to be installed:

Note: in operating systems such as MacOS it will be necessary to use `brew` or `Homebrew` to install some packages, it is recommended to use the specific documentation in each case.

[ES]
Para poner en marcha nuestro proyecto y experimentar con los modelos entrenados recomendamos seguir los siguientes pasos:
Primero, recomendamos usar la versión de `Python 3.12.8` o superior, que es la que hemos usado para todos lo cuadernos. También, deberás instalar la última versión de `Jupyter notebook` para ejecutar los cuadernos con el código, y `Conda` que será necesario para ejecutar tanto *Jupyter* como algunas librerías como *numpy*. Por último, habrá que tener instaladas las siguienes librerías que se usan a lo largo de todo el código:

Nota: en sistemas operativos como MacOS será necesario hacer uso de `brew`o `Homebrew` para instalar algunos paquetes, se recomienda usar la documentación específica en cada caso.

- [Matplotlib](https://matplotlib.org/stable/install/index.html) (>= 3.9)
- [Networx](https://github.com/networkx/networkx) (>= 3.3)
- [Numpy](https://numpy.org/install/) (>= 2.0.0)
- [SciPy](https://scipy.org/install/) (>= 1.13.X)
- [Scikit-learn](https://scikit-learn.org/stable/install.html) (>=1.5)
- [Pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html) (>=2.2.X)

1. Clone the repository - Clonar el repositorio:

[EN]
First, you must clone our repository or download the folders and place them in the desired location.

[ES]
Primero, deberás clonar nuestro repositorio o descargar las carpetas y colocarlas en la ubicación deseada.

2. Download the data - Descargar los datos:\\

[EN]
Next, you will have to download the *Facebook* data used to train the models. You must download them and enter them in the folder called `facebook_large` or name the folder of the data you download with the same name. In any case, the folder with the data must be at the same directory level as the `cadernos` folder.

[ES]
Seguidamente, deberás descargar los datos de *Facebook* utilizados para entrenar a los modelos. Debes descargarlos e introducirlos en la carpeta llamada `facebook_large` o nombrar la carpeta de los datos que descargues con ese mismo nombre. En cualquier caso la carpeta con los datos debe estar en el mismo nivel de directorio que la carpeta `cuadernos`.

**Link - Enlace: https://snap.stanford.edu/data/facebook-large-page-page-network.html**

3. Run the notebooks! - ¡Ejecutar los cuadernos!

[EN]

[ES]


<a name="documentation"></a>
# Documentation - Documentación



<a name="contact"></a>
# Contact - Contacto



