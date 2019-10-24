## CS13303 - Computación en Java

En esta actividad se podrá aplicar el uso de las excepciones para su correcto funcionamiento dentro del código.

### CS13303T06 - Instrucciones de Control de flujo 

#### Actividad 1

Actividad 8

Crear archivo JAR

Crear un archivo Manifest.mf con el siguiente contenido:

Manifest-version: 1.0

Main-Class: cloud/Main

Las dos lineas deben estar pegadas, una encima de otra**

En la segunda línea colocar el nombre de la clase que contiene el método public static void main (String[] args) {}

Correr el siguiente comando

jar -cvfm out.jar Manifest.mf cloud/*.class cloud/*/*.class

Donde:

- out.jar es el nombre del archivo de salida
- Manifest.mf es el nombre del archivo manifiesto
- cloud/*.class indica que se deben incluir todas las clases en el archivo .jar
- cloud/*/*.class indica que se deben incluir todas las clases de todas las subcarpetas en el archivo .jar
