# TP1 - Programación Orientada a Objetos en Java

##  Descripción del Proyecto

Este proyecto implementa un sistema para la administración de **Eventos Universitarios**, **Salas**, **Actividades** (Charlas y Talleres) y **Estudiantes Inscriptos**, aplicando los conceptos fundamentales del paradigma orientado a objetos en Java:

* **Encapsulamiento:** Atributos privados con métodos de acceso (getters/setters) y calificadores de acceso.
* **Herencia y Clases Abstractas:** La clase abstracta `Actividad` sirve como base para `Charla` y `Taller`.
* **Polimorfismo:** Tratamiento uniforme de las actividades desde la colección en `EventoUniversitario` invocando métodos redefinidos como `calcularCostoMateriales()` y `getTipo()`.
* **Métodos Finales:** Implementación de `mostrarIdentificacion()` como método `final` en la clase base para evitar su redefinición.
* **Relaciones entre Clases:**
  * **Agregación:** Entre `EventoUniversitario` y `Sala` (la sala existe independientemente del evento).
  * **Composición:** Entre `EventoUniversitario` y `Actividad` (las actividades nacen y existen como parte del evento).
  * **Asociación / Inscripción:** Entre `Actividad`, `Inscripcion` y `Estudiante`.

