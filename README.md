# Proyecto-RecSys-Pearl

## Descripción

Este proyecto tiene como objetivo testear el dataset PEARL para el entrenamiento de LLMs y evaluar un sistema recomendador conversacional.  Se entrenaron 3 modelos de lenguaje,siento estos Llama3.2, Gemma2 y Phi3.5 mini.

## Estructura del proyecto

``` bash
Proyecto-RecSys-Pearl
│   README.md
└── Modelos
│   │   Llama3.ipynb
│   │   Gemma2.ipynb
│   │   Phi.ipynb
└── ModelosEntrenados
│   │   lora_llama3_model_train.zip
└── Data
│   │   formatted_test.json
│   │   formatted_train.json
│   │   formatted_validation.json
```

## Modelos

Dentro de este directorio se encuentran los notebooks del entrenamiento y testeo realizado sobre cada modelo ya entrenado y en formato zero shot. Todos los notebooks ya se encuentran ejecutados y para poder replicar los resultados se debe tener en cuenta que se debe tener acceso a la GPU de Google Colab y simplemente ejecutar las celdas de código.

## Modelos Entrenados

Dentro de este directorio se encuentran los modelos ya entrenados y en formato zip. Para poder utilizar estos modelos se debe descomprimir el archivo y cargar el modelo en el notebook correspondiente.

## Data

Dentro de este directorio se encuentran los archivos json que contienen los datos de entrenamiento, validación y testeo. Estos archivos son necesarios para poder entrenar y testear los modelos.
