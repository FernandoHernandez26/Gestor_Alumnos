# 🎓 Gestor de Alumnos – Kotlin

Aplicación de consola desarrollada en **Kotlin** para gestionar alumnos, almacenar sus datos académicos y realizar diferentes operaciones sobre sus notas.

Este proyecto corresponde a la actividad **UD01 – Actividad 09**, realizada con IntelliJ IDEA.

## 📌 Descripción del proyecto

El Gestor de Alumnos permite administrar una lista de estudiantes de forma sencilla mediante un menú interactivo.

Cada alumno dispone de los siguientes datos:
- Nombre.
- Apellidos.
- Nota final.

El programa permite registrar, consultar, buscar y eliminar alumnos, además de realizar cálculos y clasificaciones según sus calificaciones.

## ⚙️ Funcionalidades

- **Registrar alumnos:** introducir nombre, apellidos y nota final.
- **Validación de datos:** comprobar que los campos no estén vacíos y que la nota sea numérica y esté entre 0 y 10.
- **Listar alumnos:** mostrar todos los estudiantes registrados.
- **Calcular media:** obtener la media de las notas del grupo.
- **Mostrar aprobados:** mostrar alumnos con una nota igual o superior a 5.
- **Mostrar suspensos:** mostrar alumnos con una nota inferior a 5.
- **Buscar alumnos:** localizar estudiantes por nombre o apellidos.
- **Eliminar alumnos:** borrar un estudiante mediante su posición en la lista.
- **Menú interactivo:** acceder a todas las funcionalidades desde la consola.

## 🛠️ Tecnologías utilizadas

- **Lenguaje:** Kotlin.
- **IDE:** IntelliJ IDEA.
- **Control de versiones:** Git.
- **Repositorio:** GitHub.

## 📁 Estructura del proyecto

```text
UD01_Actividad09_GestorAlumnos/
│
├── src/
│   ├── Alumno.kt
│   ├── GestorAlumnos.kt
│   └── Main.kt
│
├── .gitignore
└── README.md
```

### Organización de los archivos

| Archivo | Descripción |
|---|---|
| `Alumno.kt` | Define los datos de cada alumno. |
| `GestorAlumnos.kt` | Contiene las funciones de gestión y el menú principal. |
| `Main.kt` | Inicia la ejecución del programa. |

## ▶️ Ejecución del programa

1. Clonar el repositorio:

```bash
git clone URL_DEL_REPOSITORIO
```

2. Abrir el proyecto en IntelliJ IDEA.
3. Comprobar que Kotlin está correctamente configurado.
4. Ejecutar el archivo `Main.kt`.
5. Utilizar el menú de la consola para seleccionar las operaciones disponibles.

## 📋 Menú principal

El programa dispone de las siguientes opciones:

```text
===== GESTOR DE ALUMNOS =====

1. Registrar alumno
2. Listar alumnos
3. Calcular media del grupo
4. Mostrar aprobados
5. Mostrar suspensos
6. Buscar alumno
7. Eliminar alumno
8. Salir

Seleccione una opción:
```

## 📚 Conceptos trabajados

Durante el desarrollo del proyecto se han practicado los siguientes conceptos de Kotlin:

- Clases y objetos.
- Data Classes.
- Listas mutables (`MutableList`).
- Funciones.
- Condicionales (`if` y `when`).
- Bucles (`for` y `do while`).
- Validación de datos.
- Operadores lógicos.
- Filtrado y búsqueda de elementos.
- Gestión de colecciones.

## 🎯 Objetivo de aprendizaje

El objetivo de esta actividad es poner en práctica los fundamentos de programación con Kotlin, aprendiendo a organizar el código mediante clases y funciones independientes y desarrollando una aplicación funcional desde cero.

---

**Proyecto académico – UD01 · Actividad 09**

Desarrollado con Kotlin ❤️
