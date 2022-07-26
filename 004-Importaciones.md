# Importaciones de clase

- Se importa una clase dentro de otra para indicar al compilador que haremos uso de ella en nuestro programa.
- Se usa la sentencia import
- Se puede importar
    - Una clase
    ```Java
    import java.util.ArrayList; // Se especifica el nombre específico de la clase a importar
    ```
    - Todas las clases ded un paquete
    ```Java
    import java.util.*; // * nos ayuda a importar todas las clases dentro del paquete
    ```
    - Los métodos estáticos de una clase
    ```Java
    import static java.lang.Math.*;
    ```

    Tener cuidado con estas posibles trampas en las preguntas del examen, estas sentencias arrojan error de compilación
    ```Java
    import java.util;
    import static java.util; // No se pueden importar paquetes completos solo las clases contenidas en él
    import static java.util.ArrayList; //Siempre para importar static se debe colocar * al final
    ```

    _Las sentencias import siempre van después de la sentencia del package_