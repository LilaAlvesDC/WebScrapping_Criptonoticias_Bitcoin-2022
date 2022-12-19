# Nube de palabras a partir de noticias 

Este repositorio contiene un script de Python para realizar un análisis de noticias de criptomonedas generadas durante el años 2022.
 
- [Nube de palabras a partir de noticias](#nube-de-palabras-a-partir-de-noticias)
  - [Esquema](#esquema)
  - [Prerequisitos](#prerequisitos)
  - [Descripción del script](#descripción-del-script)
  - [Resultados](#resultados)
  - [Ejecución del script](#ejecución-del-script)
  - [Autor](#autor)
  - [Licencia](#licencia)

## Esquema

- Preparamos nuestro entorno de trabajo    
- Descarga del modelo de    lenguaje español        
- Importar librerías       
- Scrapeo de noticias       
- Procesamiento del texto con    spacy        
- Análisis de frecuencia de palabras    
- Generación de    nubes de palabras
  
## Prerequisitos

Para ejecutar este script es necesario tener instaladas las siguientes librerías:
 - spacy
 - matplotlib
 - pandas
 - numpy
 - wordcloud
 - BeautifulSoup4

También es necesario descargar el modelo de lenguaje español de spacy ejecutando `!python -m spacy download es_core_news_sm` en la línea de comando.

## Descripción del script

El script realiza las siguientes tareas:

1. Prepara el entorno de trabajo instalando las librerías necesarias y descargando el modelo de lenguaje español de spacy.
2. Realiza un scrapeo de noticias de criptomonedas de la página web https://www.criptonoticias.com/.
3. Procesa el texto obtenido con spacy para eliminar palabras vacías y símbolos de puntuación, y realiza algunas normalizaciones.
4. Analiza la frecuencia de aparición de cada palabra en el texto.
5. Genera una nube de palabras a partir del texto procesado.


## Resultados

A continuación se muestra una imagen con la nube de palabras generada a partir del texto procesado:

![WordCloud_Bitcoin_2022](Bitcoin_2022.png)

## Ejecución del script

Para ejecutar el script, simplemente debes abrir el archivo en tu entorno de desarrollo y ejecutarlo. Asegúrate de tener las librerías necesarias instaladas y de haber descargado el modelo de lenguaje español de spacy antes de ejecutar el script.

## Autor

Este script ha sido creado por @LilaAlvesDC como parte de un proyecto de análisis de datos.

## Licencia

Este script se distribuye bajo la licencia GNU General Public License. Puedes usar y modificar el código para tus propios proyectos, siempre y cuando menciones al autor original y distribuyas el código bajo la misma licencia.
