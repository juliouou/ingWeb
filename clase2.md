## 1. Bases de Datos y Modelado

### 1.1. Modelado de Datos y Gestión SQL

* **Oracle Data Modeler:** Herramienta gráfica utilizada para el **diseño inicial del modelo relacional** de la base de datos. Permite la creación y gestión de modelos lógicos, relacionales y físicos, asegurando una estructura de datos sólida y optimizada.
* **Oracle SQL / PL-SQL:**
    * **SQL (Structured Query Language):** Se utiliza para la **consulta y manipulación estándar** de los datos (selección, inserción, actualización de libros, usuarios, transacciones).
    * **PL/SQL (Procedural Language/SQL):** Se utiliza para implementar la **lógica compleja** dentro de la base de datos (procedimientos almacenados, *triggers* y funciones) que gestionan las reglas de negocio (ej. el sistema de gemas/créditos).

### 1.2. Gestión de Contenido Binario

* **Campos BLOB (Binary Large Object):** Se utiliza este tipo de dato en la base de datos relacional para el **almacenamiento directo de las imágenes de los libros**. Esto simplifica la gestión inicial del contenido multimedia dentro de la misma transacción de datos.

### 1.3. Estrategia de Escalabilidad Futura

* **Migración a MongoDB:** Se proyecta la migración del almacenamiento principal a **MongoDB (una base de datos NoSQL)**. Esto se hará para ganar **flexibilidad en el esquema de datos** y mejorar la **escalabilidad horizontal**, preparándose para un crecimiento masivo de usuarios y datos variados.

---

## 2. Herramientas de Desarrollo y Productividad

### 2.1. Power Platform / Power Apps

* **Uso:** Se considera el uso de Power Apps (parte de Power Platform) para el **desarrollo rápido de aplicaciones internas** (low-code/no-code).
* **Objetivo:** Crear herramientas sencillas y eficientes para que los **administradores** gestionen tareas específicas, como la moderación de contenido o la visualización de reportes de actividad.

### 2.2. CircuitVerse (Contexto de Uso)

* **Nota:** Aunque no es una herramienta de desarrollo web tradicional, su mención en el proyecto se asocia al posible **uso como herramienta educativa o de simulación** dentro del entorno de aprendizaje del equipo o para un componente didáctico del proyecto.

---

## 3. Seguridad y Control de Acceso

* **Control de Acceso Basado en Roles (RBAC):** Se implementará un sistema para **restringir el acceso** a ciertas funcionalidades y módulos basándose en el rol del usuario (Usuario Estándar vs. Administrador).
* **Gestión Segura de Credenciales:** Las contraseñas se almacenarán utilizando **técnicas de *hashing*** robustas.
* **Encriptación de Datos Sensibles:** Se aplicará **encriptación** a los datos sensibles que requieran protección adicional durante el tránsito y el almacenamiento.

---
## Trabajo en Clase:

<img width="737" height="728" alt="Screenshot 2025-10-15 121034" src="https://github.com/user-attachments/assets/a6045f7c-8071-418b-a5cb-003e502d54fb" />
<img width="781" height="859" alt="Screenshot 2025-10-15 121049" src="https://github.com/user-attachments/assets/bfbdccab-3ee3-4396-aa48-5c96cd89e8a7" />
<img width="820" height="610" alt="Screenshot 2025-10-15 121100" src="https://github.com/user-attachments/assets/4abb3037-4b66-422e-b2e5-0fbd2342ecb0" />


