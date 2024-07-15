# Cliente Literatura

Este proyecto es una aplicación de ejemplo que utiliza Spring Framework y Java para interactuar con una API externa de libros y autores. La aplicación permite realizar búsquedas de libros por título, listar libros registrados, listar autores registrados, buscar autores que estaban vivos en un determinado año y listar libros por idioma.

## Funcionalidad

- **Buscar libro por título:** Permite al usuario buscar un libro específico por su título utilizando una API externa.
- **Listar libros registrados:** Muestra todos los libros almacenados en la base de datos local junto con su autor, idioma y número de descargas.
- **Listar autores registrados:** Muestra todos los autores almacenados en la base de datos local junto con su fecha de nacimiento y fallecimiento.
- **Listar autores que estaban vivos en un determinado año:** Permite al usuario ingresar un año y muestra todos los autores que estaban vivos en ese año según la base de datos local.
- **Listar libros por idioma:** Permite al usuario seleccionar un idioma y muestra todos los libros disponibles en ese idioma según la base de datos local.

## Propósito

El propósito de esta aplicación es demostrar el uso de Spring Framework para integrar datos de una API externa y almacenarlos en una base de datos local. Además, muestra cómo gestionar entidades relacionadas (autores y libros) utilizando JPA (Java Persistence API).

## Tecnologías Utilizadas

- Java
- Spring Framework (Spring Boot, Spring Data JPA)
- Hibernate (como implementación JPA)
- Jackson (para el mapeo JSON)
- Maven (para la gestión de dependencias)
- H2 Database (base de datos embebida para desarrollo)
- API externa para obtener datos de libros y autores
