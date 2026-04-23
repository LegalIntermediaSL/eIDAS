# Plan de mejoras futuro para eIDAS

## Estado del documento

Este archivo deja prevista una hoja de ruta de mejora para el repositorio `eIDAS`.

Importante:

- este plan no se esta ejecutando ahora
- su funcion es servir como referencia para una fase posterior de trabajo
- las tareas aqui descritas deben activarse solo cuando se decida abrir una nueva pasada de mejora del proyecto

## Objetivo general

Mejorar la calidad editorial, la mantenibilidad, la trazabilidad y la publicacion del proyecto sin perder su enfoque divulgativo y modular.

## Principios de ejecucion futura

Cuando este plan se active, convendra seguir estos criterios:

- priorizar cambios que mejoren la confianza del lector
- evitar reorganizaciones bruscas sin actualizar enlaces internos
- separar claramente las mejoras de estructura de las mejoras de contenido
- tratar como especialmente sensibles los capitulos con mayor dependencia normativa o institucional
- documentar cada fase en `BITACORA.md` y `CHANGELOG.md` solo en el momento de ejecutarla

## Fase 1. Orden editorial y confianza documental

### Objetivo

Definir una base editorial comun para que el crecimiento futuro del tutorial sea mas consistente y mas facil de revisar.

### Tareas previstas

1. crear una plantilla minima comun para capitulos
2. redactar una guia editorial del repositorio
3. incorporar fecha de revision y estado normativo en capitulos clave
4. distinguir mejor entre contenido estable y contenido sujeto a revision periodica

### Entregables previstos

- `GUIA-EDITORIAL.md` o `CONTRIBUTING.md`
- plantilla de capitulo reutilizable
- actualizacion inicial de capitulos sensibles como `00`, `11`, `50` y `51`

### Resultado esperado

Un repositorio mas coherente, con criterios visibles y con mejor trazabilidad para lectores y futuras revisiones.

## Fase 2. Reorganizacion y mantenibilidad

### Objetivo

Reducir complejidad estructural y preparar el proyecto para crecer sin que `tutorial/` se vuelva dificil de mantener.

### Tareas previstas

1. reorganizar `tutorial/` por bloques tematicos
2. actualizar el indice principal en `README.md`
3. revisar y corregir enlaces internos tras la reorganizacion
4. estudiar fusiones o compactaciones de capitulos proximos si aportan claridad

### Estructura orientativa

- `tutorial/fundamentos/`
- `tutorial/servicios-confianza/`
- `tutorial/ecosistema/`
- `tutorial/implantacion/`
- `tutorial/eidas-2/`
- `tutorial/espana/`
- `tutorial/apoyo/`

### Resultado esperado

Una arquitectura documental mas clara tanto para mantenimiento interno como para lectura externa.

## Fase 3. Calidad continua y publicacion

### Objetivo

Preparar el proyecto para una evolucion sostenida, con controles basicos de calidad y una posible salida web.

### Tareas previstas

1. anadir validacion automatica en GitHub para Markdown y enlaces
2. definir una rutina periodica de revision de capitulos sensibles
3. preparar una version web documental del proyecto
4. coordinar mejor la relacion estructural con `eIDAS-en`

### Entregables previstos

- workflows basicos de GitHub
- criterio simple de mantenimiento periodico
- propuesta tecnica para publicacion web
- tabla de correspondencia basica entre ediciones por idioma

### Resultado esperado

Un proyecto mas robusto, publicable y facil de sostener en el tiempo.

## Prioridad recomendada cuando se active

Si mas adelante se decide ejecutar este plan, el orden sugerido es el siguiente:

1. guia editorial
2. plantilla minima de capitulo
3. metadatos de revision en capitulos clave
4. reorganizacion de carpetas
5. validacion automatica en GitHub
6. version web documental

## Riesgos y precauciones

- reorganizar carpetas sin revisar enlaces puede romper la navegacion
- anadir demasiadas reglas editoriales puede frenar futuras aportaciones
- mezclar en una sola fase cambios estructurales y redaccion de fondo puede dificultar la validacion
- la parte relativa a Espana y eIDAS 2.0 requerira especial atencion por su mayor sensibilidad temporal

## Criterio de activacion futura

Este plan deberia activarse solo cuando se cumpla al menos una de estas condiciones:

- se quiera preparar una nueva fase de calidad editorial
- se detecte que `tutorial/` empieza a resultar dificil de mantener
- se decida publicar el contenido en formato web
- se quiera alinear mejor la edicion en espanol con `eIDAS-en`

## Nota final

Este documento no implica ningun cambio operativo inmediato. Su finalidad es dejar prevista una hoja de ruta clara para retomarla mas adelante con contexto y orden.
