# Normas Ley Chile (Biblioteca del Congreso Nacional)

Recuperación y limpieza de las más de 380.000 normas contenidas en Ley Chile, servicio de la Biblioteca del Congreso Nacional de Chile.
En este repositorio se comparten los cuadernos Jupyter de Python utilizados para recuperar y limpiar las normas del BCN.

## Estructura

/ids: En este directorio se encuentra el cuaderno para recuperar los IDs de todas las normas de la BCN.

/xmls: En este directorio se encuentra el cuaderno para recuperar todos los documentos XML correspondientes a las normas contenidas en el BCN.

## Recuperación

Para realizar la recuperación de las normas se utilizan dos servicios web prestados por Ley Chile. El primero es para obtener las IDs de las normas en base a una petición HTTP extraida desde la navegación de la web de Ley Chile. El segundo es un servicio web de intercambio XML que se encuentra en la documentación de los servicios web prestados por el BCN. Este en base a una ID de una norma devuelve el documento XML con toda la información de esta.