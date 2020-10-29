# Twitter-Streamer-Sentimiento

Utilizando Spark y Spark ML en lenguaje Python, aplicar Machine Learning a datos de la red social que prefieras con el fin de hacer algún tipo de predicción. 

Uso de herramientas como la API de la red social, realizar el trabajo en Databricks u otros servicios y uso de analizador de sentimientos como Texblob.

Spark Streaming recibe los datos de la API de Twitter por sockets. 
Spark Engine (Core) procesa datos utilizando ‘foreachRDD’ y luego los analizamos con Vader y TextBlob.
Dstream no es más que una abstracción proporcionada por Spark Streaming que representa a una secuencia de RDDs ordenados en el tiempo que cada uno de ellos guarda datos de un intervalo concreto.
