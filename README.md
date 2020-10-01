# Seguridad Domótica
Página web realizada como trabajo en la Universidad. 
Esta práctica ha sido desarrollada por 3 compañeros más.

## Contenido de la práctica
La práctica se basa en el desarrollo de una página web de una empresa de seguridad domótica.
Se distribuye en dos interfaces diferentes que son las siguientes:

* Interfaz del cliente: con esta interfaz el cliente puede consultar y modificar algunos de los servicios que tiene contratado, además de añadir más servicios si esta interesado en ellos. En dicha solicitud, el cliente registrará la petición en la página web y el empleado será el encargado de dar de alta dicho servicio.

* Interfaz del empleado de la empresa: el empleado es el encargado de dar de alta los servicios que el cliente quiere contratar y de realizar modificaciones necesarias sobre ellos y sobre el cliente. Este empleado puede tener varios clientes asociados, cada uno con sus servicios contratados.

En el sistema de notificaciones simplemente está implementado la interfaz (no tiene funcionalidad), es decir, esta el historial de notificaciones pero nunca cambia pase lo que pase. Lo único que alerta este sistema es, si el empleado añade algún tipo de servicio en el cliente, en la interfaz del cliente le salta una ventana emergente notificándole de dicho cambio. En la interfaz del empleado este sistema no cambia nunca, es solo visual.

Cada una de las interfaces tiene un login diferente, dependiendo del tipo de usuario que utiliza la página web. Dicho login se encuentra en el directorio "Pagina web seguridad domotica" como un archivo .txt.

## Despliegue de la página web
Para poder desplegar la página web, hay que descargarse el directorio de "Pagina web seguridad domotica" del repositorio como un archivo comprimido. Cuando descomprimes la carpeta comprimida en tu ordenador local, debes abrir el archivo .html llamado "LoinApp" y a partir de ahí interaccionar con la página web. Para poder cambiar de interfaces, es necesario cerrar sesión en la que te encuentras, para iniciar sesión en la otra interfaz.
