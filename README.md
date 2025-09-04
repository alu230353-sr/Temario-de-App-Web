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

## Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web  
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
<ins># 2.-Diseño e implementación del backend  </ins>
Servidor
El backend de una aplicación web es responsable de gestionar la lógica de negocio, el acceso a los datos, la autenticación y la comunicación con el frontend. El servidor es el componente que recibe las peticiones de los clientes, procesa la información y responde en consecuencia.

Tecnologías populares: Node.js, Python (Django/Flask), Java (Spring), PHP, Ruby on Rails.
El servidor se ejecuta constantemente, esperando peticiones de los clientes (navegadores, aplicaciones móviles, etc.).
Manejo de peticiones y respuestas HTTP
La comunicación entre el cliente y el servidor se realiza a través del protocolo HTTP:

Petición HTTP: El cliente (por ejemplo, el navegador) envía una solicitud al servidor, indicando qué recurso desea o qué acción quiere realizar. Ejemplo: GET /api/productos
Respuesta HTTP: El servidor procesa la solicitud y envía una respuesta, que puede incluir datos (normalmente en formato JSON o HTML) y un código de estado (200 OK, 404 Not Found, etc.).
Las principales métodos HTTP son:

GET: Obtener datos.
POST: Crear datos.
PUT/PATCH: Actualizar datos.
DELETE: Eliminar datos.
El backend debe manejar rutas, validaciones, autenticación y errores para cada tipo de petición.

Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)
El backend suele necesitar almacenar y recuperar información de una base de datos. Entre las más populares están:

MySQL/PostgreSQL: Bases de datos relacionales. Usan tablas con filas y columnas. Utilizan SQL para consultar y modificar datos.
Ejemplo de conexión en Node.js con MySQL:
js
const mysql = require('mysql');
const connection = mysql.createConnection({
  host: 'localhost',
  user: 'usuario',
  password: 'contraseña',
  database: 'nombre_bd'
});
connection.connect();
MongoDB: Base de datos NoSQL orientada a documentos. Almacena datos en formato BSON (similar a JSON).
Ejemplo de conexión en Node.js con MongoDB:
js
const { MongoClient } = require('mongodb');
const uri = 'mongodb://localhost:27017';
const client = new MongoClient(uri);
await client.connect();
const db = client.db('nombre_bd');
El backend realiza operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre la base de datos según las peticiones del cliente.


Servidor  
Manejo de peticiones y respuestas HTTP  
Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)  
<ins># 3.-Bases de datos  </ins>
Modelado de datos y relaciones
El modelado de datos es el proceso de definir cómo se almacenará la información en la base de datos. Esto incluye:

Tablas: Representan entidades (por ejemplo, Usuarios, Productos).
Campos: Son los atributos de cada entidad (por ejemplo, nombre, correo, precio).
Relaciones: Definen cómo se conectan las entidades entre sí. Las principales son:
Uno a uno (1:1): Un registro de una tabla se asocia con uno de otra.
Uno a muchos (1:N): Un registro de una tabla se asocia con varios de otra.
Muchos a muchos (N:M): Varios registros de una tabla se asocian con varios de otra (requiere una tabla intermedia).
Ejemplo:

plaintext
Usuarios (id, nombre, email)
Posts (id, titulo, contenido, usuario_id)
Relación: Un usuario puede tener muchos posts (1:N)
ORM (Object Relational Mapping)
Un ORM es una herramienta que permite interactuar con la base de datos usando objetos y clases en el lenguaje de programación, en vez de escribir directamente las sentencias SQL.

Ventajas:

Facilita el trabajo con la base de datos.
Hace el código más mantenible y seguro.
Permite migraciones automáticas del esquema.
Ejemplo de ORMs populares:

Django ORM (Python)
SQLAlchemy (Python)
TypeORM (Node.js)
Hibernate (Java)
Ejemplo (Python con SQLAlchemy):

Python
class Usuario(Base):
    __tablename__ = 'usuarios'
    id = Column(Integer, primary_key=True)
    nombre = Column(String)
    email = Column(String)
CRUD desde el backend
CRUD son las operaciones básicas para gestionar datos en una base de datos:

Create: Crear un nuevo registro.
Read: Leer/consultar registros existentes.
Update: Modificar registros existentes.
Delete: Eliminar registros.
Ejemplo de CRUD usando un ORM (pseudo-código):

Python
# Create
nuevo_usuario = Usuario(nombre="Ana", email="ana@email.com")
session.add(nuevo_usuario)
session.commit()

# Read
usuario = session.query(Usuario).filter_by(id=1).first()

# Update
usuario.nombre = "Ana María"
session.commit()

# Delete
session.delete(usuario)
session.commit()
 Modelado de datos y relaciones  
ORM (Object Relational Mapping)  
CRUD desde el backend  
<ins># 4.-Seguridad básica en aplicaciones web  </ins>
La seguridad es un pilar fundamental en el desarrollo de aplicaciones web. En este apartado se tratan dos conceptos clave: la **validación de formularios** y los mecanismos de **autenticación y autorización**.

---

## 4.1 Validación de formularios

La validación de formularios consiste en comprobar que los datos introducidos por el usuario cumplen ciertos requisitos antes de ser procesados por el servidor. Esto ayuda a prevenir vulnerabilidades como la inyección de código, errores y comportamientos inesperados.

### Tipos de validación

1. **Validación en el cliente (Front-end):**
   - Se realiza usando JavaScript o atributos HTML (`required`, `pattern`, etc).
   - Proporciona retroalimentación inmediata al usuario.
   - Ejemplo:
     ```html
     <form>
       <input type="email" required>
       <input type="password" pattern="[A-Za-z0-9]{8,}">
     </form>
     ```

2. **Validación en el servidor (Back-end):**
   - Se realiza después de recibir los datos del formulario.
   - Es imprescindible, ya que la validación en el cliente puede ser manipulada o ignorada.
   - Ejemplo en Python (Flask):
     ```python
     email = request.form.get('email')
     if not re.match(r"[^@]+@[^@]+\.[^@]+", email):
         flash("Email inválido")
     ```

### Buenas prácticas

- Nunca confiar solo en la validación del cliente.
- Validar el tipo, formato y rango de los datos.
- Escapar los datos para evitar inyección de código.
- Mostrar mensajes claros al usuario en caso de error.

---

## 4.2 Autenticación y autorización

### Autenticación

La **autenticación** es el proceso de verificar la identidad de un usuario. Los métodos más comunes incluyen:

- **Contraseña:** El usuario proporciona una contraseña secreta.
- **Autenticación de dos factores (2FA):** Se requiere una segunda prueba de identidad (SMS, app, correo).
- **OAuth:** Permite autenticarse usando proveedores externos (Google, GitHub).

Ejemplo básico de autenticación (Python Flask):
```python
if usuario and usuario.verificar_contraseña(password):
    session['usuario_id'] = usuario.id
else:
    flash('Credenciales incorrectas')
```

### Autorización

La **autorización** determina si el usuario autenticado tiene permisos para acceder a ciertos recursos o realizar acciones específicas.

- **Roles:** (Usuario, administrador, invitado) Cada uno tiene diferentes permisos.
- **Listas de control de acceso (ACL):** Definen qué usuarios/grupos pueden acceder a qué recursos.

Ejemplo de autorización:
```python
if usuario.rol == 'admin':
    # Acceso permitido
else:
    # Acceso denegado
```

### Buenas prácticas

- No almacenar contraseñas en texto plano; usar algoritmos de hash seguros (bcrypt, Argon2).
- Implementar expiración de sesión y protección contra CSRF.
- Usar HTTPS para proteger la transmisión de datos sensibles.
- Limitar el número de intentos de inicio de sesión para evitar ataques de fuerza bruta.

---

## Resumen

- **Validar siempre los datos de entrada tanto en cliente como en servidor.**
- **Autenticar usuarios antes de permitir el acceso a funciones sensibles.**
- **Autorizar el acceso según roles y permisos definidos.**
- **Aplicar buenas prácticas de seguridad y mantenerse actualizado sobre vulnerabilidades comunes.**

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
