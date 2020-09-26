# 2S2020SA_artefactosApp
En esta rama se estara llevando el manejo de los ejecutables que se vayan realizando de la aplicacion TengoHambreApp

##V1.0.0
La aplicacion TengoHambreApp es una aplicacion que se encuentra realizada en NodeJS y consta de 4 aplicaciones de las cuales 3 son los modulos de cliente, repartidor y restaurante y por ultimo esta el orquestador.

##Forma de levantarlo
###Correr la aplicacion

La aplicacion consta de 4 proyectos en NodeJS los cuales son: cliente repartidor restaurante orquestador Primero se debe ingresar a la carpeta y correr npm install, para que instale los repositorios que requiere, puesto que la carpeta de node-modules se elimino para subir el repositorio de forma mas ligera

###Levantar los servidores

cada uno se puede levantar al ingresar a la carpeta, instalar los modulos npm install Luego para iniciar la aplicacion se usa el comando set DEBUG=NombreApp:* & npm start en el cual se sustituye NombreApp por el que corresponde a cada una de las descritas anteriormente
Ingresar a la UI

Para Cliente localhost:3000 Para Restaurante localhost:3100 Para Repartidor localhost:3200, el orquestador esta en el puerto 3400 pero ya que solo es como intermediario no es necesario ingresar a alguna UI

Como caso Alternativo se tiene la rama SOA_PR4

Dentro de la carpeta video_practica_6 esta el video de Sonar.
