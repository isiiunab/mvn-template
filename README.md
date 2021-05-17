# mvn-template

# Requisitos

Antes de iniciar la configuración y el desarrollo asegúrese que tiene instalado lo siguiente:


* Java JDK 8
* maven 
* MySQL 8

# Arrancar el proyecto 

Para compilar el código utilizar:
```
mvn package
```
El archivo ```.jar ``` queda en directorio creado ```target```. Para ejecutar el método main de la clase App utilizar 
```
mvn exec:java
```
o
```
java -cp target/my-exam-1.0-SNAPSHOT.jar co.gov.misiontic2022.app.App
```