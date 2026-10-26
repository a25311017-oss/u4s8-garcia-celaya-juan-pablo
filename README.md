# Práctica Unidad 4 - Semana 8: Despliegue Final del Proyecto Django

## 📌 Descripción del Proyecto
Este repositorio contiene la solución completa para la unidad 4, semana 8 del curso. Consiste en una aplicación web desarrollada con el marco de trabajo **Django**, conectada a una base de datos **MySQL alojada en Aiven** e implementando autenticación de usuarios con aislamiento de datos[cite: 1].

## 🛠️ Tecnologías Utilizadas
* **Backend:** Python / Django[cite: 1]
* **Base de Datos:** MySQL (Servidor gestionado en Aiven)[cite: 1]
* **Gestión de Entornos:** Variables de entorno (`.env`)[cite: 1]
* **Control de Versiones:** Git / GitHub[cite: 1]

## 🚀 Características y Funcionalidades
1. **Sistema de Autenticación Completo:**
   * Registro de nuevos usuarios[cite: 1].
   * Inicio de sesión (`login`) y cierre de sesión (`logout`)[cite: 1].
2. **Aislamiento de Datos:**
   * Cada usuario autenticado gestiona y visualiza únicamente sus propios registros[cite: 1].
3. **Conexión a Base de Datos Externa:**
   * Configuración de la persistencia de datos mediante MySQL en Aiven[cite: 1].
4. **Archivos Estáticos y Despliegue:**
   * Configuración preparada para despliegue final (`DEBUG = False`)[cite: 1].
   * Manejo de archivos estáticos en la carpeta `staticfiles/`[cite: 1].

---

## 📂 Estructura del Repositorio

```text
u4s8-garcia-celaya-juan-pablo/
│
├── core/               # Configuración principal del proyecto Django
├── miproyecto/         # Aplicación principal (vistas, modelos, rutas)
├── evidencia/          # Evidencias del desarrollo y pruebas realizadas
├── staticfiles/        # Archivos estáticos recolectados (CSS, JS, imágenes)
├── .env.example        # Plantilla con las variables de entorno necesarias
├── .gitignore          # Archivos e historiales ignorados por Git
├── manage.py           # Script ejecutable de gestión de Django
├── requirements.txt    # Dependencias del proyecto
└── README.md           # Documentación del proyecto
