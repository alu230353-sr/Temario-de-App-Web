# Temario-de-App-Web
## Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web.  
<ins># 1.-Introducción al desarrollo web </ins>
El desarrollo web es el proceso de crear sitios y aplicaciones accesibles a través de internet. A lo largo de los años, ha evolucionado desde simples documentos de texto hasta complejas aplicaciones interactivas que ofrecen experiencias similares a las aplicaciones nativas.

---

## Historia y Evolución del Desarrollo Web

- **1991:** Tim Berners-Lee publica el primer sitio web, marcando el inicio de la World Wide Web.
- **Década de 1990:** Los sitios web eran principalmente documentos estáticos en HTML con imágenes y enlaces.
- **Finales de los 90:** Se introduce CSS, permitiendo separar contenido y presentación.
- **2000s:** JavaScript se populariza, permitiendo interactividad básica en las páginas web.
- **2005:** AJAX revoluciona la web, haciendo posible la actualización de partes de una página sin recargarla por completo.
- **Década de 2010:** Nacen los frameworks y librerías como Angular, React y Vue, facilitando el desarrollo de aplicaciones web complejas.
- **Actualidad:** Surgen nuevas arquitecturas como las aplicaciones de página única (SPA) y aplicaciones progresivas (PWA), acercando la experiencia web a la de las aplicaciones nativas.

---

## Tipos de Aplicaciones Web

### 1. Aplicaciones Web Estáticas

- **Descripción:** Son páginas cuyo contenido no cambia dinámicamente. Cada usuario ve lo mismo.
- **Tecnologías:** HTML, CSS.
- **Ejemplo:** Portafolios, landing pages sencillas.

### 2. Aplicaciones Web Dinámicas

- **Descripción:** El contenido se genera en el servidor y puede variar según el usuario, la base de datos o la interacción.
- **Tecnologías:** HTML, CSS, JavaScript, lenguajes del lado servidor (PHP, Python, Node.js), bases de datos.
- **Ejemplo:** Blogs, foros, tiendas online.

### 3. SPA (Single Page Application, Aplicación de Página Única)

- **Descripción:** Toda la aplicación carga en una sola página y se actualiza dinámicamente sin recargar el navegador.
- **Tecnologías:** Frameworks/librerías como React, Angular, Vue.
- **Ejemplo:** Gmail, Trello.

### 4. PWA (Progressive Web App, Aplicación Web Progresiva)

- **Descripción:** Aplicaciones web que ofrecen características avanzadas como funcionamiento offline, notificaciones push y acceso a hardware, acercándose a la experiencia de una app nativa.
- **Tecnologías:** Service Workers, Manifest, tecnologías modernas de JavaScript.
- **Ejemplo:** Twitter Lite, Spotify Web.

Historia y evolución del desarrollo web  
Tipos de aplicaciones web (estáticas, dinámicas, SPA, PWA)  
2.Arquitectura de aplicaciones web 
Share

New chat
Spaces
Preview
alu230353-sr
Copilot Chat
Arquitectura de aplicaciones web explicada  
You said:   
<ins># 2.Arquitectura de aplicaciones web </ins>
Copilot said: La arquitectura de aplicaciones web se refiere
La arquitectura de aplicaciones web se refiere a la estructura y diseño fundamental que define cómo los componentes de una aplicación web interactúan entre sí y con el usuario final. Es clave para garantizar escalabilidad, seguridad, rendimiento y facilidad de mantenimiento.

Componentes principales de una arquitectura web
Cliente (Frontend):

Es la parte visual con la que interactúa el usuario, generalmente desarrollada con HTML, CSS y JavaScript.
Puede incluir frameworks como React, Angular, o Vue.js.
Servidor (Backend):

Es el responsable de procesar la lógica de negocio, acceder a bases de datos y gestionar la autenticación.
Suele estar construido con lenguajes como Python (Django, Flask), JavaScript (Node.js), Ruby, Java, etc.
Base de datos:

Almacena y gestiona los datos de la aplicación.
Ejemplos: MySQL, PostgreSQL, MongoDB.
Servicios externos:

APIs, servicios de autenticación, almacenamiento en la nube, etc.
Tipos de arquitectura de aplicaciones web
Monolítica:

Toda la lógica de la aplicación (frontend, backend, base de datos) está en un solo proyecto.
Ventaja: Fácil de desarrollar y desplegar.
Desventaja: Difícil de escalar y mantener a largo plazo.
Cliente-Servidor:

Separación clara entre el cliente y el servidor.
El cliente envía solicitudes al servidor, que las procesa y responde.
Microservicios:

La aplicación se divide en pequeños servicios independientes que se comunican entre sí.
Permite escalabilidad y despliegue independiente de cada servicio.
Sin servidor (Serverless):

El backend se ejecuta en servicios gestionados por proveedores en la nube (como AWS Lambda).
Los desarrolladores solo escriben la lógica, sin preocuparse por la infraestructura.
Flujo típico de una aplicación web
El usuario interactúa con la interfaz web (frontend).
El frontend envía solicitudes HTTP al backend (servidor).
El backend procesa la solicitud, accede a la base de datos si es necesario y responde.
El frontend muestra la información al usuario.
Cliente-Servidor  
Arquitectura de tres capas (presentación, lógica, datos)  
REST y API-first design  
<ins># 3. -Lenguajes y tecnologías fundamentales </ins>
**HTML (HyperText Markup Language):**  
Es el lenguaje básico de marcado para crear la estructura de las páginas web. Define elementos como títulos, párrafos, enlaces, imágenes, listas y más. Es esencial para dar forma y organización al contenido.

**CSS (Cascading Style Sheets):**  
Se utiliza para definir el estilo visual de una página web: colores, fuentes, márgenes, posiciones y disposición de elementos. Permite separar el contenido (HTML) de la presentación, facilitando el diseño responsivo y atractivo.

**JavaScript:**  
Es un lenguaje de programación interpretado que añade interactividad y dinamismo a las páginas web. Permite manipular el DOM, validar formularios, animaciones, peticiones a servidores (AJAX), y la creación de aplicaciones completas en el navegador.

**PHP:**  
Es un lenguaje de programación del lado del servidor, muy usado para crear sitios web dinámicos. PHP permite recibir datos de formularios, interactuar con bases de datos, gestionar sesiones de usuario y generar contenido HTML personalizado.

**MySQL:**  
Sistema de gestión de bases de datos relacional, utilizado para almacenar y organizar datos de aplicaciones web. Se integra fácilmente con lenguajes como PHP y permite realizar operaciones como consulta, inserción, actualización y eliminación de datos mediante SQL.

**Relación entre tecnologías:**  
- HTML, CSS y JavaScript trabajan juntos en el frontend (lado del cliente).
- PHP y MySQL suelen formar parte del backend (lado del servidor), donde PHP procesa la lógica y MySQL almacena los datos.
- Una aplicación web típica recibe solicitudes del usuario en el frontend, las procesa en el backend y almacena/recupera información de la base de datos.  

HTML, CSS, JavaScript, PHP, MySQL  
4.-Control de versiones  
Git y GitHub  
Flujo de trabajo con ramas (branching, merge, pull requests)  

Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web  
1.-Diseño e implementación del frontend  
Maquetación/Wireframe/Mockup  
API  
2.-Diseño e implementación del backend  
Servidor  
Manejo de peticiones y respuestas HTTP  
Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)  
3.-Bases de datos  
 Modelado de datos y relaciones  
ORM (Object Relational Mapping)  
CRUD desde el backend  
4.-Seguridad básica en aplicaciones web  
Validación de formularios  
Autenticación y autorización   

Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional  
1. -Integración de frontend y backend  
Interfaz de usuario Frontend  
Manejo de API  
Proceso de Solicitud y Respuesta de Backend  

2.- Almacenamiento en Servidor  
Tipos de servidores   
Servidores y servicios de hosting   
Proveedores de Servicios de Almacenamiento  

3.-Optimización y rendimiento  
Optimización de recursos (imágenes, scripts)  
Despliegue de aplicaciones web  
CI/CD básico  
Documentación del proyecto  
