# Actividad 2: tutorial práctico de VS Code, Git y GitHub

**Institución:** Centro Educativo Nonogasta (CEN)  
**Materia:** Base de Datos  
**Docente:** Tec. Perea Lazo Alex N.  
**Modalidad:** individual o en grupos de hasta **4 integrantes**  
**Producto:** repositorio de GitHub y video tutorial grabado

## Propósito

En la actividad anterior investigaron qué son Git y GitHub. Ahora deberán ponerlo en práctica y **enseñar a otra persona** cómo trabajar con un proyecto abierto en Visual Studio Code (VS Code), registrar cambios desde su terminal y subirlos a GitHub.

## Investigación previa

Busquen tutoriales en YouTube sobre cómo instalar o configurar Git, trabajar con la terminal de VS Code y vincular un repositorio local con GitHub. Prueben los pasos antes de grabar. Pueden consultar otras fuentes si las necesitan.

El video que entreguen debe ser **propio**: expliquen con sus palabras y muestren los pasos funcionando en su computadora. En el `README.md` registren los enlaces de los tutoriales y recursos que consultaron.

## Proyecto de ejemplo

Creen una carpeta de proyecto sencilla, relacionada con Base de Datos. Debe contener al menos:

```text
mi-proyecto-bd/
├── README.md
└── schema.sql
```

En `schema.sql` pueden crear una tabla simple, por ejemplo `libros`, `estudiantes` o `turnos`. El objetivo de esta actividad es demostrar el uso de Git y GitHub; **no hace falta desarrollar una base de datos completa**. Usen únicamente datos ficticios y no publiquen contraseñas ni credenciales.

## Video tutorial obligatorio

Graben **su pantalla y su voz** mientras explican lo que hacen. Pueden utilizar OBS Studio para la grabación. La cámara es **opcional**: aparecer en cámara suma puntaje adicional, pero no es un requisito para obtener la nota máxima.

**Duración orientativa:** 5 a 8 minutos. Todos los integrantes deben participar con una explicación o una acción concreta durante el tutorial.

El video debe mostrar, en orden:

1. **Presentación breve:** nombres de los integrantes, objetivo del tutorial y proyecto que utilizarán.
2. **Preparación:** carpeta abierta en VS Code, archivos del proyecto y terminal integrada. Muestren cómo comprueban que Git está disponible. Si la cuenta de GitHub ya está vinculada en esa computadora, indíquenlo; si necesitan iniciar sesión, eviten grabar contraseñas o códigos.
3. **Primer registro:** ejecuten y expliquen `git init`, `git status`, `git add` y `git commit -m "mensaje descriptivo"`.
4. **Conexión con GitHub:** creen un repositorio en GitHub, vincúlenlo desde la terminal con `git remote add origin URL` y suban el proyecto con `git push`. Expliquen qué significa `origin` y qué hace `push`. Si necesitan indicar la rama o configurar el primer envío, muestren el comando que usaron.
5. **Segundo cambio:** modifiquen un archivo, revisen el resultado con `git status`, hagan un **segundo commit** y vuelvan a subirlo.
6. **Comprobación:** abran GitHub y muestren los archivos publicados y el historial de los dos commits.
7. **Cierre:** expliquen la diferencia entre guardar un archivo, hacer un commit y subir los cambios a GitHub.

No basta con leer una lista de comandos: expliquen **para qué usan cada uno** y muestren el resultado en pantalla. Antes de entregar, reproduzcan el video completo para verificar que se entiende la voz y que la terminal se puede leer.

## Apartado «Cómo hicimos el tutorial»

Agreguen al `README.md` un apartado con ese título. Incluyan:

- Las herramientas utilizadas (por ejemplo, VS Code, Git, GitHub, OBS Studio y alguna herramienta de edición, si la usaron).
- Los enlaces a los videos de YouTube y demás fuentes que consultaron.
- Cómo organizaron la grabación y qué hizo cada integrante.
- Un problema que encontraron durante la práctica y cómo lo resolvieron, **si se presentó alguno**.

Redacten este apartado de forma breve y con sus propias palabras.

## Entrega

**Suban el archivo de video mediante el enlace de entrega proporcionado por el docente.** En esa misma entrega incluyan el enlace al repositorio de GitHub. Antes de enviarlo, comprueben que el repositorio se puede abrir y que el video se reproduce correctamente.

No se reemplaza el video por un enlace al tutorial de otra persona: el archivo entregado debe contener **su propia grabación de pantalla con audio explicativo**.

## Criterios de evaluación

| Criterio | Puntos |
|---|---:|
| Explica la preparación en VS Code y la conexión entre el proyecto local y GitHub | 2 |
| Usa y explica los comandos desde la terminal de VS Code | 3 |
| Realiza dos commits con cambios reales y verifica el resultado en GitHub | 2 |
| Video claro: pantalla legible, audio explicativo y participación de todos los integrantes | 2 |
| `README.md` con el apartado «Cómo hicimos el tutorial», herramientas y fuentes consultadas | 1 |
| **Total** | **10** |

**Punto adicional (opcional):** pueden sumar **hasta 1 punto**, sin superar la nota máxima de **10**, si incorporan cámara de forma clara y útil durante la explicación. La cámara no es necesaria para obtener 10 puntos con los criterios obligatorios.
