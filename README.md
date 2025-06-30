Aquí tienes la traducción al español, manteniendo los nombres de las variables en inglés:

---

# Full Stack: Sitio Web de Comercio Electrónico con Angular y Java Spring Boot

## Descripción general

Este repositorio contiene el código de un sitio web de comercio electrónico construido usando Angular para el front-end, Spring Boot para el back-end y MySQL como base de datos. Este proyecto fue desarrollado siguiendo la materia de Tecnologías de Desarrollo de Aplicaciones Web en el grupo 4BM2 bajo el Dr. José Asunción Enríquez Zárate. Trabajé en este sitio web para ayudarme a aprender más sobre el desarrollo Full Stack. El front-end está desarrollado en Angular usando el lenguaje de programación TypeScript y se conecta con el back-end a través de una API REST. El back-end está construido usando el framework Spring Boot con el lenguaje de programación Java, el cual utiliza JDBC para conectarse a una base de datos MySQL con el fin de almacenar y recuperar los datos necesarios.

## Funcionalidades

* **\[Product listing]**: Listado de productos disponibles por categoría y visualización de los detalles de un producto.
* **\[Searching]**: Búsqueda de productos disponibles por palabra clave.
* **\[Pagination]**: Paginación de los productos según la página actual y el tamaño de página.
* **\[Shopping Cart]**: Carrito de compras para todos los productos deseados, con operaciones CRUD como: agregar un nuevo producto, listar los productos deseados, actualizar la cantidad de un producto y eliminar un producto del carrito.
* **\[Checkout Form]**: Posibilidad de finalizar la compra con el carrito, llenando los campos requeridos, y guardar el pedido.
* **\[Login/Logout]**: Seguridad en la autenticación y autorización de usuarios usando Okta.
* **\[Members-Only Pages]**: Rutas accesibles solo para personas autenticadas.
* **\[Handling Browser Refresh]**: Almacenamiento del carrito en el almacenamiento local/sesión del navegador web para que los datos no se pierdan al actualizar la página.
* **\[Order History]**: Visualización de todos los pedidos realizados por un cliente, asegurando la API para que solo usuarios autenticados puedan acceder al endpoint del historial de pedidos.

## Tecnologías Utilizadas

* **Angular 16.2.1**: Framework de componentes para el front-end que permite construir aplicaciones web de una sola página.
* **TypeScript 5.1.6**: Lenguaje de programación que añade tipado estático con anotaciones opcionales a JavaScript.
* **Spring Boot 3.1.2**: Framework para el back-end que permite crear aplicaciones web en Java.
* **Java 17.0.8**: Lenguaje de programación orientado a objetos que produce software para múltiples plataformas.
* **MySQL 8.0.17**: Sistema de gestión de bases de datos relacional.
* **Okta 2.1.6**: Plataforma en la nube para la gestión de identidad y acceso que permite la autenticación y autorización segura y conveniente de usuarios.

## Primeros Pasos

### Prerrequisitos

* **Node.js y npm**: Angular requiere Node.js, que incluye npm (Node Package Manager) para gestionar paquetes y dependencias.
* **Angular CLI**: Instalar Angular CLI globalmente con npm, ya que proporciona las herramientas necesarias para crear, compilar y ejecutar aplicaciones Angular.
* **Editor de Código**: Se necesita un editor de código para visualizar o escribir código. Las opciones populares para Angular son Visual Studio Code o WebStorm, y para Java Spring Boot se puede usar IntelliJ.
* **Java Development Kit (JDK)**: Asegúrate de tener una versión compatible del JDK instalada en tu sistema. Spring Boot es compatible con JDK 8, 11 y 16 (o posteriores).

### Instalación

1. Clonar el repositorio: `git clone https://github.com/NesiCodes/Fullstack-Ecommerce-Web.git`
2. Navegar al directorio `db-scripts`: `cd 01-stater-files/db-scripts`
3. Ejecutar cada script SQL usando MySQL Workbench para crear el esquema de base de datos y las tablas requeridas.
4. Navegar al directorio del back-end: `cd 02-backend/spring-boot rest api`
5. Abrir el proyecto en IntelliJ IDE y dejar que Maven construya e instale automáticamente las dependencias requeridas.
6. Navegar al directorio del front-end: `cd frontend/angular-ecommerce`
7. Instalar Angular CLI: `npm install -g @angular/cli`
8. Instalar las dependencias del front-end definidas en `package.json`.

## Uso

1. Iniciar el servidor del back-end: Navegar a la raíz del proyecto desde la línea de comandos y ejecutar `mvn spring-boot:run` o ejecutar la clase `SpringBootEcommerceApplication` en IntelliJ IDE.
2. Iniciar el servidor de desarrollo del front-end: Navegar a la raíz del proyecto desde la línea de comandos y ejecutar `ng serve` o correr la aplicación desde WebStorm IDE.
3. Acceder a la aplicación desde un navegador web en `http://localhost:4200`.

### Diagrama de Relaciones entre Entidades

![img9](https://github.com/NesiCodes/Fullstack-Ecommerce-Web/assets/89842810/5c3fc1da-45ce-4ae2-a155-f654f91fca9a)

