<div align="center">

# 📚 API REST de Estudiantes con Express.js

¡Bienvenido al repositorio de la API REST de Gestión de Estudiantes!  
Un servidor práctico, moderno y ligero construido sobre Node.js y Express.js.

[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![JSON](https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white)](https://www.json.org/)
[![License: MIT](https://img.shields.io/badge/License-Educational-blue.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

---

</div>

## 🎯 Propósito del Proyecto

**Express.js** es el framework backend de Node.js más utilizado en la industria tecnológica. Comprender cómo un servidor procesa las peticiones HTTP y responde con objetos JSON es el cimiento de cualquier infraestructura web moderna (bases de datos, microservicios, autenticación y despliegue en la nube).

### 📄 Descripción General
Esta API RESTful administra el ciclo de vida básico (*CRUD*) de registros de estudiantes almacenados dinámicamente en memoria (array en JavaScript). Todo el intercambio de información se realiza mediante peticiones HTTP estandarizadas con sus respectivos códigos de estado (*HTTP Status Codes*).

---

## 🚀 Funcionalidades Principales

* 📥 **Consultar catálogo general:** Lista completa de estudiantes.
* 🔍 **Búsqueda por parámetro:** Filtro directo de un estudiante por su ID único.
* ➕ **Registro de nuevos estudiantes:** Validación e inserción en el sistema.
* ✏️ **Actualización de información:** Modificación de datos de estudiantes existentes.
* ❌ **Eliminación de registros:** Remoción segura de estudiantes por ID.

---

## 🗂️ Estructura del Repositorio

```text
📦 express-estudiantes-api
├── 📁 node_modules/         # (Excluido vía .gitignore)
├── 📄 .gitignore            # Archivos y carpetas excluidos de Git
├── 📄 index.js              # Servidor principal y endpoints de la API
├── 📄 package.json          # Metadatos del proyecto y dependencias
└── 📄 README.md             # Documentación oficial del repositorio
