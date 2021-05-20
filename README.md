# Examen para formadores y tutores 
Para el ejercicio propuesto se evaluará el código, buenas prácticas de programación, diagrama de casos de uso, diagrama de clases,  programación orientada a objetos, diseño orientado a objetos (básico), SQL básico, mapeo objeto relacional, pruebas unitarias y software funcional.
* [Ejercicio propuesto](https://docs.google.com/document/d/1eahGOvMsmcjKD74_HqsvLB6umFtmDCk0bD8Fsm7lalE/edit?usp=sharing) 
* [Formulario de entrega](https://forms.gle/ySFLZFtkoNjtLaJU7)
# Requisitos

Antes de iniciar la configuración y el desarrollo asegúrese que tiene instalado lo siguiente:


* Java JDK 8
* maven ([instalación](https://www.arteco-consulting.com/instalacion-de-maven/]), [gestión de dependencias](https://www.arteco-consulting.com/tutorial-de-maven/)) 
* MySQL 8 

# Arrancar el proyecto 

Dentro de la carpeta ```mvn-template/my-exam/``` ejecutar el siguiente comando:
```
mvn package
```
El archivo ```.jar ``` generado queda en directorio creado ```target```. Para ejecutar el método main de la clase App utilizar 
```
mvn exec:java
```
o
```
java -cp target/my-exam-1.0-SNAPSHOT.jar co.gov.misiontic2022.app.App
```
Donde App es la clase que tiene el método ```main()```

# Compilar cambios

Si realiza un cambio y quiere revisar el resultado utilice:
```
mvn clean package
```

# Ejecutar test de software

Para ejecutar los test utilice:
```
mvn test
```