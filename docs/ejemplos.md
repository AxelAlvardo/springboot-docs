# Ejemplos

## Crear un controlador REST

=== "Java"

````
```java
@RestController
public class HolaController {

    @GetMapping("/hola")
    public String hola() {
        return "Hola Mundo";
    }
}
```
````

=== "Kotlin"

````
```kotlin
@RestController
class HolaController {

    @GetMapping("/hola")
    fun hola(): String {
        return "Hola Mundo"
    }
}
```
````

!!! tip "Práctica"
Ejecuta la aplicación y accede a:
http://localhost:8080/hola

Volver al [Inicio](index.md).
