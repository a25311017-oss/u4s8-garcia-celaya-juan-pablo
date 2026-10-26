# Sistema Web de Gestión de Servicios — Django

**Desarrollador:** Juan Pablo García Celaya  
**Matrícula:** 25311017  
**Grupo:** DSM 4-1  
**Institución:** Universidad Tecnológica de Hermosillo (UTH)  
**Área:** Desarrollo de Aplicaciones Web

---

## 1. Descripción del proyecto

Este proyecto consiste en el desarrollo de una aplicación web utilizando Django y Python, enfocada en la gestión de servicios mediante una interfaz web.

El sistema permite organizar y administrar información de servicios, consultar los registros existentes y realizar operaciones para mantener actualizada la información. También incorpora plantillas HTML para presentar los datos de forma estructurada y facilitar la interacción del usuario con la aplicación.

El proyecto se desarrolla progresivamente como parte de las prácticas y actividades de la asignatura Desarrollo de Aplicaciones Web, integrando nuevas funcionalidades y mejoras a lo largo de las diferentes unidades y semanas del curso.

## 2. Objetivos

- Desarrollar una aplicación web funcional utilizando Django.
- Implementar operaciones de registro, consulta, edición y eliminación de servicios.
- Organizar el código mediante aplicaciones, vistas, modelos y plantillas.
- Utilizar una base de datos para almacenar y administrar información.
- Aplicar buenas prácticas de desarrollo y control de versiones con Git y GitHub.
- Preparar el proyecto para su ejecución local y despliegue en un entorno web.

## 3. Funcionalidades principales

- **Gestión de servicios:** administración de los registros del sistema.
- **Consulta de información:** visualización de los servicios registrados.
- **Creación y edición:** incorporación de nuevos servicios y actualización de información.
- **Eliminación de registros:** posibilidad de eliminar servicios mediante las vistas correspondientes.
- **Interfaz web:** uso de plantillas HTML para organizar el contenido.
- **Mensajes de interacción:** presentación de notificaciones para informar sobre determinadas operaciones.
- **Persistencia de datos:** integración con una base de datos mediante el ORM de Django.
- **Control de versiones:** seguimiento de modificaciones mediante Git y GitHub.

*Nota: las funcionalidades disponibles dependen de la versión actual del código y de su configuración.*

## 4. Tecnologías utilizadas (Stack tecnológico)

| Tecnología | Uso |
|---|---|
| Python | Lenguaje principal de programación. |
| Django | Framework para desarrollar la aplicación web. |
| HTML5 | Estructura de las páginas web. |
| CSS | Presentación y estilos de la interfaz. |
| Tailwind CSS | Herramientas de estilos utilizadas mediante CDN. |
| SQLite / MySQL | Base de datos, según la configuración del entorno. |
| Git | Control de versiones del código. |
| GitHub | Repositorio remoto y respaldo del proyecto. |
| Visual Studio Code | Entorno de desarrollo. |
| Render | Plataforma utilizada para desplegar proyectos web cuando está configurada para este sistema. |
| Aiven | Servicio de base de datos en la nube contemplado en la configuración del proyecto. |

## 5. Estructura general del proyecto

```text
miproyecto-django_gcjp-main/
├── core/
│   ├── migrations/
│   ├── templates/
│   │   └── core/
│   │       └── servicios.html
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── admin.py
├── miproyecto/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
├── manage.py
├── requirements.txt
├── .gitignore
└── README.md
```

La estructura anterior es una referencia general. Los archivos y directorios pueden variar de acuerdo con la versión del proyecto.

## 6. Instalación y ejecución local

### Requisitos

- Python instalado.
- Git instalado.
- Acceso al repositorio del proyecto.
- Un entorno virtual de Python.
- Las dependencias definidas en `requirements.txt`.

### Clonar el repositorio

```bash
git clone URL_DEL_REPOSITORIO
cd miproyecto-django_gcjp-main
```

Sustituye `URL_DEL_REPOSITORIO` por la dirección real del repositorio de GitHub.

### Crear y activar el entorno virtual

En Windows PowerShell:

```powershell
python -m venv venv
Set-ExecutionPolicy -Scope Process -ExecutionPolicy RemoteSigned
.\venv\Scripts\Activate.ps1
```

### Instalar las dependencias

```bash
python -m pip install -r requirements.txt
```

### Aplicar las migraciones

```bash
python manage.py migrate
```

### Verificar la configuración

```bash
python manage.py check
```

### Iniciar el servidor

```bash
python manage.py runserver
```

Después, abre la siguiente dirección en el navegador:

http://127.0.0.1:8000/

## 7. Historial de unidades y semanas

El desarrollo del proyecto se ha realizado de manera incremental, utilizando las actividades académicas para incorporar funcionalidades, corregir errores y mejorar la organización del código.

### Unidad 1 — Fundamentos del desarrollo web

- Introducción al desarrollo de aplicaciones web.
- Preparación del entorno de trabajo.
- Organización inicial de los archivos del proyecto.
- Fundamentos de programación y estructura de una aplicación web.

### Unidad 2 — Estructura y presentación web

- Trabajo con documentos HTML y estilos CSS.
- Organización de las páginas y sus componentes.
- Preparación de la interfaz para presentar información.
- Desarrollo y actualización del portafolio web como trabajo relacionado del curso.

### Unidad 3 — Desarrollo de aplicaciones con Django

- Configuración del entorno de Python y Django.
- Organización del proyecto y sus aplicaciones.
- Implementación de vistas, rutas y plantillas.
- Integración de funcionalidades para administrar información.
- Uso de Git y GitHub para respaldar los avances.

### Unidad 4 — Integración y mejoras del sistema

- Actualización de funcionalidades de la aplicación.
- Trabajo con modelos y migraciones de Django.
- Ajustes en las vistas y plantillas de servicios.
- Preparación de la conexión con una base de datos.
- Corrección de errores y validación de la aplicación.
- Actualización del repositorio y documentación del proyecto.

### Unidad 4 — Semana 7

- Consolidación de los avances del proyecto.
- Actualización de archivos y documentación.
- Revisión del repositorio remoto.
- Preparación de la entrega académica y del historial de desarrollo.

**Importante:** el detalle de cada unidad y semana debe ajustarse a las actividades realmente solicitadas por el profesor y a
