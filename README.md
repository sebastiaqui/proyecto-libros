###Sistema de Gestión de Libros en Línea

#### Descripción del Proyecto

- Este proyecto es un pequeño sistema de gestión de libros en linea, realizado con Nodejs, el cual permite a los usuarios realizar operaciones como agregar, eliminar, actualizar y buscar libros. Ademas se utilizo un sistema de autenticaión básico utilizando JSON web tokens;

#### Funcionalidades Principales
- **API REST:**
  - Crear, leer, actualizar y eliminar libros.
  - Campos requeridos para los libros: título, autor, año de publicación y estado (disponible, reservado).

- **Autenticación:**
  - Sistema de autenticación básico utilizando JWT.
  - Solo los usuarios logeados pueden realizar operaciones de creación, edición y eliminación de libros.

- **Interfaz de Usuario:**
  - Interfaz intuitiva para  interactuar con la API.
  - Permite a los usuarios realizar operaciones disponibles.

#### Tecnologías Utilizadas
- Node.js
- Express.js
- MongoDB
- JSON Web Tokens (JWT)

#### Estructura del Proyecto
  - `/src`: Archivos fuente del proyecto.
  - `/routes`:Archivos de configuración de Passport.js.
  - `/config.js`:Este archivo contiene los datos para la conexion a la base de datos.
  - `/db.js`: Este archivo establece una conexion a una base de datos MongoDB.
  - `/server.js`:Este archivo contiene las bibliotecas necesarias, para dar entrada al aplicativo, encontramos temas de seguridad, de incio de sesion, configuración de rutas e inicio del servidor.
  
#### Instalación y Ejecución
1. Clona este repositorio: `git clone https://github.com/tu_usuario/tu_proyecto.git`.
2. Instala las dependencias: `npm install`.
3. Configura la base de datos y el archivo `config.js`.
4. Ejecuta el proyecto: `npm run dev`.

#### Documentación
La documentación de la API está disponible en `/api-docs`.

#### Contribuciones
¡Contribuciones son bien recibidas!. 

#### Licencia
Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE.md](LICENSE.md) para más detalles.



