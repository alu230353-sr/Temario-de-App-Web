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
Cliente-Servidor
La arquitectura cliente-servidor separa las responsabilidades entre dos entidades principales:

Cliente: El cliente es generalmente el navegador web o una aplicación que solicita servicios o datos al servidor. Se encarga de la interfaz de usuario y la experiencia interactiva.
Servidor: El servidor recibe las solicitudes del cliente, procesa la lógica de negocio, accede a la base de datos y devuelve los resultados al cliente. Permite centralizar la gestión, la seguridad y el almacenamiento de datos.
Ventajas:

Separación de responsabilidades.
Mejor escalabilidad y mantenimiento.
Facilita la reutilización de componentes.
Arquitectura de tres capas (Presentación, Lógica, Datos)
Es una evolución del modelo cliente-servidor y divide la aplicación en tres capas independientes:

Capa de Presentación:
La interfaz que interactúa directamente con el usuario (HTML, CSS, JavaScript).
Capa de Lógica de Negocio:
Gestiona las reglas, procesos y funcionalidades principales de la aplicación (por ejemplo, los controladores en frameworks como Django o Spring).
Capa de Datos:
Se encarga del almacenamiento, recuperación y gestión de datos (bases de datos SQL/NoSQL).
Ventajas:

Mejor organización del código.
Facilita el mantenimiento y la escalabilidad.
Permite cambios en una capa sin afectar a las demás.
REST y API-first Design
REST (Representational State Transfer)
Es un estilo de arquitectura para el diseño de servicios web:

Utiliza las operaciones HTTP estándar (GET, POST, PUT, DELETE).
Los recursos se identifican mediante URLs.
Se basa en la transferencia de representaciones (JSON, XML).
Es stateless (cada petición contiene toda la información necesaria).
Ventajas:

Simplicidad y flexibilidad.
Interoperabilidad entre sistemas.
API-first Design
Consiste en diseñar primero la interfaz de programación de la aplicación (API) antes de implementar la lógica interna:

El contrato de la API se define desde el inicio (por ejemplo, usando OpenAPI/Swagger).
Permite que equipos de frontend y backend trabajen en paralelo.
Facilita la integración con otros servicios y clientes.
Ventajas:

Desarrollo más ágil.
Mejor documentación y mantenibilidad.
Facilita la escalabilidad y la reutilización.
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
<ins># 4.-Control de versiones </ins>
### 4.-Control de versiones

El **control de versiones** es una práctica fundamental en el desarrollo de software que permite gestionar y mantener el historial de cambios en archivos y proyectos. Esto facilita la colaboración, el seguimiento de modificaciones y la recuperación de versiones anteriores si es necesario.

#### Git

**Git** es el sistema de control de versiones más popular y utilizado actualmente. Es distribuido, lo que significa que cada desarrollador tiene una copia completa del repositorio y su historial. Las principales características de Git son:

- **Seguimiento de cambios** en el código fuente.
- **Trabajo colaborativo** entre varios desarrolladores.
- **Creación de ramas** para desarrollar nuevas funcionalidades sin afectar el código principal.
- **Fusión (merge)** de ramas para integrar cambios.

#### GitHub

**GitHub** es una plataforma en la nube que utiliza Git para alojar repositorios y facilitar la colaboración entre desarrolladores. GitHub ofrece herramientas adicionales como gestión de proyectos, seguimiento de issues, revisión de código y acciones automáticas (GitHub Actions).

#### Flujo de trabajo con ramas (branching, merge, pull requests)

El flujo de trabajo típico con Git y GitHub consiste en:

1. **Branching (ramificación):**  
   Se crea una rama para trabajar en una nueva funcionalidad o corregir un error. Esto permite desarrollar de forma aislada sin afectar la rama principal (`main` o `master`).

2. **Desarrollo en la rama:**  
   Se realizan los cambios y se van guardando con **commits**.

3. **Merge (fusión):**  
   Una vez terminados los cambios, se integra la rama al proyecto principal. Esto se hace mediante la operación de **merge**.

4. **Pull Request (Solicitud de extracción):**  
   En GitHub, se crea un **pull request** para solicitar que los cambios realizados en una rama sean revisados y fusionados con la rama principal. Otros miembros del equipo pueden revisar el código, dar comentarios y aprobar la integración.

**Ejemplo de flujo de trabajo:**

- Crear una rama:  
  `git checkout -b feature/nueva-funcionalidad`
- Realizar cambios y hacer commits:  
  `git add .`  
  `git commit -m "Implementa nueva funcionalidad"`
- Subir la rama al repositorio remoto:  
  `git push origin feature/nueva-funcionalidad`
- Crear un Pull Request en GitHub.
- Revisar y fusionar los cambios en la rama principal.

**Ventajas:**

- Permite trabajo colaborativo y organizado.
- Facilita la revisión y control de cambios.
- Reduce el riesgo de errores al trabajar en paralelo.
Git y GitHub  
Flujo de trabajo con ramas (branching, merge, pull requests)  

Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web  
<ins># 1.-Diseño e implementación del frontend </ins>
A. Maquetación / Wireframe / Mockup
Maquetación:
Es el proceso de estructurar visualmente la interfaz. Se define la ubicación de los elementos (menús, botones, formularios, etc.) en la página, generalmente usando cajas y líneas sin detalles gráficos.

Wireframe:
Es un boceto de baja fidelidad. Sirve para mostrar la estructura y navegación del sitio/app. Herramientas populares: Figma, Sketch, Adobe XD, Balsamiq.

Mockup:
Es una representación visual más detallada (alta fidelidad) de la interfaz. Incluye colores, tipografías, imágenes y estilos.

Ejemplo de proceso:

Bocetar la estructura en papel o digital (Wireframe).
Refinar el diseño añadiendo color, fuentes, imágenes (Mockup).
Traducir el diseño a HTML/CSS/JS (Maquetación en código).
B. API (Interfaz de Programación de Aplicaciones)
El frontend suele consumir datos de una API (normalmente REST o GraphQL).
La API provee endpoints para obtener, crear, modificar o eliminar información.
Ejemplo:
js
fetch('https://api.ejemplo.com/usuarios')
  .then(response => response.json())
  .then(data => mostrarUsuarios(data));
Pasos básicos:

Definir qué datos necesita el frontend.
Hacer llamadas HTTP (GET, POST, PUT, DELETE) a la API.
Mostrar los datos recibidos en la interfaz.

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
