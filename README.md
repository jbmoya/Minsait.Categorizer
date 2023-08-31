# Librería de Predicción con ML.Net para UiPath

Esta librería de UiPath permite utilizar fácilmente un modelo de Machine Learning entrenado (FastTree) con ML.Net para hacer predicciones dentro de un proceso automatizado. 

## Descripción

La librería encapsula la funcionalidad del proyecto "Proyecto de Predicción con ML.Net" y expone métodos simples para consumir el modelo y obtener una predicción a partir de nuevos datos de ejemplo para su utilización en Uipath. 

Esto permite incorporar capacidades de Machine Learning en procesos RPA creados con UiPath.

## Características

- Recibe como parámetros el path archivo del modelo y los nuevos datos
- Devuelve la predicción y el score correspondiente
- Fácil de usar en procesos UiPath

## Dependencias

- Proyecto de Predicción con ML.Net (incluido). Categorizer180.1.0.1.nupkg
- UiPath Studio

## Uso

1. Importa la librería en UiPath Studio (Origen de packages local) y la libreria Categorizer180
2. Utiliza le metodo Minsait.Categorizer e informa los parametros de entrada y salida
3. Obtén la predicción y el score para usar en tu proceso

## Ejemplo

![Descripción de la imagen](/ejemplo1.png)

## Licencia

MIT

¡Espero que este ejemplo te sirva para documentar tu librería UiPath! No dudes en indicarme si necesitas más información.