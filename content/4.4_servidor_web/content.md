
# Servidor Web Local

## Archivos locales vs remotos
Sabes si estás ejecutando el ejemplo desde un archivo local porque la dirección web tendrá *file://* al principio, seguido de la ruta al archivo en tu disco duro local. Por el contrario, si ves un ejemplo  alojados en un servidor remoto, la dirección web tendrá *http://* o *https://* al principio, para mostrar que el archivo ha sido recibido a través de HTTP desde un servidor remoto.

## Servidor HTTP local simple

1. Instalar Python. Si eres usuario de Windows, puedes conseguir un instalador desde la página principal de Python y seguir las instrucciones para instalarlo:

- Vé a python.org
- Debajo de la sección de Descarga, haz clic en el link para Python "3.xxx".
- En la parte superior de la página, selecciona el instalador ejecutable windows x86 y descárgalo.
- Cuando se haya descargado, córrelo.
- En la primera página de instalación, asegúrate de marcar el checkbox "Añadir Python 3.xxx al PATH"
- Clic en Instalar, luego clic en Cerrar cuando la instalación ya haya finalizado.
2. Abre la terminal bash. Para corroborar que Python está instalado, ingresa el siguiente comando:
```
$ python -V
```
3. Esto debe retornar un número de versión. Si esto esta bien, navega al directorio que contiene tu ejemplo, usando el comando cd.
```
$ cd Desktop
```
4. Ingresa el comando para iniciar el servidor en ese directorio:
```
$ python -m http.server
```
5. Por defecto, se ejecutará el contenido del directorio en un servidor web local, en el puerto 8000. puedes ir a este servidor yendo a la URL http://localhost:8000 en tu navegador web. Aquí verá el contenido del directorio listado - haga clic en el archivo HTML que desea ejecutar.