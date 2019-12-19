# Propuesta Link COBRA
---

Requerimientos Funcionales escritos por Juan Bernardo Tobar (JBT).

Este documento describe los requerimientos del proyecto de LINK Cobra que JBT propone desarrollar. Este documento refleja de manera completa los requerimientos. Esto significa que si se responde 'Si' a todos los items en esta lista formulados de la manera; "*es verdad que___________?*" esta etapa del proyecto se da por terminado y JBT tiene derecho a cobrar los precios mencionados en cada sección.

**Resumen**
*Costos Iniciales*
 - Dashboard: 2k USD
 - Campaña ("Flujo de Pago"): 3k USD
 - Back-end: Incluido en costo de "Campaña"

*Costos Mensuales*
 - Costo Mensual Fijo: 100 USD para mantener todos lo requerimientos en este documento
 - Costo Mensual Variable: Costo a proveedores terceros de infraestructura, servicios que incluyen la mantención de los requerimientos en este documento son a 100 USD x hora.
---

## Dashboard

**Precio: 2k**

1. - [ ] existe un dashboard accesible vía la web
2. - [ ] se ve una base de datos de deudas en forma de tabla
3. - [ ] se puede filtrar las filas de la tabla de deudas por columnas
4. - [ ] se puede añadir deudas individuales
5. - [ ] se puede añadir deudas en masa vía tabla excel
5. - [ ] se puede hacer click para "crear una campana"
6. - [ ] se puede ver base de datos de campaña en forma de tabla




## Campaña ("Flujo de Pago")

**Precio: 3k**

1. - [ ] el "crear una campana" significa que un SMS es enviado con un link URL
2. - [ ] al hacer click en el link, se abre un portal en el browser móvil del usuario
3. - [ ] en la pagina inicial: el usuario ve su nombre y deuda
4. - [ ] en la pagina inicial: el usuario puede hacer click en 'Verifica tus datos', 'No me Interesa','Llámame','Aprende Mas'


Flujo "Verifica tus Datos" -> "Fin"

5. - [ ] al hacer click en 'Verifica tus datos', el usuario puede ingresar su cedula de identidad
6. - [ ] si la cedula de identidad es incorrecta, no puede proceder. Si es correcta puede proceder a 'Datos Adicionales'
7. - [ ] en la pagina de 'Datos Adicionales', el usuario puede ingresar lo siguiente: Dirección Domiciliaria (Intersección, Numero, Barrio, Sector); Dirección de Trabajo (Intersección, Numero, Edificio/Piso/Oficina, Sector); email; 2 teléfonos adicionales; 2 Referencias (Nombre, Relación, Numero Celular).
8. - [ ] al ingresar los datos en 'Datos Adicionales', el usuario puede proceder a 'Método de Renegociación'
9. - [ ] en la pagina de 'Método de Renegociación': el usuario puede escoger entre 'Pago Inmediato' y 'Pago Aplazado', y proceder a 'Términos y Condiciones'
10. - [ ] en la pagina de 'Términos y Condiciones': existe un espacio donde se puede ver los Términos y condiciones del método de renegociación escogido en la pagina anterior
11. - [ ] en la pagina de 'Términos y Condiciones': el usuario puede hacer click en 'Acepto' y proceder a 'Forma de Pago'
12. - [ ] en la pagina de 'Forma de Pago', el usuario puede escoger entre 'Contacto Agente', 'Cancelar en Línea','Transferencia Manual'
13. - [ ] si el usuario escoge 'Contacto Agente',hay una pagina que confirma al usuario que un agente se pondrá en contacto, y el botón de 'Finalizar'
14. - [ ] si el usuario escoge 'Cancelar en Línea', hay un espacio donde se puede colocar un "botón de pago", y el botón de 'Finalizar'
15. - [ ] si el usuario escoge 'Transferencia Manual', hay un espacio donde se puede colocar un documento PDF, y el botón de 'Finalizar'
16. - [ ] al hacer click en el botón de finalizar, el usuario procede a la pagina final


Flujo "No me Interesa"/"Llámame"/"Aprende Mas" -> "Fin"

17. - [ ] al hacer click en 'No me Interesa', hay una pagina donde existe un espacio donde se puede colocar información
18. - [ ] al hacer click en 'Llámame', hay una pagina que confirma que un agente se pondrá en contacto
19. - [ ] al hacer click en 'Aprende Mas', hay una pagina donde existe un espacio donde se puede colocar información

20. - [ ] los resultados de este proceso son enviados a la base de datos en la tabla de campañas 

## Back-end
**Precio: incluido en precio de Campaña**
1. - [ ] existe un servidor que sirve al "Flujo de Pago"
1. - [ ] existe una base de datos MySQL en este servidor
2. - [ ] la base de datos tiene una tabla para deudas
3. - [ ] la base de datos tiene una tabla para campañas
4. - [ ] el servidor envía un SMS vía un API de LINK al deudor
5. - [ ] existe una infraestructura blockchain a la cual es posible integrar cualquier proceso o data de este proyecto


---

## Costos Mensuales

Hay 3 costos mensuales
1. **Costo Personal:** 100$ x mes. Mantenimiento de que funcionen todos los requerimientos mencionados en este documento.
2. **Costos de Infraestructura:** costos de infraestructura/servidor son cubiertos por LINK y van directo a los proveedores de los servicios
3. **Costos servicio adicional:** cualquier servicio que no sea mantener los requerimientos mencionados en este documento son a $100 x hora.

