# Clases en Java

- Conjunto de atributos y métodos.
- Se definen en archivos .java que al ser compilados generan un arcivo .class.
- Se describe el comportamiento de determinado tipos de abstracciones de mundo real.
- Una clase es una plantilla para la creación de tantos objetos como se desee.
- Un archivo .java pude contener varias clases, aunque solo una con el modificador _public_ cuyo nombre debe coincidir con el nombre del archivo.
- Las clases contienen atributos, constructores y métodos.
- La creación de nuevos objetos se hacen por medio del operador _new_.
- Las clases se organizan en paquetes (directorios).
- Los paquetes se definen con la sentencia _package_. Debe ser la primera línea del .java.
- Los paquetes pueden o no contener clases, hay paquetes que contiene tan solo subpaquetes.

## Método Main

Es el punto de entrada a una aplicación Java SE. Debe estar en una clase pública y tener el siguiente formato definido:

```Java
public static void main (String args []){

}
public static void main (String [] args){ // Número variable de argumentos ...

}
public static void main(String ... data){

}
```


Tener en cuenta que pueden existir varios métodos main en la misma clase, siempre y cuando el tipo de la lista de argumentos sea diferente.

```Java
public static void main (String args []){

}
public static void main (int args []){

}
public static void main (Object args []){

}

```