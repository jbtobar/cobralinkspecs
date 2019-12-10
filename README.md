# Link COBRA

## Requerimientos funcionales

---

### Reqs Generales

1. - [ ] Hay un dashboard
2. - [ ] Hay un flujo-de-pago
3. - [ ] Hay una base de datos
4. - [ ] Hay un API **??**
5. - [ ] Hay una infrastructura blockchain

### Reqs Dashboard

En el dashboard se puede:

1. - [ ] acceder via web-app
2. - [ ] ver la base de datos madre en forma de tabla
3. - [ ] filtrar las filas de la tabla por columnas
4. - [ ] añadir/editar/remover datos a la base de datos madre
5. - [ ] crear una campaña a la cual se accede via el flujo-de-pago
6. - [ ] ver resultados de campaña

### Reqs Flujo-de-Pago

El flujo de pago:


1. - [ ] se accede a traves de un url unico para cada campaña
2. - [ ] al hacer click en el link, se abre en el browser movil del usuario
3. - [ ] en la pagina inicial: el usuario ve su nombre y deuda
4. - [ ] en la pagina inicial: el usuario puede hacer click en 'Verifica tus datos', 'No me Interesa','Llamame','Aprende Mas'


Flujo "Verifica tus Datos" -> "Fin"

5. - [ ] al hacer click en 'Verifica tus datos', el usuario puede ingresar su cedula de identidad
6. - [ ] si la cedula de identidad es incorrecta, no puede proceder. Si es correcta puede proceder a 'Datos Adicionales'
7. - [ ] en la pagina de 'Datos Adicionales', el usuario puede ingresar lo siguiente: Direccion Domiciliaria (Interseccion, Numero, Barrio, Sector); Direccion de Trabajo (Interseccion, Numero, Edificio/Piso/Oficina,Sector); email; 2 telefonos adicionales; 2 Referencias (Nombre, Relacion, Numero Celular).
8. - [ ] al ingresar los datos en 'Datos Adicionales', el usuario puede proceeder a 'Metodo de Renegociacion'
9. - [ ] en la pagina de 'Metodo de Renegociacion': el usuario puede escoger entre 'Pago Immediato' y 'Pago Aplazado', y proceeder a 'Terminos y Condiciones'
10. - [ ] en la pagina de 'Terminos y Condiciones': existe un espacio donde se puede ver los terminos y condiciones del metodo de renegociacion escogijo en la pagina anterior
11. - [ ] en la pagina de 'Tereminos y Condiciones': el usuario puede hacer click en 'Acepto' y proceder a 'Forma de Pago'
12. - [ ] en la pagina de 'Forma de Pago', el usuario puede escoger entre 'Contacto Agente','Cancelar en Linea','Transferencia Manual'
13. - [ ] si el usuario escoge 'Contacto Agente',hay una pagina que confirma al usuario que un agente se pondra en contacto, y el boton de 'Finalizar'
14. - [ ] si el usuario escoge 'Cancelar en Linea', hay un espacio donde se puede colocar un "boton de pago", y el boton de 'Finalizar'
15. - [ ] si el usuario escoge 'Transferencia Manual', hay un espacio donde se puede colocar un documento PDF, y el boton de 'Finalizar'
16. - [ ] al hacer click en el boton de finalizar, el usuario procede a la pagina final


Flujo "No me Interesa"/"Llamame"/"Aprende Mas" -> "Fin"

17. - [ ] al hacer click en 'No me Interesa', hay una pagina donde existe un espacio donde se puede colocar informacion
18. - [ ] al hacer click en 'Llamame', hay una pagina que confirma que un agente se pondra en contacto
19. - [ ] al hacer click en 'Aprende Mas', hay una pagina donde existe un espacio donde se puede colocar informacion

### Reqs Base de Datos

1. - [ ]
2. - [ ] Tablas para Base Madre (Deudas), Campanas

### Reqs Infrastructura Blockchain

1. - [ ] Infrastructura blockchain utilizando implementacion de Ethereum
2. - [ ] Blockchain privado con 2 nodos en 2 servidores
3. - [ ] Logica y procesos utilizando Smart Contracts - Solidity 
