# Modelo Cliente-Servidor

![Cliente-servidor](https://upload.wikimedia.org/wikipedia/commons/1/1c/Cliente-Servidor.png)

Desde el punto de vista funcional, se puede definir la computación Cliente/Servidor como una arquitectura distribuida que permite a los usuarios finales obtener acceso a la información en forma transparente.
En el modelo cliente servidor, el cliente envía un mensaje solicitando determinado servicio o información a un servidor (hace una petición) y este último envía uno o varios mensajes
con la respuesta (provee el servicio).

![Petición HTTP](https://cursodecreacionweb.files.wordpress.com/2012/08/cliente_servidor1.png)

## Cliente
El cliente es el proceso que permite al usuario formular los requerimientos y pasarlos al servidor, se le conoce con el término _front-end_.

El Cliente normalmente maneja todas las funciones relacionadas con la manipulación y despliegue de datos.

Las funciones que lleva a cabo el proceso cliente se resumen en los siguientes puntos:
- Administrar la interfaz de usuario.
- Interactuar con el usuario.
- Recibir resultados del servidor.
- Formatear resultados.
- Exponer el flujo de datos de la lógica del negocio.

## Servidor
Es el proceso encargado de atender a múltiples clientes que hacen peticiones de algún recurso administrado por él. Al proceso servidor se le conoce con el término _back-end_.

El servidor normalmente maneja todas las funciones relacionadas con la mayoría de las reglas del negocio y los recursos de datos.

Las funciones que lleva a cabo el proceso servidor se resumen en los siguientes puntos:
- Recibir y procesar los requerimientos de los clientes.
- Procesar y extraer información de bases de datos.
- Formatear datos en diferentes formatos para trasmitirlos a los clientes.
- Realizar validaciones a nivel de bases de datos.
- Resguardar de manera segura datos sensibles.
- Procesar la lógica del negocio.

# Flujo de datos
1. El navegador va al servidor DNS y encuentra la dirección real del servidor donde el sitio web vive.
2. El navegador envía un mensaje de petición HTTP al servidor, pidiéndole que envíe una copia de la página web para el cliente. Este mensaje y todos los datos enviados entre el cliente y el servidor, se envían a través de tu conexión a Internet usando TCP/IP.
3. Siempre que el servidor apruebe la solicitud del cliente, el servidor enviará al cliente un mensaje "200 OK", que significa, "¡por supuesto que puedes ver ese sitio web! Aquí está.", y comenzará a enviar los archivos de la página web al navegador como una serie de pequeños trozos llamados paquetes de datos.
4. El navegador reúne los pequeños trozos, forma un sitio web completo y te lo muestra.

# Explicando las partes
1. Conexión a Internet: Permite enviar y recibir datos en la Web.
2. TCP/IP: Protocolo de Control de Transmisión y Protocolo de Internet, son los protocolos de comunicación que definen cómo deben viajar los datos a través de la Web.
3. DNS: Los servidores del Sistema de Nombres de Dominio (DNS, por sus siglas en inglés), son como una libreta de direcciones de sitios web. Cuando escribes una dirección web en el navegador, el navegador busca los DNS antes de recuperar el sitio web. El navegador necesita averiguar en qué servidor vive el sitio web y así enviar los mensajes HTTP al lugar correcto.
4. HTTP: El Protocolo de Transferencia de Hipertexto es un protocolo de aplicación que define un idioma para que los clientes y servidores se puedan comunicar.
5. Archivos de código: los sitios web se construyen principalmente con HTML, CSS y JavaScript, aunque te encontrarás con otras tecnologías más adelante.
6. Recursos: Este es un nombre colectivo para el resto de materiales que conforman un sitio web, como imágenes, música, video, documentos de Word, archivos PDF, etc.