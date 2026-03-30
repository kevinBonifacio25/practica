# practica
practica riwi

#Sistema de Registro de Estudiantes (CRUD)
Este es un programa en Python diseñado para gestionar el registro de alumnos de forma eficiente. El sistema permite realizar las operaciones básicas de un CRUD (Crear, Leer, Actualizar y Eliminar) interactuando con archivos JSON para la persistencia de datos.
# Características
El programa cuenta con las siguientes funcionalidades principales:

    Registro Dinámico: Permite dar de alta a múltiples estudiantes capturando ID, nombre, edad, curso y estado.
    Consulta General: Muestra una lista detallada de todos los alumnos registrados.
    Búsqueda Específica: Localiza a un estudiante rápidamente mediante su número de identificación (ID).
    Actualización de Datos: Permite modificar el estado, curso y edad de un alumno existente.
    Eliminación de Registros: Borra estudiantes del sistema de forma permanente.
    Persistencia de Datos: Los cambios se guardan automáticamente en un archivo local a través de un módulo de gestión de archivos (crud.py).

# Estructura del Código
El proyecto está organizado en funciones modulares para facilitar su mantenimiento:

    register_students(): Gestiona la entrada de nuevos datos.
    show_student_list(): Formatea y muestra la información en pantalla.
    search_students(): Implementa la lógica de filtrado por ID.
    update_student(): Permite la edición de campos críticos del estudiante.
    delete_student(): Maneja la lógica de remoción de elementos de la lista.

# Requisitos

    Python 3.x
    Módulo recyclable_functions: Utilizado para la validación de entradas numéricas.
    Módulo crud: Utilizado para el guardado y carga de datos en formato JSON.

# Ejemplo de Uso
Al ejecutar el programa, podrás interactuar con el panel de registro:

text

---REGISTRATION PANEL---
Enter the number of students: 1
Registering student 1 of 1:
Enter the student ID: 101
Enter the student name: Juan Perez
...
