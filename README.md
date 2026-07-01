# Registro de Estudiantes — Actividad Entregable No. 3

Aplicación web para registrar, consultar, actualizar y eliminar información de
estudiantes, desarrollada con **HTML5, JavaScript y CSS3**, sin bases de datos
ni frameworks. Toda la información se administra mediante arreglos y objetos
de JavaScript.

**Autor:** Juniors Stivens Marin Lopez
**Institución:** Uniempresarial
**Asignatura:** Lenguajes de Programación
**Docente:** Kellyn Johanna Delgado Jaimes

## Funcionalidades

- **Registrar estudiantes**: documento, nombre completo, programa académico,
  nota 1, nota 2 y nota 3.
- **Cálculo automático**: nota definitiva (promedio de las 3 notas) y estado
  (Aprobado / Reprobado, con nota mínima de aprobación 3.0).
- **Listado dinámico** con documento, nombre, programa, promedio y estado.
- **Búsqueda** de estudiantes por número de documento.
- **Edición** de cualquier dato excepto el documento y el promedio (este
  último se recalcula automáticamente).
- **Eliminación** de registros existentes, con confirmación previa.
- **Validaciones**:
  - Ningún campo puede quedar vacío.
  - El documento no se puede repetir.
  - Las notas deben estar entre 0 y 5.
  - Los campos numéricos (documento y notas) solo aceptan números.

## Cómo usar la aplicación

1. Clona o descarga este repositorio.
2. Abre el archivo `index.html` en cualquier navegador web moderno
   (Chrome, Edge, Firefox).
3. No requiere instalación, servidor ni dependencias externas.

## Estructura del proyecto

```
├── index.html   # Estructura, estilos (CSS3) y lógica (JavaScript)
└── README.md    # Documentación del proyecto
```

## Tecnologías

- HTML5
- CSS3
- JavaScript (ES6+), sin frameworks ni librerías externas
