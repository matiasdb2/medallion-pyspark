<h1>Medallion Architecture con PySpark</h1>

<h2>Descripción</h2>

En este repositorio encontrarás una notebook detallada que te guiará paso a paso en la aplicación de la Arquitectura Medallion utilizando Apache Spark, junto con el dataset necesario para trabajar. En principio la notebook está adaptada para su uso en Google Colab: contiene el código para instalar y poder utilizar PySpark en la VM de Colab.

<h2>Sobre Apache Spark</h2>

<b>Apache Spark</b> es un potente motor de procesamiento distribuido y de código abierto utilizado en el proceso de ETL (Extract, Transform, Load) en big data. Permite realizar operaciones de extracción, transformación y carga de datos a gran escala, aprovechando su capacidad de procesamiento distribuido y su capacidad de procesamiento en memoria. Spark proporciona una interfaz fácil de usar para manipular y transformar datos, permitiendo realizar análisis complejos y procesamiento de datos en tiempo real de manera eficiente.

El framework Apache Spark soporta varios lenguajes de programación, entre ellos <b>Scala, Java, Python y R.</b>

Además de estos lenguajes, existen bibliotecas y conectores disponibles para otros lenguajes como SQL, MATLAB y otros, que permiten interactuar con Spark de manera más conveniente desde diferentes entornos de programación.

<h2> Sobre la Arquitectura Medallion </h2>

La arquitectura Medallion en ETL es un enfoque modular y escalable que organiza el proceso de extracción, transformación y carga de datos en tres etapas: bronce, plata y oro.

Esta arquitectura facilita la gestión y el procesamiento eficiente de grandes volúmenes de datos.

<h2>Capas de la Medallion Architecture</h2>

<b>Capa Bronce (Bronze):</b> Esta es la capa de entrada de datos crudos o sin procesar. Aquí se almacenan los datos en su forma original, generalmente en tiempo real o en lotes. Los datos en esta capa a menudo provienen de múltiples fuentes y pueden tener una estructura y calidad variables. En esta capa, los datos se suelen almacenar en formatos como archivos CSV, JSON o registros de base de datos sin transformaciones significativas.

<b>Capa Plata (Silver):</b> En la capa Silver, los datos de la capa Bronce se procesan y transforman en un formato más estructurado y limpio. Aquí se realizan tareas como el filtrado, la validación, la deduplicación y la normalización de datos. Los datos en esta capa suelen estar en formatos como Parquet, Avro o ORC, que ofrecen compresión y eficiencia de lectura mejoradas. La capa Silver también puede incluir esquemas de datos más definidos y metadatos adicionales para facilitar su comprensión y uso posterior.

<b>Capa Oro (Gold):</b> La capa Gold es la capa final de la arquitectura Medallion, donde se encuentran los datos listos para su análisis y uso en aplicaciones empresariales. Aquí se realizan transformaciones y agregaciones más avanzadas para crear conjuntos de datos enriquecidos y preparados para análisis. Los datos en esta capa suelen estar estructurados en esquemas definidos y optimizados para consultas rápidas y análisis sofisticados. También puede incluir datos enriquecidos con información adicional o combinados con otras fuentes para obtener una visión más completa.

En resumen, la capa Bronce es la entrada de datos crudos, la capa Plata procesa y transforma los datos a un estado más limpio y estructurado, y la capa Oro proporciona datos listos para su análisis y uso empresarial. Esta arquitectura escalable y modular facilita el manejo y procesamiento de datos a gran escala.

<h2>Beneficios</h2>

<b>Escalabilidad:</b> Aprovecha la potencia del procesamiento distribuido de Apache Spark para manejar grandes volúmenes de datos y escalar tus operaciones de ETL de manera eficiente.

<b>Rendimiento:</b> Optimiza tus flujos de trabajo de ETL con el motor de computación en memoria de Apache Spark, logrando tiempos de procesamiento más rápidos y una mayor productividad.

<b>Reusabilidad:</b> Aprende cómo diseñar y construir componentes modulares de ETL utilizando PySpark, promoviendo la reutilización de código y facilitando el mantenimiento en proyectos futuros.

<b>Flexibilidad:</b> Adapta los conceptos y ejemplos proporcionados en esta notebook a tus casos de uso específicos, personalizando y ampliando los flujos de trabajo de ETL según los requisitos únicos de tu organización.

<h2>Comenzando</h2>

Para comenzar, simplemente clona o descarga la notebook desde este repositorio y ábrela en tu entorno de Colab, junto con el archivo comprimido que contiene los dataset necesarios en formato CSV. Sigue los pasos detallados y los ejemplos proporcionados para comprender y aplicar la Medallion Architecture utilizando Apache Spark.

<h3> <b> ¡Mucha suerte! Cualquier consulta estoy a disposición. </b> </h3>
