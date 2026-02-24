# Primera Entrega - Análisis de Videojuegos de PlayStation

## Descripción del Proyecto
Este repositorio contiene mi primer proyecto de análisis exploratorio de datos (EDA). El objetivo es analizar el catálogo de videojuegos de PlayStation para entender mejor cómo se distribuye la oferta en el mercado, identificando las tendencias en géneros y las empresas con mayor participación.

Este análisis puede resultar de interés para estudiantes del sector de los videojuegos, creadores de contenido o jugadores que quieran conocer métricas de la industria.

## Preguntas a responder
A través del código, se busca contestar las siguientes preguntas iniciales:
1. ¿Cuáles son los géneros de videojuegos más frecuentes?
2. ¿Qué estudios desarrolladores (developers) tienen más juegos en este catálogo?
3. ¿Qué empresas (publishers) lideran la publicación de estos títulos?

## Fuente de Datos
Para este trabajo se consumió la API pública y gratuita de *SampleAPIs* (`https://api.sampleapis.com/playstation/games`). Esta API es de acceso libre y no requiere autenticación (API Key). 
El código implementado descarga los datos y genera de forma automática un archivo local llamado `videojuegos_playstation.csv` para resguardar la información.

## Herramientas Utilizadas
El proyecto fue desarrollado en Python dentro de un Jupyter Notebook, empleando las siguientes librerías:
* **Pandas:** Para la estructura, limpieza y exploración de los datos.
* **Matplotlib:** Para la creación de gráficos de barras que facilitan la interpretación de los resultados.
* **Requests:** Para la conexión y descarga de información desde la API.

## Conclusiones Principales
A partir de las visualizaciones generadas en el Notebook, se obtuvieron las siguientes respuestas:
* **Géneros:** Existe una clara dominancia del género *Action Role-playing*, seguido en segundo lugar por *Hidden Object*.
* **Empresas Líderes:** La compañía *Square Enix* destaca significativamente en el catálogo, ocupando el primer puesto tanto en el desarrollo como en la publicación de videojuegos.
