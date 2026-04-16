# Contexto del Repositorio de Actividades Universitarias

Este repositorio contiene las actividades, ejercicios y proyectos universitarios del alumno.
Está organizado por carpetas que corresponden a cada asignatura.
Actualmente, las asignaturas principales son:

- `Modelos_Regresion/`: Para la asignatura de Modelos de Regresión.
- `Proyecto_IA/`: Para la asignatura de Proyecto de Inteligencia Artificial.

## Reglas para las IAs que trabajen en este repositorio:

1. **Formato:** Las soluciones a los ejercicios deben realizarse en archivos R Markdown (`.rmd` o `.Rmd`), con el código en R necesario para resolverlos.
2. **Imágenes:** Si hay imágenes que forman parte del enunciado de los ejercicios, deben guardarse localmente en una subcarpeta `img/` dentro de la carpeta de la asignatura, e incluirse en el archivo `.rmd` usando la sintaxis de Markdown `![Descripción](img/nombre_imagen.png)`.
3. **Explicaciones:** El código debe estar debidamente comentado, explicando paso a paso la lógica de la resolución. El uso de R debe mostrar claramente los pasos intermedios (por ejemplo, cálculo de frecuencias esperadas o estadísticos celda a celda) en lugar de utilizar solo funciones automáticas de resumen (como `chisq.test`), para evidenciar el procedimiento manual de aprendizaje, aunque también se pueden usar las funciones automáticas para comprobar los resultados.
4. **Datos:** Los datos proporcionados en los enunciados deben ingresarse manualmente en data frames o matrices al inicio de la resolución del ejercicio.
5. **Autor:** El autor de los ejercicios es Jordi Gisbert Ferriz.

## Estructura del Repositorio y Metodología General

6. **Estructura de Carpetas:** Cada nueva práctica se debe crear en una nueva carpeta con el nombre `Practica_DD_MM_YY`. Si la práctica pertenece a un bloque o subsección (por ejemplo, `Informatica`), la carpeta debe crearse dentro de esa ruta (ej. `Proyecto_IA/Informatica/Practica_DD_MM_YY`).
7. **Nombres de Archivos:** El archivo principal R Markdown debe tener exactamente el mismo nombre que la carpeta que lo contiene (ej. `Practica_DD_MM_YY.rmd`).
8. **Autocontención de Recursos:** Siempre que una práctica requiera de recursos externos (como datasets en formato `.csv`, `.xlsx`, etc.) que ya existan de forma general en el repositorio, **se debe hacer una copia** de estos archivos dentro de la carpeta específica de la nueva práctica. Esto asegura que cada práctica esté autocontenida con sus propios datos e imágenes.
9. **Apartados Opcionales:** Como metodología general, si una práctica o ejercicio contiene apartados marcados como "opcionales", estos **siempre** deben realizarse de todas formas para maximizar el aprendizaje.
10. **Formatos de Salida:** La resolución debe entregarse siempre incluyendo el archivo `.rmd` original y el archivo compilado en formato `.html`.
