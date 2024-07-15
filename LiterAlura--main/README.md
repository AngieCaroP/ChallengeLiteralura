# 📚 Literalura

## 🚀 Practicando Spring Boot: Challenge Literalura
¡Bienvenido a ChallengeLiteralura! Una aplicación de consola en Java que te permite explorar y gestionar libros de forma sencilla. Conéctate a la API de Gutendex y almacena datos en PostgreSQL para tener todo a mano. 📖✨

## 🌟 Funcionalidades

- 🔍 **Buscar libro por título**: Encuentra libros por su título e inserta la información en la base de datos.
- 📚 **Listar libros registrados**: Visualiza todos los libros almacenados.
- 💼 **Listar autores registrados**: Ve todos los autores disponibles en la base de datos.
- 📅 **Listar autores vivos en un determinado año**: Descubre qué autores estaban vivos en un año específico.
- 🌐 **Listar libros por idioma**: Filtra libros por idioma (ES, EN, FR, PT).
- 📈 **Top 10 libros más descargados**: Consulta los libros más populares.
- 📉 **Libro más descargado y menos descargado**: Averigua cuál es el libro más descargado y el menos descargado.

## 🛠️ Requisitos

- Java 17
- Spring Boot 3.2.4
- PostgreSQL
- Maven

## 📥 Instalación

1. Clona el repositorio:
    ```sh
    git clone https://github.com/AngieCaroP/ChallengeLiteralura
    ```

2. Configura la base de datos PostgreSQL y actualiza las credenciales en el archivo
   `application.properties`.

3. Ejecuta la aplicación:
    ```sh
    ./mvnw spring-boot:run
    ```

## 💻 Uso

1. **Buscar un libro**:
   - Ejecuta la aplicación y selecciona la opción 1.
   - Ingresa el título del libro que deseas buscar.

2. **Listar libros**:
   - Selecciona la opción 2 para listar todos los libros registrados.

3. **Listar autores**:
   - Selecciona la opción 3 para listar todos los autores registrados.

## 📄 Descripción de las Funcionalidades

### 🔍 1. Buscar libro por título
La persona usuaria debe ingresar el nombre del libro que desea buscar. Por ejemplo, si se busca "Pride" (Orgullo), la aplicación debe ir a la API de Gutendex, buscar la información sobre este libro y registrarlo en la base de datos. Si el libro ya está en la base de datos, no se insertará nuevamente.

### 📚 2. Listar libros registrados
Muestra todos los libros que han sido registrados en la base de datos. Por ejemplo, libros como "Don Quijote" (Don Quijote), "Emma", "Pride and Prejudice" (Orgullo y Prejuicio), entre otros.

### 💼 3. Listar autores registrados
Muestra todos los autores que han sido registrados en la base de datos. Por ejemplo, autores como Jane Austen y William Shakespeare.

### 📅 4. Listar autores vivos en un determinado año
Permite listar los autores que estaban vivos en un año específico. Por ejemplo, en el año 1600, autores como Cervantes y Shakespeare estaban vivos.

### 🌐 5. Listar libros por idioma
Permite listar los libros por su idioma (ES, EN, FR, PT). Por ejemplo, si se busca por ES, se mostrarán los libros en español.

## 🌐 API
La aplicación utiliza la API de Gutendex para obtener información sobre los libros. Más información sobre la API está disponible en [Gutendex API](https://gutendex.com).

### 📧 Autora
- Carolina Pantoja
- [LinkedIn](https://www.linkedin.com/in/carolina-pantoja-716184144)
- Formación: Java Orientado a Objetos G6 - ONE
- Alura Latam
- Oracle Next Education