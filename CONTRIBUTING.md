# Cómo contribuir

Esta guía concentra el flujo de colaboración del equipo y de los agentes. La revisión, las decisiones y la autoría final pertenecen al equipo humano.

## Entrada rápida

La ruta de entrada es [README](README.md), [AGENTS](AGENTS.md), esta guía, la [base vigente](04-informe/00-base-del-proyecto.md) y el índice del área que se trabajará. Si ya recorriste un paso, continuá con el siguiente; no reinicies la lectura.

1. Leé la base vigente y las fuentes del curso pertinentes. Para el proyecto, consultá la [clase 8](01-material-del-curso/presentaciones/clase-08-coordinacion-y-proyecto.md), diapositivas 7–14, y su [PDF original](01-material-del-curso/presentaciones/clase-08-coordinacion-y-proyecto.pdf). La transcripción no verifica elementos visuales.
2. Acordá el resultado esperado, los archivos permitidos y las comprobaciones antes de escribir. Si el pedido es solo revisar o investigar, mantené el trabajo en lectura, sin crear archivos.
3. Revisá `git status --short --branch`. Identificá cambios previos, incluidos archivos sin seguimiento, y preservalos. Si una edición se cruza con trabajo ajeno, detenete y consultá.

## Qué documento manda

Las consignas se respaldan en el material del curso y las aclaraciones docentes verificadas, reunidas en las [consignas del proyecto](00-documentacion/consignas-del-proyecto.md). La base vigente registra el tema del equipo y distingue propuestas y decisiones abiertas. Los borradores, la planificación anterior y el archivo histórico no reemplazan esa definición ni prueban aprobación.

Ante contradicciones, señalá las fuentes y pedí una decisión al equipo; no inventes requisitos ni cierres acuerdos pendientes. Una guía interna no es una rúbrica docente. Las decisiones tomadas fuera del repositorio deben registrarse con confirmación humana, no inferirse.

## Dónde trabajar

| Área | Función |
| --- | --- |
| [00-documentacion](00-documentacion/README.md) | Consignas y guías internas. |
| [01-material-del-curso](01-material-del-curso/README.md) | Material original y transcripciones. |
| [02-planificacion](02-planificacion/README.md) | Objetivos de trabajo, tareas, responsables y calendario. |
| [03-investigacion](03-investigacion/README.md) | Fuentes y registro de evidencia. |
| [04-informe](04-informe/README.md) | Base vigente y borradores del informe. |
| [05-difusion](05-difusion/README.md) | Publicación, campaña e interacción. |
| [06-presentaciones](06-presentaciones/README.md) | Avances y presentación final. |
| [99-archivo](99-archivo/README.md) | Antecedentes históricos, no instrucciones vigentes. |

Las áreas de trabajo por defecto son `02-planificacion/` a `06-presentaciones/`, siempre dentro del alcance acordado. Modificar la base del repositorio (incluida esta guía), mover carpetas o crear áreas requiere autorización explícita según AGENTS. No reordenes archivos ni reescribas contenido académico para resolver una tarea documental.

## Trabajo con agentes

Cada encargo debe indicar objetivo, salida esperada (informe de lectura o edición), rutas permitidas y protegidas, contexto vigente, evidencia necesaria y comprobaciones. Una investigación de solo lectura no autoriza correcciones.

Si se reparten tareas, permití escritores simultáneos únicamente en archivos disjuntos. El agente coordinador integra las entregas y sus límites antes de la revisión humana; delegar no amplía permisos ni sustituye esa revisión. Cada entrega debe enumerar archivos cambiados, comprobaciones observadas, incertidumbres y decisiones pendientes. No des por aceptado el trabajo de otro agente sin revisarlo.

## Evidencia y redacción

Conservá las fuentes originales y registrá URL, página o sección, fechas y limitaciones en el [registro de investigación](03-investigacion/README.md), sin duplicar su ficha. Vinculá cada afirmación relevante con evidencia verificable y distinguí hechos, interpretación, propuesta y actividad realizada. Indicá si solo leíste un resumen o una transcripción.

El equipo adoptó IEEE; el registro de investigación define su uso y la integración de la numeración. Esto no demuestra una exigencia docente. No inventes datos, fuentes, opiniones de audiencia ni aprobación. No presentes consejos médicos o afirmaciones de salud sin evidencia pertinente, ni causalidad a partir de asociaciones.

## Comprobar y entregar

Antes de entregar una edición:

- Revisá el diff y confirmá que solo contiene la unidad acordada, sin alterar cambios previos.
- Comprobá destinos de enlaces locales modificados, nombres, índices y precedencia de la base vigente. Aclarar si no se revisaron anclas, enlaces externos o contenido visual.
- Ejecutá `git diff --check` y consultá nuevamente el estado. Para Markdown pasivo no hacen falta runners, automatizaciones ni pruebas de software.
- Informá resultado, rutas exactas, comprobaciones y límites; dejá las decisiones abiertas para el equipo.

## Git y publicación

No se exige crear una rama para cada edición documental. Consultá el estado actual antes de cualquier operación y acordá rama y alcance si hacen falta. Preparar staging o crear commits requiere pedido explícito: seleccioná solo las rutas y cambios autorizados, nunca todo el árbol por defecto, y mantené commits por unidad de trabajo revisable. Usá Conventional Commits cuando se solicite un commit, conforme a la convención del equipo.

Push, apertura de PR y publicación de contenido requieren autorizaciones separadas. Un permiso anterior no es autorización permanente. No presupongas remotos, historial sincronizado ni aprobación académica por la existencia de un commit.
