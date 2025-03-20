# **JSPBYNIKO - Proyecto Final JSP + Hibernate**

Este repositorio contiene el **Proyecto Final** de **JSP** con **Hibernate** para la persistencia de datos. El objetivo es desarrollar una **página web** que gestione proyectos y tareas, utilizando **JSP** en el frontend y **Hibernate** para la interacción con la base de datos.

## 🚀 **Tecnologías Utilizadas**

- **JSP** (Java Server Pages)
- **Hibernate** (ORM para la persistencia de datos)
- **Servlets** (gestión de peticiones)
- **HTML/CSS** (Frontend básico)
- **MySQL** (Base de datos)
- **Java** (Backend)

## 🛠️ **Características del Proyecto**

### **Base de Datos:**
- **Proyectos:** id, nombre_proyecto, descripción, fechas de inicio y fin, estado.
- **Tareas:** id, id_proyecto (clave foránea), descripción, responsable, fechas de inicio y fin, estado.

### **Servlets:**
- **Mostrar lista de proyectos** (filtrado por estado).
- **Registrar nuevos proyectos.**
- **Mostrar lista de tareas** de un proyecto.
- **Agregar nuevas tareas** a un proyecto.
- **Eliminar tareas** (solo admins).
- **Eliminar proyectos** (solo admins).

## 📂 **Estructura del Proyecto**

- **Frontend:** Usando **JSP** para generar páginas dinámicas.
- **Backend:** Usando **Hibernate** para la persistencia de datos con **MySQL**.
- **Servlets:** Gestionan la lógica y las interacciones entre el frontend y la base de datos.

## ⚙️ **Instrucciones de Configuración**

1. **Base de Datos:** Crea las tablas `proyectos` y `tareas` con el script SQL proporcionado.
2. **Configuración de Hibernate:** Configura **Hibernate** para la conexión con la base de datos MySQL.
3. **Servidor Web:** Utiliza un servidor como **Apache Tomcat** para ejecutar el proyecto.

## 💻 **Ejecución del Proyecto**

Accede al proyecto a través de **Tomcat**. Podrás gestionar proyectos, tareas, y realizar operaciones CRUD según el rol de usuario (admin o usuario estándar).

