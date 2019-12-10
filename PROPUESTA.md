# Link COBRA

## Propuesta

---

1. Desarrollo infrastructura Blockchain
2. Desarrollo Front-End integrado a UpLink - Angular v7
3. Desarrollo Back-end API y Base de Datos - MySQL

4. Tiempo de desarrollo 4-5 semanas maximo

---

### Cotizacion

#### Desarrollo Inicial

 - infrastructura Blockchain
 - **dashboard web-app**
 - **flujo-de-pago para campañas**
 - **base de datos MySQL**
 - **API para conectar dashboard/flujo-de-pago con MySQL/Blockchain**
 

 - seguimiento continuo con equipo desarollo Link Mobile de inicio a fin
 - Pruebas MVP antes de lanzar producto
 - Soporte Mensual tecnico del desarollo

#### Mantenimiento y Supervision

 - Infrastructura de operacion con garantia de servicio (minimo 2 servidores)
 - Reporteria mensual - documento detallando performance
 - Atencion a posibles inconvenientes en el servicio back-end

---

### Arquitectura

 - Servidores UpLink
  - Dashboard web-app
  - **flujo-de-pago?**


 - Servidores ADOM-COBRA
  - infrastructura blockchain
  - base de datos MySQL

---

### Notas sobre costos mensuales:



 - 1M de usuarios - 5 requests al dia = 5M requests al dia
 - 5M % 24 horas % 60 minutos % 60 segundos = 58 requests por segundo

 

 - 1 servidor por cada 10 requests por segundo = 6 servidores de 1GB RAM = 60$
 - 1 load balancer para applicaciones = 20$
 - 1 load balancer para DB = 20$
 - 100GB en servidores para base de datos - o 10 servidores de 10GB = $200
 - DigitalOcean Outgoing Traffic a 1TB = 20

 
 - Total Mensual DigitalOcean = 60+20+20+100+20 = $220*** 

 
 - Total Mensual AWS = 600$
 

 
