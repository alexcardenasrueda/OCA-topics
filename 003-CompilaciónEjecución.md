# Compilar y ejecutar archivos Java

Los comandos para realizar la compilación y la ejecución vienen dentro de el JDK de java

## Compilar archivo

En el directorio donde se encuentra el archivo, escribir

```Java
javac NombreArchivo.java
```

Si la clase está definida en un paquete, escribir

```Java
javac -d . NombreArchivo.java
```

## Ejecutar archivo

En el directorio raiz desde el que se realizó la compilación, escribir:

java NombreClaseMain  ------------------ Tener en cuenta que no es el nombre del archivo sino de la clase por lo tanto
va sin el nombre de la extensión .java

Si está dentro de un paquete

```Java
java paquete.NombreClaseMain

```
_El comando "java" toma el nombre de la clase como parámetro_

## Pasar argumentos al main

```Java
java NombreClaseMain arg1 arg2

```
### Si el argumento es un String que contiene espacios

```Java
java NombreClaseMain "valor arg1" arg2
```



_Para ejecutar estos comandos no olvidar configurar las variables de entorno dentro del SO_