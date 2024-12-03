# Analisis y diseño de Sistema de gestion - MKS

## Contexto

Mokoso’s ha logrado cumplir los 30 años de actividad en el rubro de la venta de 
indumentaria infantil, brindando buena atención, buena calidad en sus 
productos y la fidelización de sus clientes. A pesar de eso, la falta de registros y 
automatización en sus procesos, vuelve ineficientes muchas de sus tareas 
diarias. Actualmente, la empresa enfrenta desafíos como la falta de un registro 
de inventario y de una actualización del mismo tras cada venta. Esto conlleva a 
que cada vez que tienen que realizar un pedido a sus proveedores deben 
revisar manualmente lo que necesitan desde los estantes de la tienda, o se 
enfrentan al desabastecimiento de productos específicos cuando el cliente los
solicita.
La implementación de un WMS por parte de la empresa, va a proporcionarle un 
medio para abordar estas dificultades, brindando la precisión en tiempo real de 
su inventario, lo cual ayudará a su vez a la toma de decisiones al momento de 
crear los pedidos a sus proveedores. Esto se traduce en mayor productividad y 
eficiencia, y a su vez en un mejor servicio para el cliente.

## Definiciones del Proyecto y del Sistema

### Objetivo general del proyecto

• Desarrollar un WMS (Warehouse Management System – Sistema 
de Gestión de Almacenes) para la gestión de inventarios y de 
pedidos a proveedores en Mokoso’s. 

### Objetivos específicos del proyecto

• Dar inicio a la transformación digital mejorando la eficiencia 
operativa. 
• Facilitar el proceso de toma de decisiones gracias al acceso a 
datos precisos en tiempo real.
• Brindar un sistema informático que ayude a la optimización de los 
procesos de negocio.

#### Diagrama de Gantt

Las tareas del proyecto a desarrollar se encontrarán distribuidas en un período
total de 16 semanas, lo cual equivale a 4 meses. A continuación, podemos 
visualizar su distribución en el Diagrama de Gantt:

![image](https://github.com/user-attachments/assets/1a0e1afc-66c5-446e-97ff-53489c86d73c)

### Objetivo general del sistema

• Implementar un sistema que gestione el control y actualización 
del inventario, como así también, de los pedidos a 
proveedores, dando eficiencia a las tareas diarias de 
Mokoso’s.

## Alcance del sistema

Abarcará la gestión de un inventario, el cual se actualizará con cada venta y 
con cada entrega de pedido que llegue desde los proveedores. En él también 
se podrán visualizar los precios minoristas y mayoristas de cada producto. Los 
productos estarán establecidos en categorías determinadas según las 
necesidades del cliente. Por otro lado, almacenará un registro de pedidos con 
su correspondiente detalle de pedidos a cada proveedor. El negocio podrá 
visualizar el estado de estos pedidos (creado, en preparación, enviado, 
entregado).

## Límite del alcance del sistema

No incluirá la gestión financiera, ni gestión de clientes. Estos requerimientos se 
incluyen en la lista de requerimientos candidatos en caso de en un futuro 
ampliar las funcionalidades del sistema.

## Restricciones del sistema

Este sistema deberá desarrollarse completamente en un período de 4 (cuatro) 
meses. Las tecnologías a utilizar serán MySQL para la base de datos, y Java 
para el desarrollo del software. Para la conexión entre el sistema y la base de 
datos se empleará JDBC (Java Database Connectivity). Por último, para el 
diseño de la interfaz se podrá disponer de Figma, y para el desarrollo de la 
interfaz gráfica se empleará Java Swing.

## Elicitaciones

La herramienta que se utilizará para llevar a cabo el control de todo el proceso 
de elicitación será Trello. Se trata de una herramienta de gestión de proyectos 
que permite organizar las distintas tareas en bloques llamados tarjetas, 
asignarles responsables y plazos. Por otro lado, todo el proceso estará 
plasmado en un diagrama de flujo.
El proceso de elicitación se llevará a cabo mediante dos tipos de técnicas: 
encuestas para la recopilación de datos cuantitativos, y entrevistas semi￾estructuradas para la obtención de datos cualitativos. Éstas serán 
administradas a los usuarios del sistema: la dueña de la empresa y la 
encargada de administración. Entre ambas, a su vez, se encargan de gestionar 
las ventas. 
En primer lugar, para la realización de las encuestas, las cuales tendrán un 
formato de respuesta múltiple opción, se hará uso de la herramienta Google 
Forms. Por otro lado, para las entrevistas, donde podrá profundizarse en 
detalles de los requerimientos y sus relaciones, se empleará la plataforma 
Google Meet. Con estos procedimientos podremos recolectar los 
requerimientos necesarios para desarrollar un sistema que brinde utilidad a los 
usuarios y una solución eficaz a las necesidades principales del negocio. 
Los resultados de las encuestas serán analizados a partir del uso de análisis 
estadístico. Posteriormente, se analizarán las coincidencias en ambas 
entrevistas y, por otro lado, se considerará la viabilidad de las diferencias 
detectadas. Éstas podrían ser consideradas factibles de ser incorporadas como 
requerimientos al sistema.

### Diagrama de flujo del proceso de elicitación

![image](https://github.com/user-attachments/assets/392fe676-2d0b-4bfa-b367-8bb9aa67d9f6)

### Conclusión del proceso de elicitación

Como resultado del proceso de elicitación se logró, a través de las distintas 
fases, conocer las necesidades a resolver del cliente, convirtiéndolas en 
requerimientos que sirvan como soluciones eficientes a las mismas.
Junto con los distintos actores que interactuarán con el sistema, se definieron 
una lista de requerimientos no funcionales y requerimientos funcionales que, en 
sinergia, da como resultado un sistema completo y adaptado a lo que el 
negocio necesita.
Las principales necesidades detectadas corresponden a la administración del 
inventario y la gestión de pedidos a proveedores, con su correspondiente 
almacenamiento y seguimiento. El sistema garantizará el desarrollo de estas
funciones y la simplificación del proceso de gestión del negocio.

## Análisis de Competencia

El análisis de competencia fue realizado a partir de una minuciosa investigación 
acerca de las distintas opciones disponibles en el mercado en materia de 
gestores de stock y pedidos.
Para el análisis de competencia se seleccionaron dos sistemas que abordan 
los mismos procesos que el sistema que se plantea desarrollar. Estos sistemas 
son: Fishbowl Inventory y Zoho Inventory.

| **Categoría**       | **Sistema para Mokoso’s**                                  | **Fishbowl Inventory**                      | **Zoho Inventory**                           |
|----------------------|-----------------------------------------------------------|---------------------------------------------|---------------------------------------------|
| **Funcionalidad**    | Sistema de Gestión de Inventario y de Pedidos con seguimiento de estado de pedidos. | Sistema de Gestión de Inventarios para empresas medianas. | Sistema de Control de Inventarios para empresas pequeñas y medianas. |
| **Personalización**  | Altamente personalizable.                                 | Moderada.                                   | Moderada.                                   |
| **Complejidad**      | Baja.                                                     | Moderada.                                   | Moderada.                                   |
| **Costo**            | Bajo.                                                     | Moderado a Alto.                            | Bajo a Moderado.                            |
| **Escalabilidad**    | Con altas probabilidades de mejoras.                      | Moderado a Alto.                            | Moderada.                                   |

Podemos concluir que el sistema diseñado para Mokoso’s tiene varias ventajas 
en el mercado actual comparativamente con sistemas similares ya existentes. 
Entre las ventajas que podemos visualizar son su bajo costo y que es 
altamente personalizable. Por otro lado, tiene altas probabilidades de mejora, 
las cuales se pueden extraer de la lista de requerimientos candidatos.
Por último, si bien los sistemas considerados en la comparación son más 
complejos, el sistema a desarrollar incluye la gestión de pedidos y su 
seguimiento lo cual, lo vuelve una herramienta con una utilidad de alto valor 
que las demás no poseen.

## Conocimiento del negocio

Mokoso’s, como negocio de venta de indumentaria infantil, se enfrenta a un 
gran desafío en la toma de decisiones con respecto a los detalles de pedidos a 
los proveedores para reabastecer los artículos e incorporar nuevos. El 
inventario es un elemento clave en esta instancia y debe ser correctamente 
gestionado. En una tienda de indumentaria infantil son muchos los factores que 
influyen, sobre todo en la categorización de sus productos. Un mismo artículo 
posee múltiples atributos, como son una marca, un tamaño, un color, una 
temporada, todo lo cual debe estar registrado dentro del inventario. Todos estos 
detalles no están siendo abarcados en el sistema manual actual que sostienen, 
lo que conlleva a errores y desabastecimiento afectando el rendimiento del 
negocio y la satisfacción de las necesidades del cliente.
El sistema a desarrollar permitirá la adecuada gestión del inventario, 
actualizándose con cada venta y entrada de nuevos pedidos. De esta forma, se
dispondrá en tiempo real de las existencias de su inventario, optimizando la 
toma de decisiones al momento de crear nuevos pedidos a los proveedores. 
Esto mejorará la eficiencia en las transacciones del negocio, lo cual se reflejará 
en el proceso de ventas.
Asimismo, con el nuevo sistema, Mokoso’s podrá almacenar los pedidos y 
detalles de pedidos a sus proveedores. Dentro de esta sección, se visualizarán
los productos encargados con sus respectivos precios y, tal como se encuentra 
en el inventario, estarán acompañados por su marca, temporada, talle, color, 
entre otros. Cada pedido tendrá la fecha de en la que fue realizado y se podrá 
hacer un seguimiento de su estado hasta que se entrega en el establecimiento 
del negocio. Gracias a esta funcionalidad, se facilitará el seguimiento y control 
de las compras realizadas para el negocio.

## Diagrama de Dominio

![image](https://github.com/user-attachments/assets/493f1917-fe65-428a-9711-f6befafed48f)

## Procesos de negocio

Proceso: Gestión de inventario
Roles: Cliente - Usuario - Sistema
Pasos:
• Usuario: agrega al inventario los artículos que ingresan desde 
los pedidos a proveedores.
• Sistema: almacena los nuevos artículos en el inventario.
• Cliente: compra artículos en el negocio.
• Usuario: elimina del inventario los artículos comprados por el 
cliente. 
• Sistema: actualiza el stock en el inventario.

### Diagrama de actividades del proceso Gestión de inventario:

![image](https://github.com/user-attachments/assets/5eff5807-2cf4-4c12-ba0d-97443ef3e6d0)

Proceso: Gestión de pedidos a proveedores
Roles: Usuario - Sistema
Pasos:
• Usuario: crea un nuevo pedido a proveedores.
• Usuario: ingresa los productos en el detalle de pedido.
• Sistema: almacena el pedido creado.
• Usuario: consulta el estado del pedido a proveedores.

### Diagrama de actividades del proceso Gestión de pedidos a proveedores:

![image](https://github.com/user-attachments/assets/2ff76c36-ae44-486a-9dac-45aeb479538f)

### Diagnóstico de los procesos relevados

Proceso: Gestión de inventario
Problema: Desabastecimiento al momento de la compra por parte del cliente.
Causa: Falta de control a tiempo en detalle del inventario para realizar los 
pedidos a los proveedores.

Proceso: Gestión de pedidos a proveedores
Problema: Retraso en el reabastecimiento de artículos.
Causa: Falta de control en el estado de seguimiento de los pedidos realizados 
a proveedores.

## Propuesta de solución

### Propuesta funcional

Tras el diagnóstico realizado en el negocio Mokoso's, se propone desarrollar un 
sistema de gestión de almacenes (WMS) que abarque la gestión de inventario 
y la gestión de pedidos a proveedores. Este sistema permitirá mantener 
actualizada la información sobre existencias de los productos en venta y 
facilitar la toma de decisiones al momento de realizar nuevos pedidos, 
asegurando la optimización del reabastecimiento de productos.
Cada producto del inventario contará con atributos como marca, talle (tamaño), 
color y temporada, lo que permitirá gestionar el inventario de manera detallada
y funcional a las necesidades del cliente. El sistema también incluirá la 
posibilidad de crear, almacenar y seguir el estado de los pedidos a 
proveedores, desde su creación hasta la entrega en la tienda. Los estados de 
los pedidos creados serán: creado, en preparación, enviado, entregado.

### Propuesta técnica

El desarrollo del sistema de gestión de almacenes (WMS) será desplegado en 
el lenguaje de programación Java. Este lenguaje estructurado y robusto 
permitirá la escalabilidad del sistema a medida que Mokoso’s crezca en 
volúmenes de datos, asegurando su nivel de rendimiento.
La base de datos se realizará en MySQL, una base de datos relacional que 
asegurará el manejo eficiente de la gestión de inventario y pedidos en tiempo 
real.
Para la conexión entre el sistema y la base de datos, se utilizará JDBC (Java 
Database Connectivity). Esto garantizará la sincronización de los datos de 
inventario y pedidos manteniendo el sistema actualizado.
La interfaz será diseñada con Figma y realizada en Java Spring. Esta 
herramienta nos permite una alta personalización y proporciona una gran 
facilidad de uso, brindando una interfaz intuitiva y amigable para el usuario.

## Arquitectura tecnológica

El sistema WMS se desplegará utilizando una arquitectura cliente-servidor, 
donde los usuarios (dueña y encargada de administración) interactuarán con el 
sistema a través de una interfaz desarrollada en Java Swing. Esta interfaz 
permitirá realizar las operaciones relacionadas con la gestión del inventario y 
los pedidos a proveedores.
Para el almacenamiento y procesamiento de datos, se utilizará un servidor local 
en las instalaciones de Mokoso's, asegurando la seguridad de la información y 
la rapidez en las operaciones diarias. Además, se plantea la posibilidad de 
conectar el sistema a la nube para futuras expansiones, permitiendo la 
accesibilidad remota y el respaldo de la información.
El sistema contará con un mecanismo de autenticación y control de acceso
basado en roles. Dependiendo del rol asignado, los usuarios tendrán permisos
específicos para realizar distintas acciones como la gestión de inventarios, la 
gestión de pedidos, o la consulta de estados de los mismos. Esto garantizará 
que solo los usuarios autorizados, los cuales acceden al sistema con usuario y 
contraseña, puedan acceder a las distintas funciones del sistema. Esta medida 
reducirá el riesgo de accesos no autorizados o alteraciones no deseadas en los 
datos.
Este modelo es escalable y adaptable a las necesidades del negocio, 
garantizando un crecimiento sostenido en el tiempo.

### Diagrama de Arquitectura

![image](https://github.com/user-attachments/assets/38dc5cae-8b47-4faa-8928-fab51bf776e9)

El diagrama de arquitectura plantea un paquete de análisis denominado 
“Gestión de Almacenes”. Este paquete, contiene a su vez dos paquetes los 
cuales son “Gestión de Inventario” y “Gestión de Pedidos”. De esta manera, 
logramos graficar dependencias entre subsistemas.
El paquete “Gestión de Inventario”, contiene al objeto interfaz llamado
“VentanaInventario”, y el objeto entidad “Producto”.
El paquete “Gestión de Pedidos”, contiene al objeto interfaz llamado 
“VentanaNuevoPedido”, los objetos entidad “Proveedor”, “Detalle de Pedido” y 
“Producto”.

## Definición y codificación de Requerimientos

### Lista de Requerimientos Candidatos

### Funcionalidades del Sistema

- **Gestión de Usuarios**
  - Registrar usuario
  - Iniciar sesión
  - Crear perfil de usuario
  - Ver perfil de usuario
  - Editar perfil de usuario
  - Cerrar sesión

- **Gestión de Inventario**
  - Acceder a inventario
  - Consultar inventario
  - Modificar inventario
  - Cancelar cambios en inventario
  - Agregar a inventario
  - Eliminar de inventario
  - Filtrar inventario

- **Gestión de Pedidos**
  - Acceder a pedidos
  - Crear nuevo pedido
  - Consultar detalle de pedido
  - Realizar seguimiento de pedido
  - Cancelar pedido

- **Gestión de Proveedores**
  - Almacenar nuevo proveedor
  - Modificar proveedor
  - Eliminar proveedor
  - Consultar proveedores
  - Generar reporte mensual de pedidos a proveedores

- **Requerimientos no funcionales**
  - **Seguridad**: El sistema debe resguardar la privacidad de los datos del usuario.
  - **Disponibilidad**: El sistema debe estar disponible para ser utilizado permanentemente.
  - **Escalabilidad**: El sistema debe ser capaz de mantener el mismo rendimiento a pesar del aumento del volumen de información almacenada. Capacidad máxima de stock por producto: 1000 unidades.
  - **Portabilidad**: El sistema debe poder instalarse en distintos dispositivos.
  - **Usabilidad**: La interfaz del sistema debe ser de uso intuitivo y predecible para el usuario.
  - **Mantenibilidad**: El sistema debe poder actualizarse sin interrumpir su normal funcionamiento.

- **Requerimientos técnicos**
  - El sistema será instalado en un equipo con sistema operativo Windows.
  - El sistema debe ser desarrollado completamente en un plazo de 4 meses.
  - La base de datos del sistema debe ser desarrollada en **MySQL**.
  - El sistema debe ser desarrollado con **Java**.
  - La interfaz gráfica debe ser desarrollada con **Java Swing**.
  - La conexión entre el sistema y la base de datos se realizará con **JDBC (Java Database Connectivity)**.

A continuación, se presentan los requerimientos definitivos para el desarrollo 
del sistema. Estos requerimientos serán codificados y categorizados en 
requerimientos funcionales y requerimientos no funcionales. Los requerimientos 
no considerados de la lista de requerimientos candidatos, serán tenidos en 
cuenta para posibles mejoras o ampliaciones del sistema.

### Requerimientos Funcionales

![image](https://github.com/user-attachments/assets/c40ecb68-144b-4db9-be7a-0dc367eaac42)

### Requerimientos No Funcionales

![image](https://github.com/user-attachments/assets/0480317b-35bc-4345-b251-9dc4a3d3c630)

## Inicio del análisis: Casos de Uso

### Diagrama de Casos de Uso

![image](https://github.com/user-attachments/assets/ffb95a18-00c9-4508-a976-970ae1fb0bfc)

Relaciones: include y extend.

Include:
• Consultar inventario y Modificar inventario incluyen obligatoriamente 
ingresar a Acceder a inventario.
• Crear nuevo pedido, Cancelar pedido y Consultar detalle de pedido 
incluyen obligatoriamente Acceder a pedidos.
• Almacenar nuevo proveedor, Modificar proveedor, Consultar 
proveedores y Eliminar proveedor incluyen obligatoriamente Acceder a 
proveedores.

Extend:
• Filtrar inventario extiende de Consultar inventario.
• Cancelar cambios en inventario extiende de Modificar inventario.
• Realizar seguimiento de pedido extiende de Consultar detalle de pedido.

Identificación de Actores
• Usuario: toda persona encargada de las transacciones que se 
llevan a cabo dentro del negocio Mokoso’s.
• Sistema: sistema encargado de llevar a cabo eficientemente 
todas sus funciones y responder a las transacciones 
solicitadas por el usuario.

### Mapa de Trazabilidad

| **Cod.** | **Requerimiento**         | **Caso de Uso**         | **Actor Principal** | **Comentarios**                                             |
|----------|---------------------------|-------------------------|---------------------|-------------------------------------------------------------|
| RF001    | Iniciar sesión            | CU001                   | Usuario             | El usuario ingresa sus datos e inicia sesión. El sistema valida los datos de inicio de sesión. |
| RF002    | Acceder a inventario      | CU002                   | Usuario             | El usuario solicita acceder al inventario. El sistema valida el acceso al inventario. |
| RF003    | Consultar inventario      | CU003                   | Usuario             | El usuario consulta el inventario accediendo a él. |
| RF004    | Modificar inventario      | CU004                   | Usuario             | El usuario modifica datos almacenados en el inventario accediendo a él. |
| RF005    | Agregar a inventario      | CU004                   | Usuario             | El usuario agrega nuevos datos al inventario. |
| RF006    | Eliminar de inventario    | CU004                   | Usuario             | El usuario elimina datos almacenados en el inventario. |
| RF007    | Cancelar cambios en inventario | CU005               | Usuario             | El usuario puede cancelar cambios que haya realizado en el inventario. |
| RF008    | Filtrar inventario        | CU006                   | Usuario             | El usuario puede filtrar resultados en las consultas realizadas en el inventario. |
| RF009    | Acceder a pedidos         | CU007                   | Usuario             | El usuario solicita acceder a los pedidos a proveedores. El sistema valida el acceso a los pedidos. |
| RF010    | Crear nuevo pedido        | CU008                   | Usuario             | El usuario crea un nuevo pedido a proveedores accediendo a pedidos. |
| RF011    | Consultar detalle de pedido | CU009                 | Usuario             | El usuario consulta detalle de pedido a proveedor accediendo a pedidos. |
| RF012    | Realizar seguimiento de pedido | CU010             | Usuario             | El usuario puede consultar el seguimiento de pedido realizado a proveedor. |
| RF013    | Cancelar pedido           | CU011                   | Usuario             | El usuario cancela pedido realizado a proveedor accediendo a pedidos. |
| RF014    | Acceder a proveedores     | CU012                   | Usuario             | El usuario solicita acceder a los proveedores. El sistema valida el acceso a los proveedores. |
| RF015    | Almacenar nuevo proveedor | CU013                   | Usuario             | El usuario almacena datos de nuevo proveedor accediendo a proveedores. |
| RF016    | Modificar proveedor       | CU014                   | Usuario             | El usuario modifica datos de proveedor accediendo a proveedores. |
| RF017    | Consultar proveedores     | CU015                   | Usuario             | El usuario consulta datos de proveedor accediendo a proveedores. |
| RF018    | Eliminar proveedor        | CU016                   | Usuario             | El usuario elimina proveedor accediendo a proveedores. |


### Especificación de Casos de Uso

Caso de Uso: Iniciar Sesión
Referencias: RF001-CU001

| **Actores**   | **Usuario, Sistema**                                                  |
|---------------|----------------------------------------------------------------------|
| **Descripción**| Permite al usuario ingresar al sistema de gestión a través de un nombre de usuario y contraseña. |
| **Precondición**| El usuario debe estar registrado al sistema.                        |
| **Flujo Principal**| - El usuario accede a la interfaz del sistema.                       |
|               | - El usuario debe ingresar por teclado su nombre de usuario.          |
|               | - El usuario debe ingresar por teclado su contraseña.                |
|               | - El usuario puede seleccionar la opción recordar contraseña.        |
|               | - El usuario debe seleccionar el botón de iniciar sesión.            |
|               | - El sistema debe autentificar los datos de inicio de sesión.        |
|               | - El sistema da acceso al usuario al sistema de gestión.             |
| **Flujo Alternativo**| El usuario no se encuentra registrado al sistema de gestión:   |
|               | - El usuario accede a la interfaz del sistema.                        |
|               | - El usuario se registra al sistema de gestión con un nombre de usuario y una contraseña. |
|               | - El sistema verifica que esos datos de inicio de sesión no se encuentren ya almacenados. |
|               | - El sistema almacena el nuevo nombre de usuario con su contraseña.  |
|               | - El usuario ingresa por teclado su nombre de usuario.                |
|               | - El usuario ingresa por teclado su contraseña.                      |
|               | - El usuario puede seleccionar la opción recordar contraseña.        |
|               | - El usuario selecciona el botón de iniciar sesión.                  |
|               | - El sistema debe autentificar los datos de inicio de sesión.        |
|               | - El sistema da acceso al usuario al sistema de gestión.             |
| **Postcondición**| El usuario debe cerrar sesión al finalizar la totalidad de sus tareas cada día. |
| **Excepciones**| En caso de que los datos de inicio de sesión no sean verificados por el sistema: |
|               | - El sistema redirige al usuario a la interfaz de inicio de sesión.  |
| **Mensajes que se mostrarán al usuario**| - Mensaje: "Inicia sesión o regístrate." |
|               | - Mensaje: "Tienes 3 intentos más para el inicio de sesión. Luego la cuenta será bloqueada por seguridad." |


Caso de Uso: Modificar Inventario
Referencias: RF004, RF005, RF006-CU004

| **Actores**   | **Usuario, Sistema**                                                |
|---------------|---------------------------------------------------------------------|
| **Descripción**| Permite al usuario realizar cambios al inventario del negocio, ya sea agregando, eliminando o modificando datos almacenados en él. |
| **Precondición**| - El usuario debe iniciar sesión en el sistema de gestión.          |
|               | - El usuario debe acceder al inventario.                           |
| **Flujo Principal**| - El usuario accede a la interfaz del sistema.                     |
|               | - El usuario inicia sesión en el sistema.                           |
|               | - El usuario accede al inventario.                                  |
|               | - El usuario modifica datos almacenados en inventario.              |
| **Flujo Alternativo**| Si el usuario quiere agregar un nuevo elemento en el inventario:|
|               | - El usuario accede al inventario.                                  |
|               | - El usuario agrega nuevo elemento en inventario.                    |
|               | Si el usuario quiere eliminar un elemento del inventario:           |
|               | - El usuario accede al inventario.                                  |
|               | - El usuario elimina un elemento del inventario.                     |
| **Postcondición**| - El usuario guarda y actualiza los cambios introducidos al inventario. |
|               | - El usuario cancela cambios producidos en inventario.              |
|               | - El sistema almacena los cambios.                                  |
|               | - El sistema devuelve mensaje a usuario:                            |
|               |   Mensaje: “Los cambios se almacenaron exitosamente”                |
| **Excepciones**| En caso de que el usuario no incluya todos los datos requeridos como obligatorios al ingresar un nuevo elemento: |
|               | - El sistema advierte al usuario que complete los datos faltantes.  |
|               |   Mensaje que se mostrará al usuario:                               |
|               |   Mensaje: “Ingresa todos los datos requeridos para cada elemento y vuelve a intentar.” |
|               | En caso de que el usuario intente salir de la interfaz sin guardar o cancelar los cambios: |
|               | - El sistema advierte al usuario que está saliendo de la interfaz sin guardar los cambios. |
|               |   Mensaje que se mostrará al usuario:                               |
|               |   Mensaje: “Estás saliendo de la interfaz sin guardar los cambios. Si sigues perderás los cambios realizados.” |


Caso de Uso: Crear Nuevo Pedido
Referencias: RF010-CU008

| **Actores**   | **Usuario, Sistema**                                                |
|---------------|---------------------------------------------------------------------|
| **Descripción**| El usuario crea un nuevo pedido para un proveedor. Cada pedido creado tiene un detalle de pedido. |
| **Precondición**| - El usuario debe iniciar sesión en el sistema de gestión.          |
|               | - El usuario debe acceder a pedidos.                               |
| **Flujo Principal**| - El usuario accede a la interfaz del sistema.                     |
|               | - El usuario inicia sesión en el sistema.                           |
|               | - El usuario accede a pedidos.                                      |
|               | - El usuario selecciona crear nuevo pedido.                         |
|               | - El sistema asigna un código id al pedido creado.                  |
|               | - El usuario escoge el proveedor para su pedido.                    |
|               | - El usuario selecciona los productos a pedir al proveedor.        |
|               | - El sistema almacena los productos en detalles de productos.      |
| **Flujo Alternativo**| Si el usuario decide cancelar el pedido realizado a proveedor:|
|               | - El usuario accede a pedidos.                                      |
|               | - El usuario selecciona crear nuevo pedido.                         |
|               | - El sistema almacena el nuevo pedido.                              |
|               | - El usuario cancela el pedido creado.                              |
|               | - El sistema elimina el pedido del almacenamiento del sistema.     |
| **Postcondición**| - El usuario confirma la creación del pedido.                      |
|               | - El usuario cancela la creación del pedido.                        |
|               | - El sistema muestra al usuario un mensaje con la confirmación de la acción realizada: |
|               |   Si el usuario confirma la creación del pedido:                   |
|               |   Mensaje: “El pedido fue creado y almacenado exitosamente”        |
|               |   Si el usuario cancela la creación del pedido:                    |
|               |   Mensaje: “La creación del pedido ha sido cancelada”              |
| **Excepciones**| En caso de que el usuario intente salir de la interfaz sin guardar o cancelar los cambios: |
|               | - El sistema advierte al usuario que está saliendo de la interfaz sin guardar los cambios. |
|               |   Mensaje que se mostrará al usuario:                               |
|               |   Mensaje: “Estás saliendo de la interfaz sin guardar los cambios. Si sigues perderás los cambios realizados.” |

## Etapa de Análisis

### Diagrama de Secuencia

CU01: Iniciar Sesión

![image](https://github.com/user-attachments/assets/17fe496f-6098-4f0b-8af3-e034b15a0668)

Descripción del diagrama de secuencia (CU01: Iniciar sesión):

Usuario: el usuario ingresa, en la interfaz de inicio sesión, sus datos de inicio 
de sesión (nombre de usuario como String, y contraseña como String), luego, 
pulsa en el botón iniciar sesión.
Mensaje: “Estás saliendo de la interfaz sin 
guardar los cambios. Si sigues perderás los 
cambios realizados.”

Interfaz InicioSesión: desde la interfaz InicioSesion se envía una solicitud al 
Control Verificación para verificar que los datos de inicio de sesión ingresados 
sean verídicos y poder autentificar el inicio de sesión.

Control Verificación: recibe la solicitud de verificación de datos ingresados 
para el inicio de sesión y envía una consulta a la base de datos de InicioSesion 
para verificar que esos datos se encuentren almacenados y que se hayan 
ingresado correctamente.

BaseDatos InicioSesión: analiza si los datos de inicio de sesión se 
encuentran almacenados en su base de datos. Devuelve el resultado de 
verificación de inicio de sesión al control de verificación.

Control Verificación: envía al usuario el resultado del proceso y le permite 
iniciar sesión.

CU04: Modificar Inventario

![image](https://github.com/user-attachments/assets/08140151-4ce4-40d7-a09e-8200ecce4784)

Descripción del diagrama de secuencia (CU04: Modificar inventario):

Usuario: selecciona del menú de la interfaz MenúInventario la opción modificar 
inventario.

Interfaz MenuInventario: envía a Control Acceso la solicitud de acceso hacia 
la interfaz ModificarInventario.

Control Acceso: se encarga de verificar el acceso al usuario hacia la interfaz 
ModificarInventario.

Interfaz ModificarInventario: el usuario puede acceder a la interfaz 
ModificarInventario.

Usuario: dentro de la interfaz ModificarInventario, el usuario genera 
modificaciones dentro del inventario. Estas modificaciones pueden hacerse a 
través de distintos métodos agregando, modificando o eliminando datos de la 
base de datos. Luego, pulsa el botón Modificar.

Interfaz ModificarInventario: envía una solicitud de modificación de inventario 
al Control Verificación.

Control Verificación: se envía la solicitud de modificación de inventario a la 
base de datos Inventario.

BaseDatos Inventario: devuelve al control Verificación la respuesta a la 
solicitud de modificación de inventario. Envía a la interfaz ModificarInventario la 
aceptación a la solicitud de modificación de inventario y su correspondiente 
almacenamiento.

Interfaz ModificarInventario: devuelve el mensaje de confirmación de 
modificación de inventario al usuario.

CU08: Crear Nuevo Pedido

![image](https://github.com/user-attachments/assets/d0eb930b-b530-41b6-b68b-f4a7b56b68a6)

Descripción del diagrama de secuencia (CU08: Crear nuevo pedido):

Usuario: selecciona del menú de la interfaz MenúPedidos la opción crear 
nuevo pedido.

InterfazMenúPedidos: se envía la solicitud al control Acceso para ingresar a la 
interfaz CrearPedido.

Control Acceso: se encarga de verificar que el usuario acceda a la interfaz 
CrearPedido.

Interfaz CrearPedido: el usuario puede acceder a la interfaz CrearPedido.

Usuario: ingresa en la interfaz CrearPedido la creación de nuevo pedido 
(proveedor y productos). Luego, pulsa el botón crear nuevo pedido.

Interfaz CrearPedido: envía la solicitud para la creación de un nuevo pedido al 
control Verificación

Control Verificación: envía la solicitud para el almacenamiento de un nuevo 
pedido a la base de datos NuevoPedido.

BaseDatos NuevoPedido: envía la respuesta a la solicitud de almacenamiento 
de nuevo pedido al control Verificación. Manda la aceptación/verificación de 
almacenamiento a la interfaz CrearPedido.

Interfaz CrearPedido: devuelve al usuario el mensaje de confirmación de 
almacenamiento del nuevo pedido en la base de datos.

## Etapa de Diseño

### Diagrama de Clases de Diseño

![image](https://github.com/user-attachments/assets/1121ce2e-a2ff-46cb-a700-1b21a8fe69b4)

## Etapa de Implementación

### Diagrama de Despliegue

![image](https://github.com/user-attachments/assets/f9d1db77-4df1-4006-9457-c50244d0af85)

## Etapa de Pruebas

| **Caso de Uso**              | **ID Caso de Prueba** | **Tipo de Prueba** | **Técnica propuesta**                                  | **Observaciones**                                                                                                                                               |
|------------------------------|-----------------------|--------------------|--------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| CU001: Iniciar sesión        | CPS01                 | Sistema            | Seguridad                                              | Aplicación de pruebas de seguridad en los métodos `iniciarsesion()` y `cerrarsesion()` de la clase `CuentaUsuario`. Esta prueba se enfocará en garantizar que los métodos de autenticación sean seguros, protegiendo al usuario de vulnerabilidades y accesos no autorizados. |
| CU004: Modificar inventario  | CPNF02                | No funcional       | Técnica de Volumen                                     | Se implementa en el método `agregarAInventario()` de la clase `Inventario`. La finalidad es someter al sistema a una gran cantidad de datos y evaluar su rendimiento. |
| CU004: Modificar inventario  | CPU03                 | Usabilidad         | Técnica de Inspección: ensayo cognitivo                 | Se utiliza en los métodos `agregarAInventario()`, `modificarInventario()` y `eliminarDeInventario()` de la clase `Inventario`. Se simula el paso a paso que realizará el usuario al momento de crear un pedido, buscando identificar puntos donde el usuario se bloquea o no logra completar una tarea. Esto lleva a revisar la usabilidad de la interfaz. |
| CU008: Crear pedido          | CPC04                 | Usabilidad         | Técnica de Inspección: ensayo cognitivo                 | Se utiliza en el método `crearpedido()` de la clase `Pedido`. Con esta técnica, se simula el paso a paso que realizará el usuario al momento de crear un pedido, buscando identificar puntos donde el usuario se bloquea o no logra completar una tarea. Esto lleva a revisar la usabilidad de la interfaz. |
| CU008: Crear pedido          | CPC05                 | Componente         | Integridad                                             | Se utiliza en el método `crearpedido()` de la clase `Pedido`. El objetivo es verificar que al crear el pedido desde la interfaz, los datos se registren correctamente en la base de datos, manteniendo la integridad entre las tablas `Pedido` y sus detalles (`Detalle_Pedido`). |
| CU008: Crear pedido          | CPF06                 | Prueba funcional   | Caja negra                                             | Se utiliza en el método `crearpedido()` de la clase `Pedido`. Verifica que la creación del pedido se lleve a cabo con éxito en todos sus procesos. |


| **Requerimiento** | **Descripción**                                                                 |
|-------------------|---------------------------------------------------------------------------------|
| RF019             | El sistema debe avisar si hay menos de 5 unidades en stock de un producto.     |
| RF020             | El sistema debe avisar si hay sobre stock de un producto (más de 20 unidades). |


Clases de Equivalencias Válidas

| **CEV1** | **CEV2** |
|----------|----------|
| 0 ≤ 𝑒 ≤ 5 | 5 ≤ 𝑒 ≤ 20 |


Clases de equivalencias inválidas

| **CEI1** | **CEI2** |
|----------|----------|
| 𝑒 < 0    | 𝑒 > 20   |


Análisis de valores de frontera

| **Clase de equivalencia** | **Límite frontera** | **Límite inferior** | **Límite superior** |
|---------------------------|---------------------|---------------------|---------------------|
| CEV1                      | 0                   | -1                  | 1                   |
| CEV2                      | 5                   | 4                   | 6                   |
| CEI2                      | 20                  | 19                  | 21                  |


Comportamiento del Sistema

| **Dato de entrada** | **Comportamiento esperado** | **Mensaje emitido por el sistema** |
|---------------------|-----------------------------|------------------------------------|
| -1                  | El sistema debe avisar que no hay stock del producto en inventario. | Mensaje: “El producto se encuentra sin stock” |
| 0                   | El sistema debe avisar que no hay stock del producto en inventario. | Mensaje: “El producto se encuentra sin stock” |
| 1                   | El sistema debe avisar que hay poco stock del producto en inventario. | Mensaje: “El producto se encuentra con poco stock.” |
| 4                   | El sistema debe avisar que hay poco stock del producto en inventario. | Mensaje: “El producto se encuentra con poco stock.” |
| 5                   | El sistema debe avisar que hay poco stock del producto en inventario. | Mensaje: “El producto se encuentra con poco stock.” |
| 6                   | El sistema muestra la cantidad en stock del producto en inventario. | Mensaje: “Stock del producto: (número) unidades” |
| 19                  | El sistema muestra la cantidad en stock del producto en inventario. | Mensaje: “Stock del producto: (número) unidades” |
| 20                  | El sistema debe avisar que hay sobre stock del producto en inventario. | Mensaje: “Hay sobre stock del producto.” |
| 21                  | El sistema debe avisar que hay sobre stock del producto en inventario. | Mensaje: “Hay sobre stock del producto.” |


## Definición de Base de Datos para el Sistema

### Diagrama Entidad-Relación (DER)

![image](https://github.com/user-attachments/assets/f895cc7d-aa9c-4dcb-bdd9-641243d72169)


