
cache para DynamoDB

## DynamoDB Accelerator - DAX

* Caché en memoria totalmente gestionada para DynamoDB
* Mejora del rendimiento x 10 - latencia de un milisegundo a microsegundos - al acceder a tus tablas de DynamoDB
* Seguridad, alta escalabilidad y alta disponibilidad
* Diferencia con ElastiCache a nivel de CCP: DAX sólo se utiliza y se integra con DynamoDB, mientras que ElastiCache puede utilizarse para otras bases de datos


### **¿Cómo funciona DAX?**

DAX almacena una copia en caché de los datos más recientes de tus tablas de DynamoDB. Cuando una aplicación realiza una solicitud de lectura, DAX busca primero en la caché. Si los datos están en la caché, se devuelve inmediatamente a la aplicación. Si los datos no están en la caché, DAX los recupera de DynamoDB y los almacena en caché para futuras solicitudes.**Ideal para:**

* Aplicaciones con altas tasas de lectura y baja latencia.
* Juegos en línea y aplicaciones móviles.
* Aplicaciones de análisis en tiempo real.
