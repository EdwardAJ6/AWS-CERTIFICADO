
Para migraciones de datos altas

![[Pasted image 20250118232304.png]]


## Familia AWS Snowball 
- [[SnowCone 1a]]
- [[Snowball Edge 1b]]
- [[SnowBall Mobile 1c]]

### Un flujo sencillo para transferir grandes cantidades de datos a AWS

1. **Solicita tu Snowball:**
   * Accede a la consola de gestión de AWS.
   * Solicita el envío de un dispositivo Snowball a la ubicación de tu elección.

2. **Prepara tu entorno:**
   * Descarga e instala el cliente de Snowball o AWS OpsHub en tus servidores.
   * Configura el cliente para conectarse al dispositivo Snowball.

3. **Copia tus datos:**
   * Conecta físicamente el dispositivo Snowball a tu red.
   * Utiliza el cliente para transferir tus datos al Snowball de forma segura y eficiente.

4. **Devuelve el dispositivo:**
   * Una vez completada la transferencia, devuelve el Snowball a la dirección indicada por AWS.
   * AWS se encargará de recoger el dispositivo y transportarlo a sus instalaciones.

5. **Carga a S3:**
   * Los datos transferidos al Snowball serán cargados automáticamente a un bucket de Amazon S3 que hayas especificado previamente.

6. **Borrado seguro:**
   * Como medida de seguridad, los datos del Snowball serán borrados por completo una vez finalizado el proceso de transferencia.

