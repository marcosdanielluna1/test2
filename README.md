# Pasos para generar el jar de la aplicación

1. Instalar el jar sportalclientesweb-1.19.0.jar en la ruta: Maven\repository\sanitas\bravo\clientes\sportalclientesweb\1.19.0\

2. Desde la ruta donde desplegamos el proyecto (..sanitas/test2/) ejecutamos en la cmd el siguiente comando: **mvn clean install -U**

Con esto conseguimos descargar las dependencias y limpiar el target de la aplicación en caso de que tenga algun jar anterior y genera contruye un nuevo jar test2-1.0-SNAPSHOT.jar