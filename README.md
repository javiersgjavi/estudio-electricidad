# Estudio sobre la demanda y el precio de la electricidad (2017-2019)

A este repositorio tienen acceso para contribuir dos cuentas, javiersgjavi, que es mi cuenta personal, y javsolgar, que es mi cuenta para realizar los proyectos de la Universidad de Sevilla.

## ¿En qué consiste este estudio?:

Consiste en hacer un estudio sobre las series temporales de la demanda y el precio de la luz durante los años 2017, 2018 y 2019, para posteriormente intentar predecir el precio de la luz, a partir de la demanda con 24 horas de antelación.

Los datos necesarios serán extraidos de la <a href = 'https://www.ree.es/es/apidatos'>web de la REE</a>, y una vez obtenidos, le aplicaremos un proceso de clustering a los dos dataset, para posteriormente intentar caracterizar ambos datasets, con el fin de identificar cada cluster.

Una vez realizado todo el procedimiento anterior, intentaremos relacionar ambas series para responder preguntas como:

- ¿Existe relación entre precio y demanda?

- ¿Cambia esta relación por alguna circunstancia como las citadas antes: día de la semana, mes o estación, festividad ...?

Con estas respuestas, intentaremos hacer una predicción diaria, de los precios de las próximas 24 horas de septiembre de 2019.

## Contenido:

- Notebook con el código y explicación del proyecto: Estudio de la demanda y precios de la electricidad (2017-2019).ipynb
- Datasets descargados para ahorrar el tiempo de descarga.
- Pesos de la red neuronal entrenada en Google Colab: autoguardado.h5
- Imagen de la función del error obtenido durante el entrenamiento de la red: Loss.png
- Para ver el notebook con la red neuronal en Google Colab usar <a href = 'https://colab.research.google.com/drive/1V4Rjfchb_nOktsxwjWlGw4sBPgc9DCR_?usp=sharing'>este link</a>.