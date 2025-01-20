Los load Balancers (equilibrador de carga) son servidores que reenviar el trafico a multiples servidores (EC2) en sentido descendente 

![[Pasted image 20250118181449.png]]

Utilizarlo ya que
- Distribuye la cargar entre multiples instancias
- Expone un unico punto de Acceso [[DNS]] 
- Maneja los problemas de fallo en una instancia, si tenemos 10 instancias y una de estas comienza a fallar, el load balancer omite el trafico a esa instancia
- Comprobar la vida de la instancia
- Alta disponibilidad entre AZ


Tipos de Load Balancer por AWS
- Application Load Balancer [[ALB Application Load Balancer 1a]]
- Network Load Balancer [[NLB Network Load Balancer 1b]]
- Gateway Load Balancer [[GLB Gateway Load Balancer 1c]]
