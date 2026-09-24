# Investigación sobre Git y GitHub aplicada a Base de Datos

**Actividad de investigación e informe escrito**

- **Institución:** Centro Educativo Nonogasta (CEN).
- **Materia:** Base de Datos.
- **Docente:** Tec. Perea Lazo Alex N.
- **Modalidad:** individual o en grupos de hasta **4 integrantes**.

## Propósito

Investigar cómo Git y GitHub permiten registrar cambios, recuperar versiones y coordinar el trabajo en un proyecto de base de datos. Los conceptos deberán aplicarse a un ejemplo concreto con archivos SQL, como la creación y evolución de una base de datos para un sistema escolar, una biblioteca o un sistema de turnos.

## Pregunta central

> ¿Cómo ayuda el control de versiones a organizar los cambios en la estructura y las consultas de una base de datos cuando varias personas trabajan en un mismo proyecto?

## Producto y formato

Elaboren **un informe escrito en PDF**. Pueden redactarlo en el procesador de textos que prefieran y exportarlo a PDF antes de entregarlo. Extensión orientativa: **4 a 7 páginas de desarrollo**, sin contar portada, índice ni bibliografía. No se requiere una presentación de diapositivas.

### Presentación obligatoria del informe

1. **Portada:** institución, título, materia, curso y división, docente, nombres y apellidos de todos los integrantes y fecha de entrega.
2. **Índice:** títulos y subtítulos con sus números de página, actualizados al finalizar el trabajo.
3. **Introducción:** tema, propósito y ejemplo de base de datos elegido.
4. **Desarrollo:** apartados numerados, con explicaciones propias y ejemplos vinculados a Base de Datos.
5. **Conclusión:** respuesta argumentada a la pregunta central.
6. **Bibliografía:** autor u organización, título, enlace y fecha de consulta de cada fuente utilizada. Indiquen junto a cada imagen o figura de dónde proviene si no es propia.
7. **Encabezado y pie de página:** incluyan en el encabezado un título breve y el curso/división; en el pie, la numeración de páginas y una identificación breve del grupo o de la materia.

Usen títulos claros, texto legible y numeración de páginas que coincida con el índice. Pueden incorporar un diagrama entidad–relación, un esquema de tablas o capturas si ayudan a explicar el ejemplo; cada figura debe tener título.

## Contenido obligatorio del desarrollo

### 1. Git, GitHub y control de versiones

- ¿Qué es Git y para qué sirve?
- ¿Qué es GitHub y en qué se diferencia de Git?
- ¿Qué significa guardar versiones de un proyecto? Expliquen un caso en que necesiten recuperar una versión anterior de un script SQL.

### 2. Conceptos fundamentales

Expliquen con palabras propias **repositorio, commit, rama (branch), push, pull y clone**. Para cada concepto, den un ejemplo relacionado con archivos de una base de datos. Por ejemplo, un commit que agrega una tabla `clientes` o una rama para desarrollar nuevas consultas.

### 3. Organización de un proyecto de base de datos

Propongan una estructura sencilla de carpetas y archivos que permita conservar el esquema, los cambios y las consultas del proyecto. Identifiquen la función de archivos como `README.md`, `schema.sql`, `migraciones/001_crear_tablas.sql` y `consultas/reportes.sql`. Expliquen por qué conviene usar nombres descriptivos y registrar cada modificación.

Aclaren qué **no se debe publicar** en un repositorio: contraseñas, credenciales, archivos de configuración con datos sensibles o bases de datos que contengan información personal real. Para el ejemplo, utilicen datos ficticios si necesitan mostrar registros.

### 4. Flujo de trabajo y comandos esenciales

Describan, en orden, cómo una persona modifica un archivo SQL, revisa los cambios, crea un commit y comparte el trabajo en GitHub. Expliquen **qué hace y cuándo usarían** cada comando:

| Comando | Función en el proyecto |
|---|---|
| `git init` | Iniciar el seguimiento de versiones en la carpeta del proyecto. |
| `git status` | Revisar qué archivos SQL cambiaron. |
| `git add .` | Preparar los cambios elegidos para el siguiente commit; antes hay que revisar qué archivos se incluyen. |
| `git commit -m "mensaje"` | Registrar una versión con una descripción clara. |
| `git push` | Subir los commits al repositorio remoto. |
| `git pull` | Traer e integrar cambios realizados en el repositorio remoto. |
| `git clone URL` | Obtener una copia local de un repositorio existente. |

### 5. Trabajo colaborativo y conflictos

- ¿Cómo pueden distribuirse las tareas si un integrante diseña tablas, otro agrega consultas y otro documenta el proyecto?
- ¿Qué ocurre si dos personas cambian el mismo archivo SQL? Expliquen qué es un conflicto y cómo revisarían el archivo antes de resolverlo.
- ¿Por qué es importante acordar el orden de los cambios del esquema y documentar las migraciones?

### 6. Ejemplo práctico aplicado a Base de Datos

Elijan **un caso concreto**: biblioteca, sistema de turnos, gestión de estudiantes u otro proyecto de base de datos. En el informe:

1. Describan brevemente las entidades o tablas principales y su relación. Incluyan un diagrama o una tabla explicativa.
2. Muestren una estructura de archivos que contenga al menos un script de creación de tablas y un archivo de consultas.
3. Propongan **tres cambios concretos** en el proyecto, por ejemplo crear una tabla, agregar una relación o incorporar una consulta `SELECT` con `JOIN`.
4. Redacten **un mensaje de commit para cada cambio** e indiquen qué archivo modificarían.
5. Expliquen cómo compartirían los cambios con el resto del grupo. No hace falta crear un repositorio real: deben demostrar que comprenden el proceso.

**Ejemplos de mensajes de commit:**

```text
Crea tablas de libros y préstamos
Agrega clave foránea de préstamos a estudiantes
Incorpora consulta de libros prestados por estudiante
```

## Condiciones de elaboración

- Redacten con palabras propias y relacionen las definiciones con el ejemplo elegido.
- Citen las fuentes utilizadas y consignen sus enlaces completos en la bibliografía.
- Si incluyen fragmentos de SQL, expliquen qué hacen y revisen que sean coherentes con sus tablas.
- Todos los integrantes deben figurar en la portada y participar en la elaboración.
- Revisen ortografía, claridad, correspondencia entre el índice y las páginas y legibilidad del PDF.

## Criterios de evaluación

| Criterio | Descripción | Valor |
|---|---|---:|
| Comprensión conceptual | Explica Git, GitHub, los conceptos y los comandos con precisión. | 3 puntos |
| Aplicación a Base de Datos | Presenta un ejemplo coherente, tres cambios y sus commits correspondientes. | 3 puntos |
| Organización del informe | Incluye portada, índice, introducción, desarrollo, conclusión, bibliografía, encabezado, pie y páginas numeradas. | 2 puntos |
| Redacción y fuentes | Usa palabras propias, escribe con claridad y acredita las fuentes consultadas. | 2 puntos |

**Total: 10 puntos.**
