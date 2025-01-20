
## **Escalando y protegiendo tus bases de datos RDS con réplicas de lectura y Multi-AZ**

AWS RDS ofrece dos características clave para optimizar el rendimiento y la disponibilidad de tus bases de datos: réplicas de lectura y Multi-AZ.

### **Réplicas de lectura**
Las réplicas de lectura te permiten escalar la carga de trabajo de lectura de tu base de datos principal. Esto significa que puedes crear hasta 15 réplicas adicionales para manejar consultas de solo lectura, mejorando significativamente el rendimiento de tu aplicación.

### **Multi-AZ**
La configuración Multi-AZ proporciona una alta disponibilidad para tu base de datos. Al replicar tu base de datos en una zona de disponibilidad (AZ) diferente, AWS RDS puede conmutar automáticamente a la réplica en caso de fallo de la AZ principal, minimizando el tiempo de inactividad.

**Beneficios clave:**

* **Mayor rendimiento:** Las réplicas de lectura alivian la carga de la base de datos principal, mejorando el rendimiento de las consultas de solo lectura.
* **Alta disponibilidad:** Multi-AZ garantiza que tu base de datos esté disponible incluso en caso de fallos en una zona de disponibilidad.
* **Escalabilidad:** Puedes agregar o quitar réplicas de lectura según tus necesidades cambiantes.


![[Pasted image 20250119155225.png]]