
## 1. Arquitecturas de Servidor (Modelos de Backend)

Estos modelos definen cómo se organiza la lógica de negocio en la parte del servidor de la aplicación.

### 1.1. Monolítico

| Característica | Descripción Puntual |
| :--- | :--- |
| **Definición** | Todo el código (interfaz, lógica de negocio y acceso a datos) se empaqueta en una **única y gran unidad** de despliegue. |
| **Ventaja** | **Sencillo de desarrollar, probar y desplegar** al inicio del proyecto. |
| **Desventaja** | Dificultad para escalar componentes individuales; un fallo en una parte puede afectar a toda la aplicación. |

### 1.2. Microservicios

| Característica | Descripción Puntual |
| :--- | :--- |
| **Definición** | La aplicación se descompone en **servicios pequeños e independientes** que se comunican entre sí. Cada servicio tiene su propia lógica y potencialmente su propia base de datos. |
| **Ventaja** | **Escalabilidad independiente** por componente; mayor resistencia a fallos y flexibilidad tecnológica. |
| **Desventaja** | Mayor **complejidad** en la gestión de la comunicación (redes) y el monitoreo. |

---

## 2. Protocolos de Red y Comunicación

Los protocolos son las reglas que permiten la comunicación entre el cliente y el servidor.

### 2.1. HTTP (Hypertext Transfer Protocol)

* **Función:** Es el **protocolo fundamental** de la World Wide Web. Define el formato en que el cliente (navegador) y el servidor se envían y responden mensajes (solicitudes y respuestas).

### 2.2. HTTPS (Hypertext Transfer Protocol Secure)

* **Función:** Es la **versión segura de HTTP**.
* **Mecanismo:** Utiliza el protocolo **SSL/TLS** para **encriptar la comunicación** de extremo a extremo, asegurando que los datos sensibles (como credenciales de *login* o información de contacto) viajen de forma privada. **Es obligatorio** para cualquier aplicación moderna.

---

## 3. Patrones de Diseño de Software

Los patrones proporcionan una estructura probada para organizar el código y **separar las responsabilidades**.

### 3.1. Patrón MVC (Model-View-Controller)

* **Concepto:** Separa la aplicación en tres capas interconectadas para mejorar la organización del código y facilitar el mantenimiento.

| Componente | Responsabilidad |
| :--- | :--- |
| **Modelo (Model)** | Gestiona los datos y la lógica de negocio (interactúa con la Base de Datos). |
| **Vista (View)** | Se encarga de la interfaz de usuario y la presentación de los datos (lo que ve el usuario). |
| **Controlador (Controller)** | Actúa como intermediario; recibe la entrada del usuario, llama al Modelo para procesar la lógica y selecciona la Vista a mostrar. |

### 3.2. Patrón MVT (Model-View-Template)

* **Concepto:** Una variación común del MVC, popularizada por *frameworks* de desarrollo como Django.
* **Diferencia:** La "Vista" en MVT maneja la lógica de negocio (similar al Controlador en MVC), y el "Template" es la capa de presentación (HTML).

---

## 4. Servicios RESTful y APIs

### 4.1. API (Application Programming Interface)

* **Definición:** Un **conjunto de reglas** que permite a dos sistemas de software comunicarse entre sí (Ej: la API de Google Books que usará MEBOOK).

### 4.2. Servicios RESTful

* **Definición:** APIs que siguen un conjunto de principios arquitectónicos llamados **REST (Representational State Transfer)**.
* **Características:**
    * Utilizan los métodos HTTP estándar (**GET, POST, PUT, DELETE**) para realizar operaciones de datos (CRUD).
    * Son **"sin estado"** (*Stateless*): el servidor no guarda información de la sesión entre peticiones, lo que mejora la escalabilidad.
    * Son el **estándar actual** para construir servicios web.

 ## Trabajo en Clase con XAMPPm
 <img width="1158" height="903" alt="Screenshot 2025-10-22 105313" src="https://github.com/user-attachments/assets/e4a25543-b08d-43a5-826b-b0828aee648b" />
 <img width="1919" height="969" alt="Screenshot 2025-10-22 111618" src="https://github.com/user-attachments/assets/414a3ebe-035b-479e-8198-fed574fc1192" />
 <img width="1919" height="1079" alt="Screenshot 2025-10-22 112509" src="https://github.com/user-attachments/assets/49d440cb-a04c-45a6-965d-c3a962b4a0c2" />


