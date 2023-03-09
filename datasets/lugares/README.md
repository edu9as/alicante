# Datasets de Lugares de interés en la provincia de Alicante

Esta carpeta contiene un conjunto de datos descargados de la página web https://trips.alicanterunaway.com/ con información sobre los lugares de interés turístico en la provincia de Alicante. Los datos incluyen el nombre del lugar, el tipo de lugar (parque, museo, playa, monumento, etc.), el enlace al lugar en la web de donde se obtuvieron los datos, una breve descripción y las coordenadas de todos los lugares de interés.

## Estructura de la carpeta

La carpeta está estructurada de la siguiente manera:

```
├── alicante_places.csv
└── README.md
```

* `runaway.csv`: archivo CSV con los datos descargados de https://trips.alicanterunaway.com/.
* `README.md`: archivo que describe el contenido de la carpeta.

## Descripción de los datos

El archivo CSV "runaway.csv" contiene los siguientes campos:

* name: nombre del lugar.
* type: tipo de lugar (parque, museo, playa, monumento, etc.).
* url: enlace al lugar en la web de donde se obtuvieron los datos.
* description: breve descripción del lugar.
* latitude: coordenada de latitud del lugar.
* longitude: coordenada de longitud del lugar.

Los datos en el archivo CSV están separados por comas y cada fila representa un lugar de interés diferente en la provincia de Alicante.

## Uso de los datos

Los datos en este conjunto pueden ser utilizados para diversos proyectos y análisis relacionados con la industria turística y la planificación urbana. Los usuarios pueden utilizar las coordenadas de latitud y longitud para visualizar los lugares de interés en un mapa o para calcular la distancia entre los diferentes puntos de interés. Además, la información sobre los tipos de lugares puede ayudar a los usuarios a identificar patrones y tendencias en los lugares de interés más populares de la provincia de Alicante.

Se recomienda que los usuarios revisen la página web de donde se obtuvieron los datos (https://trips.alicanterunaway.com/) para obtener más información sobre los lugares de interés individuales.