# temario

## Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web

---

<img width="270" height="176" alt="image" src="https://github.com/user-attachments/assets/0f89a712-3030-4686-93ad-f663111b4808" />


### 1. Introducción al desarrollo web

#### Historia y evolución del desarrollo web
El desarrollo web comenzó en la década de 1990 con la aparición de los primeros sitios web y navegadores como Mosaic. Inicialmente, las páginas eran estáticas y se basaban únicamente en HTML. Con el tiempo, surgieron tecnologías como JavaScript y CSS, que permitieron mayor interactividad y estilos visuales. A partir de los años 2000, la llegada de aplicaciones dinámicas, AJAX y frameworks de JavaScript revolucionó la experiencia del usuario. Más recientemente, han surgido enfoques modernos como las aplicaciones de página única (SPA) y las aplicaciones progresivas (PWA), que ofrecen experiencias similares a las aplicaciones nativas.

#### Tipos de aplicaciones web
- **Aplicaciones estáticas**: Contenido fijo y predefinido, normalmente solo HTML y CSS, sin interacción con bases de datos.
- **Aplicaciones dinámicas**: El contenido se genera en tiempo real, generalmente con lenguajes de servidor (PHP, Node.js) y bases de datos (MySQL).
- **SPA (Single Page Application)**: La navegación y actualización de contenido ocurre sin recargar la página completa, usando frameworks como React, Angular o Vue.
- **PWA (Progressive Web App)**: Aplicaciones web que funcionan offline, pueden instalarse en dispositivos y ofrecen una experiencia cercana a una app nativa.

---

### 2. Arquitectura de aplicaciones web

#### Cliente-Servidor
El modelo cliente-servidor es la base de las aplicaciones web. El cliente (navegador) solicita recursos, y el servidor responde enviando páginas web, datos o archivos. Esta interacción se realiza mediante protocolos como HTTP.

#### Arquitectura de tres capas
- **Presentación**: Interfaz de usuario, generalmente HTML, CSS y JavaScript.
- **Lógica**: Procesamiento y reglas de negocio, implementadas en servidores con lenguajes como PHP, JavaScript (Node.js), etc.
- **Datos**: Almacenamiento y gestión de información, usualmente en bases de datos como MySQL.

Esta separación facilita la escalabilidad, el mantenimiento y la reutilización de componentes.

#### REST y API-first design
- **REST (Representational State Transfer)**: Estilo arquitectónico para crear servicios web que permiten comunicación entre sistemas usando HTTP y recursos identificados por URLs.
- **API-first design**: Enfoque en el que primero se diseña la API, asegurando que los servicios sean claros, escalables y fáciles de consumir por distintos clientes (web, móvil, otros sistemas).

---

### 3. Lenguajes y tecnologías fundamentales

- **HTML**: Lenguaje de marcado para estructurar páginas web.
- **CSS**: Lenguaje para diseñar y dar estilo visual a las páginas.
- **JavaScript**: Lenguaje de programación que añade interactividad y dinamismo en el navegador.
- **PHP**: Lenguaje de programación del lado del servidor para crear páginas web dinámicas y procesar datos.
- **MySQL**: Sistema de gestión de bases de datos relacional, utilizado para almacenar información estructurada.

---

### 4. Control de versiones

#### Git y GitHub
- **Git**: Sistema de control de versiones distribuido que permite gestionar los cambios en el código fuente de manera eficiente y colaborativa.
- **GitHub**: Plataforma basada en Git que facilita el trabajo en equipo, la colaboración y la publicación de proyectos.

#### Flujo de trabajo con ramas
- **Branching**: Crear ramas para desarrollar nuevas características o corregir errores sin afectar la versión principal del proyecto.
- **Merge**: Unir los cambios de una rama en otra, generalmente de la rama de desarrollo a la principal.
- **Pull requests**: Solicitudes para revisar y fusionar cambios, promoviendo buenas prácticas de colaboración y revisión de código.

## Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web

---
<img width="278" height="176" alt="image" src="https://github.com/user-attachments/assets/b3c30c31-8def-416b-8154-91e9aa3967b9" />


### 1. Diseño e implementación del frontend

- **Maquetación / Wireframe / Mockup**:  
  El proceso inicia con la creación de esquemas visuales para la interfaz de usuario usando herramientas como papel, Figma o Sketch. Los wireframes muestran la estructura y distribución de los elementos, mientras que los mockups presentan el diseño final con colores, tipografías y detalles visuales.

- **API**:  
  El frontend interactúa con el backend a través de APIs (usualmente REST). El consumo de APIs se realiza mediante peticiones HTTP (fetch, axios, etc.) para obtener, enviar y actualizar datos en la aplicación web.

---

### 2. Diseño e implementación del backend

- **Servidor**:  
  El backend se encarga de procesar la lógica de negocio y servir datos al frontend. Puede estar desarrollado en lenguajes como Node.js, PHP, Python, etc.

- **Manejo de peticiones y respuestas HTTP**:  
  El servidor recibe solicitudes (requests) del cliente y responde (responses) usando el protocolo HTTP. Cada ruta puede manejar diferentes tipos de peticiones (GET, POST, PUT, DELETE).

- **Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)**:  
  El backend se conecta a bases de datos relacionales (MySQL, PostgreSQL) o NoSQL (MongoDB) para almacenar y recuperar información según las necesidades de la aplicación.

---

### 3. Bases de datos

- **Modelado de datos y relaciones**:  
  Consiste en definir las entidades (tablas/colecciones), sus atributos y las relaciones entre ellas (uno a uno, uno a muchos, muchos a muchos) para representar la información de manera eficiente y coherente.

- **ORM (Object Relational Mapping)**:  
  Los ORMs permiten manipular datos de la base de datos usando objetos en el lenguaje de programación del backend. Ejemplos: Sequelize (Node.js), Doctrine (PHP), SQLAlchemy (Python).

- **CRUD desde el backend**:  
  El backend debe implementar las operaciones básicas de una base de datos:  
  - **Create** (crear registros)  
  - **Read** (leer registros)  
  - **Update** (actualizar registros)  
  - **Delete** (eliminar registros)

---

### 4. Seguridad básica en aplicaciones web

- **Validación de formularios**:  
  Es fundamental verificar los datos que los usuarios ingresan en los formularios para evitar errores y ataques como inyección de código.

- **Autenticación y autorización**:  
  - **Autenticación**: Verificar la identidad del usuario (login, registro, tokens, etc.).
  - **Autorización**: Definir qué acciones puede realizar cada usuario según su rol o permisos (acceso a rutas, modificaciones de datos, etc.).


## Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional

---

<img width="237" height="167" alt="image" src="https://github.com/user-attachments/assets/4f9602d1-4d8d-41d4-bc45-400da2bfdd6c" />


### 1. Integración de frontend y backend

- **Interfaz de usuario Frontend**  
  El frontend debe ofrecer una experiencia intuitiva y atractiva, facilitando la interacción del usuario con la aplicación. Utiliza tecnologías como HTML, CSS, JavaScript y frameworks modernos para construir interfaces responsivas y accesibles.

- **Manejo de API**  
  El frontend consume datos y servicios expuestos por el backend a través de APIs, principalmente usando el protocolo HTTP. Se realizan peticiones (GET, POST, PUT, DELETE) para enviar y recibir información relevante.

- **Proceso de Solicitud y Respuesta de Backend**  
  El backend gestiona las peticiones del frontend, procesa la lógica de negocio y responde con los datos solicitados o el resultado de las operaciones. El flujo incluye validación, acceso a bases de datos, y envío de respuestas en formatos como JSON o XML.

---

### 2. Almacenamiento en Servidor

- **Tipos de servidores**  
  Los servidores pueden ser físicos (dedicados) o virtuales (VPS, cloud), y funcionan como el entorno donde se aloja la aplicación web y sus datos.

- **Servidores y servicios de hosting**  
  El hosting provee espacio y recursos para desplegar la aplicación. Ejemplos incluyen compartido, dedicado, VPS y cloud hosting. Servicios populares: Heroku, AWS, Azure, Vercel, Netlify.

- **Proveedores de Servicios de Almacenamiento**  
  Empresas especializadas ofrecen almacenamiento escalable y seguro, tanto para archivos estáticos como para bases de datos. Ejemplo: Amazon S3, Google Cloud Storage, Firebase.

---

### 3. Optimización y rendimiento

- **Optimización de recursos (imágenes, scripts)**  
  Reducir el tamaño de imágenes, minificar scripts y hojas de estilo mejora el tiempo de carga y la experiencia de usuario. Herramientas como Webpack, Gulp y servicios de CDN ayudan a acelerar la entrega de contenidos.

- **Despliegue de aplicaciones web**  
  El proceso de despliegue implica publicar la aplicación en un servidor o plataforma de hosting. Incluye configurar entornos, subir archivos y asegurar el funcionamiento correcto en producción.

- **CI/CD básico**  
  Integración continua (CI) y entrega continua (CD) automatizan pruebas y despliegues, mejorando la calidad y velocidad de desarrollo. Herramientas comunes: GitHub Actions, Travis CI, GitLab CI.

- **Documentación del proyecto**  
  Documentar la arquitectura, funcionalidades, rutas de la API y procesos de despliegue facilita el mantenimiento y la colaboración entre desarrolladores.
