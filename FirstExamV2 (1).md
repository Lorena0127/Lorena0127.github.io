# Parcial Primero - V2
---

- [Parcial Primero - V2](#parcial-primero---v2)
  - [Instrucciones](#instrucciones)
  - [Punto 1: Herencia, Clases Abstractas e Interfaces](#punto-1-herencia-clases-abstractas-e-interfaces)
  - [Punto 2: Diagramas UML y Aplicación Completa](#punto-2-diagramas-uml-y-aplicación-completa)
  - [Punto 3: De Diagrama UML a Código](#punto-3-de-diagrama-uml-a-código)
  - [Evaluación](#evaluación)

---

## Instrucciones

El parcial consta de 3 puntos donde deben resolver solo 2 de los 3, el tercero es obligatorio y eligen entre el primer y segundo punto, en ambos deben crear el diagrama UML. Responde a cada uno de manera detallada, implementando la solución solicitada en el lenguaje de programación Java. Asegúrate de utilizar los conceptos solicitados en cada pregunta. En el punto 3, incluye un diagrama UML de la solución que propongas.


## Punto 1: Herencia, Clases Abstractas e Interfaces

**Objetivo:**
Implementar un sistema que simule una biblioteca con diferentes tipos de recursos (libros, revistas, y videos) utilizando herencia, clases abstractas e interfaces.

**Requerimientos:**
- Crea una clase abstracta `Recurso` con atributos `titulo` y `añoPublicacion`, y métodos abstractos `prestar()` y `devolver()`.
- Implementa tres subclases: `Libro`, `Revista` y `Video`, cada una con atributos y comportamiento específicos (ej: `Libro` tiene `autor`, `Revista` tiene `editor`, `Video` tiene `duracion`).
- Crea una interfaz `Digitalizable` con un método `descargar()`. Implementa esta interfaz en la clase `Video`.
- En el método `main`, crea un arreglo de diferentes recursos y recorre el arreglo usando polimorfismo para prestar y devolver cada recurso.

**Indicaciones adicionales:**
- En tu implementación, debes manejar correctamente el uso de clases abstractas e interfaces.
- Explica cómo el uso de la interfaz `Digitalizable` permite a `Video` tener comportamientos adicionales que no tienen las otras subclases.

**Diagrama UML:**
Dibuja el diagrama UML de clases que muestre la relación entre `Recurso`, `Libro`, `Revista`, y `Video`. Asegúrate de incluir las clases, atributos, métodos, y las relaciones de herencia y uso de la interfaz.

## Punto 2: Diagramas UML y Aplicación Completa

**Objetivo:**

Desarrollar una solución completa para un sistema que gestione diferentes tipos de electrodomésticos utilizando herencia e interfaces. Luego, realizar el diagrama UML de clases correspondiente.

**Requerimientos:**
- Crea una clase `Electrodomestico` con los atributos `marca`, `modelo` y `consumoEnergetico`.
- Crea dos subclases: `Lavadora` y `Refrigerador`. `Lavadora` tiene un atributo adicional `capacidadCarga`, y `Refrigerador` tiene el atributo `volumen`.
- Crea una interfaz `Operable` que tenga el método `encender()`. Tanto `Lavadora` como `Refrigerador` deben implementar esta interfaz.
- En el método `main`, crea instancias de `Lavadora` y `Refrigerador`, y utiliza polimorfismo para invocar el método `encender()`.

**Diagrama UML:**

Dibuja el diagrama UML de clases que muestre la relación entre `Electrodomestico`, `Lavadora`, `Refrigerador` y la interfaz `Operable`. Asegúrate de incluir las clases, atributos, métodos, y las relaciones de herencia e implementación de la interfaz.

## Punto 3: De Diagrama UML a Código

Implementen el código del siguiente diagrama UML de clases

<div align="center">
<img src="https://teach-ict.com/as_as_computing/ocr/H447/F453/3_3_6/defining_syntax/miniweb/images/UMLinheritdiagram.gif" width=90%>
</div>


## Evaluación
- Correcta implementación de clases, encapsulamiento, herencia y polimorfismo.
- Uso correcto de clases abstractas, interfaces, y polimorfismo .
- Diagrama UML preciso y solución completa con herencia e interfaces.

Recuerda que la claridad y la correcta implementación de los conceptos serán evaluadas cuidadosamente.