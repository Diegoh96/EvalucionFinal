# Sistema de Gestión de Productos

## Evaluación Final - Programación Web

### Autor

**Diego Soto**

---

# Descripción

Este proyecto corresponde a la Evaluación Final de la Unidad III de la asignatura **Programación Web**.

Consiste en una mini aplicación web para la gestión de productos utilizando tecnologías Frontend y Backend.

La aplicación permite administrar un listado de productos mediante un CRUD completo (Crear, Leer, Actualizar y Eliminar), utilizando JavaScript, Node.js, Express y Fetch API.

---

# Objetivo

Desarrollar una aplicación web interactiva que integre los componentes JavaScript con una maqueta web, implementando validaciones, manipulación del DOM, persistencia de datos y comunicación entre Frontend y Backend.

---

# Tecnologías utilizadas

## Frontend

* HTML5
* CSS3
* JavaScript ES6

## Backend

* Node.js
* Express.js

## Otras tecnologías

* Fetch API
* LocalStorage
* JSON
* Git
* GitHub

---

# Funcionalidades

La aplicación permite:

* Agregar productos.
* Listar productos.
* Editar productos.
* Eliminar productos.
* Buscar productos.
* Validar formularios.
* Persistir datos mediante archivo JSON.
* Recordar la búsqueda utilizando LocalStorage.

---

# Requisitos

Antes de ejecutar el proyecto es necesario tener instalado:

* Node.js
* npm
* Visual Studio Code

---

# Instalación

## 1. Clonar el repositorio

```bash
git clone https://github.com/Diegoh96/Evaluacion_Final.git
```

## 2. Entrar a la carpeta backend

```bash
cd Evaluacion_Final/backend
```

## 3. Instalar dependencias

```bash
npm install
```

## 4. Ejecutar el servidor

Modo desarrollo

```bash
npm run dev
```

o

Modo normal

```bash
npm start
```

---

# Abrir el Frontend

Abrir el archivo

```text
frontend/index.html
```

en el navegador.

---

# API

## Obtener productos

GET

```
http://localhost:3000/api/productos
```

---

## Obtener producto por ID

GET

```
http://localhost:3000/api/productos/1
```

---

## Crear producto

POST

```
http://localhost:3000/api/productos
```

Ejemplo

```json
{
    "nombre":"Teclado",
    "precio":25000,
    "categoria":"Accesorios",
    "stock":20
}
```

---

## Actualizar producto

PUT

```
http://localhost:3000/api/productos/1
```

---

## Eliminar producto

DELETE

```
http://localhost:3000/api/productos/1
```

---

# Validaciones implementadas

* Nombre obligatorio.
* Nombre mínimo de 3 caracteres.
* Precio obligatorio.
* Precio mayor que cero.
* Precio numérico.
* Categoría obligatoria.
* Stock obligatorio.
* Stock entero.
* Stock mayor o igual a cero.
* Feedback visual mediante CSS.
* Prevención del envío del formulario cuando existen errores.

---

# Eventos utilizados

* DOMContentLoaded
* submit
* click
* input
* change
* keyup
* keypress
* blur
* keydown
* focus

---

# Manipulación del DOM

Se utilizaron las siguientes funciones:

* getElementById()
* querySelector()
* createElement()
* appendChild()
* textContent
* innerHTML
* classList.add()
* classList.remove()

---

# Persistencia

La aplicación utiliza dos mecanismos de persistencia:

## Backend

Archivo JSON

```
backend/database/productos.json
```

## Frontend

LocalStorage

Se utiliza para almacenar la búsqueda realizada por el usuario.

---

# Estructura del proyecto

```
Evaluacion_Final/

│

├── backend/

│   ├── app.js

│   ├── package.json

│   ├── controllers/

│   ├── models/

│   ├── routes/

│   └── database/

│

├── frontend/

│   ├── index.html

│   ├── css/

│   ├── js/

│   └── assets/

│

├── README.md

└── .gitignore
```

---

# Requerimientos de la rúbrica cumplidos

## Integración

* HTML separado.
* CSS separado.
* JavaScript separado.
* Proyecto organizado.

## DOM

* Manipulación completa del DOM.
* Creación dinámica de elementos.
* Actualización dinámica de la tabla.

## Eventos

* Más de tres eventos implementados.

## Formularios

* Más de cinco validaciones.
* Mensajes de error.
* Feedback visual.
* preventDefault().

## Persistencia

* Fetch API.
* JSON.
* LocalStorage.

## Usabilidad

* Responsive.
* Compatible con Google Chrome.
* Compatible con Microsoft Edge.
* Sin errores críticos en consola.

---

# Evidencias

Agregar las siguientes capturas de pantalla:

* Pantalla principal.
* Formulario funcionando.
* Listado de productos.
* Agregar producto.
* Editar producto.
* Eliminar producto.
* Consola sin errores.
* Prueba de responsive.
* Repositorio GitHub.

---

# Conclusión

Este proyecto demuestra la integración entre Frontend y Backend utilizando JavaScript, implementando un CRUD completo con persistencia de datos, validaciones, manipulación del DOM, Fetch API y una interfaz responsive, cumpliendo con los requisitos establecidos para la Evaluación Final de Programación Web.
