# Tarea: Mi prompt profesional

## Funcionalidad elegida
Gestión de Inventario (CRUD de Productos en Java Swing).

## Version 1: prompt basico
```text
Hazme un codigo para agregar productos a un inventario.
```

## Version 2: prompt medio
```text
Actua como desarrollador Java. Crea un modulo CRUD para gestionar un inventario de productos utilizando Swing. Debe permitir agregar, listar y eliminar productos con codigo, nombre, precio y stock. Presenta el codigo estructurado.
```

## Version 3: prompt final
```text
Actua como un desarrollador Java Senior especializado en arquitectura de software. 
Desarrolla un modulo de gestion de inventario (CRUD de productos) en Java Swing para una tienda de abarrotes. 

Requisitos especificos:
- Los productos deben tener los atributos: codigo, nombre, precio (double) y cantidad en stock (int).
- Proporciona botones para Agregar, Eliminar y Listar productos.
- Restriccion: No utilices librerias externas ni frameworks (solo Java estándar con Swing), y valida que el precio sea un numero mayor a 0 antes de guardar.
- Sigue las mejores practicas orientadas a objetos, separando el modelo de datos (clase Producto) de la interfaz grafica.

Formato de respuesta:
Explica brevemente la estructura de clases antes de presentar los bloques de codigo independientes.
```
## Componentes del prompt final
| Componente | Texto de mi prompt |
|------------|--------------------|
| Rol |Actua como un desarrollador Java Senior especializado en arquitectura de software. |
| Instruccion |Desarrolla un modulo de gestion de inventario (CRUD de productos) en Java Swing... Proporciona una interfaz grafica con botones para Agregar, Eliminar y Listar productos. |
| Contexto |...para una tienda de abarrotes. Los productos deben tener los atributos: codigo (String), nombre (String), precio (double) y cantidad en stock (int). |
| Ejemplo |Sigue las mejores practicas orientadas a objetos, separando el modelo de datos (clase Producto) de la interfaz grafica. |
| Formato | Explica brevemente la arquitectura propuesta antes de presentar los bloques de codigo independientes para cada clase.|



## Evaluación del resultado
| Criterio | Cumple (Si/No) |
|------------|--------------------|
| ¿Usa Java Swing sin librerías externas ni frameworks? | Si|
| ¿Aplica la validación solicitada para el precio (> 0)? | Si|
| ¿Separa la clase Modelo (Producto) de la Interfaz Gráfica? |Si |
| ¿Sigue el formato de respuesta especificando la explicación previa? | Si|

## Errores frecuentes evitados

- Ser demasiado general: En la V1 no se especificaron el lenguaje, la interfaz gráfica ni los atributos del producto. Se evitó en la V3 definiendo claramente la tecnología (Java Swing), el tipo de aplicación (tienda de abarrotes) y los tipos de datos de cada campo (codigo, nombre, precio, stock).

- No indicar el formato: En las iteraciones iniciales el modelo mezclaba la explicación con el código en un único archivo gigante. Se evitó solicitando explícitamente una síntesis de la arquitectura previa y bloques de código independientes por cada clase.


- [Tarea: Mi prompt profesional](prompts/TAREA.md)