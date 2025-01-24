# TaskMaster
**TaskMaster** es una aplicación para la gestión de tareas personales y de equipo. Diseñada para facilitar la organización y el seguimiento de proyectos.

---

## Tabla de Contenidos

1. [Descripción del Proyecto](#descripción-del-proyecto)  
2. [Instalación](#instalación)  
3. [Uso de la Aplicación](#uso-de-la-aplicación)  
4. [Funcionalidades Principales](#funcionalidades-principales)  
5. [Contribución](#contribución)  
6. [Licencia](#licencia)  
7. [Dependencias](#dependencias)  
8. [Enlaces](#enlaces)  

---

## Descripción del Proyecto

**TaskMaster** es una aplicación web desarrollada en **Django** que permite:  

- **Crear** tareas individuales o grupales.  
- **Asignar** tareas a miembros del equipo.  
- **Gestionar** el progreso de las tareas con vistas intuitivas.  
- **Compartir** información en tiempo real gracias a la sincronización en la nube.  

Diseñada para resolver problemas comunes de organización en equipos de trabajo y para personas que buscan una forma efectiva de gestionar su tiempo y recursos.  

---

## Instalación

1. **Clonar el repositorio desde GitHub:**  
   `git clone https://github.com/tu-usuario/taskmaster.git && cd taskmaster`  

2. **Crear y activar un entorno virtual:**  
   `python -m venv venv && source venv/bin/activate` *(Linux)*  
   `python -m venv venv && venv\Scripts\activate` *(Windows)*  

3. **Instalar las dependencias necesarias:**  
   `pip install -r requirements.txt`  

4. **Configurar la base de datos y ejecutar las migraciones:**  
   `python manage.py migrate`  

5. **Iniciar el servidor de desarrollo:**  
   `python manage.py runserver`  
