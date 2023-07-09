# Trabajo-final-Spark-Streaming

![image](https://github.com/menesesnd/Trabajo-final-Spark-Streaming/assets/131542765/261133dd-f0d2-42b2-8917-ee9934510b78)


![image](https://github.com/menesesnd/Trabajo-final-Spark-Streaming/assets/131542765/be022cf6-e9d5-4a1d-b9bb-8184c501eaf2)

En esta imagenes se muestra las sentencias de las ejecuciones en el socket , de enviar generar mensajes en el socket y contando las palabras que que se envian en el UNIX o web terminal de databricks con la sentencia nc -lk 9999 enviando cada palabra, ira contando y se ira alamcenando en un archivo hdfs que se puede apreciar en la 2da imagen.

la arquitectura seria: 

* Inicia con las configuraciones de spark context
* Luego con el Spark Streaming
* Ponemos nuestros host y puerto correspondiente en donde se almacena las salidas
* Se aplica las transformaciones y acciones necesarias que se mostraran en la consola de databricks
* Se consulta si hay almacenamiento en la ruta señalada del hdfs
* Y finalmente se observa los resultados de los rdds generados en socket contando las palabras ejecutando el star y awaittermination.
* PD: Despues de ellos se ingresa a la web terminal de databricks y se ingresara las palabras antes de ello se ejecuta nc -lk 9999.


*![image](https://github.com/menesesnd/Trabajo-final-Spark-Streaming/assets/131542765/562902c9-654a-4fa1-910c-0d7a2cf0b904)
