# Historial: versiones anteriores a la edición temática

Esta copia conserva los **21 archivos completos** que se modificaron al centrar el proyecto en alimentación y bienestar emocional. Permite recuperar el contenido que incluía ejercicio y descanso, tanto por archivo como para el conjunto de la edición.

- **Fecha de preparación:** 1 de noviembre de 2026.
- **Commit de origen:** `361f5477127ecd583a1cc7de068cbb05099ebb66` (`ppt full gepeto`).
- **Cobertura:** 19 documentos Markdown y 2 PowerPoint, con la misma estructura de carpetas del repositorio.
- **Integridad:** copias idénticas byte por byte al commit de origen. El [manifiesto](manifest.json) registra las rutas, tamaños y huellas SHA-256.
- **Estado:** archivo de consulta y restauración; la definición de trabajo está en la [base del proyecto](../../../04-informe/00-base-del-proyecto.md).

## Archivos conservados

La columna «Copia anterior» abre el respaldo; «Archivo de trabajo» abre su ubicación habitual. Las copias mantienen su contenido original, incluidos sus enlaces relativos: no forman un sitio autónomo y algunos de esos enlaces solo funcionan al restaurarlas a sus rutas habituales.

| Copia anterior | Archivo de trabajo | Contenido |
| --- | --- | --- |
| [00-documentacion/consignas-del-proyecto.md](archivos/00-documentacion/consignas-del-proyecto.md) | [Abrir](../../../00-documentacion/consignas-del-proyecto.md) | Tema del equipo y aplicacion de las consignas. |
| [00-documentacion/guia-revision-informe.md](archivos/00-documentacion/guia-revision-informe.md) | [Abrir](../../../00-documentacion/guia-revision-informe.md) | Contexto y criterios internos de revision. |
| [02-planificacion/01-objetivo-de-trabajo.md](archivos/02-planificacion/01-objetivo-de-trabajo.md) | [Abrir](../../../02-planificacion/01-objetivo-de-trabajo.md) | Contexto, motivacion y objetivos de trabajo. |
| [02-planificacion/README.md](archivos/02-planificacion/README.md) | [Abrir](../../../02-planificacion/README.md) | Definicion del tema y estado de la planificacion. |
| [02-planificacion/documentos-equipo/README.md](archivos/02-planificacion/documentos-equipo/README.md) | [Abrir](../../../02-planificacion/documentos-equipo/README.md) | Descripcion del tema de los documentos incorporados. |
| [03-investigacion/README.md](archivos/03-investigacion/README.md) | [Abrir](../../../03-investigacion/README.md) | Indice de las fuentes de investigacion. |
| [03-investigacion/fuentes-marco-teorico.md](archivos/03-investigacion/fuentes-marco-teorico.md) | [Abrir](../../../03-investigacion/fuentes-marco-teorico.md) | Registro bibliografico y comprobaciones de fuentes. |
| [04-informe/00-base-del-proyecto.md](archivos/04-informe/00-base-del-proyecto.md) | [Abrir](../../../04-informe/00-base-del-proyecto.md) | Definicion, enfoque, alcance y decisiones del proyecto. |
| [04-informe/01-problema-y-objetivos.md](archivos/04-informe/01-problema-y-objetivos.md) | [Abrir](../../../04-informe/01-problema-y-objetivos.md) | Problema, pregunta, objetivos y delimitacion. |
| [04-informe/02-introduccion.md](archivos/04-informe/02-introduccion.md) | [Abrir](../../../04-informe/02-introduccion.md) | Introduccion y registro de motivaciones. |
| [04-informe/03-marco-de-referencia.md](archivos/04-informe/03-marco-de-referencia.md) | [Abrir](../../../04-informe/03-marco-de-referencia.md) | Conceptos, antecedentes y referencias. |
| [04-informe/README.md](archivos/04-informe/README.md) | [Abrir](../../../04-informe/README.md) | Organizacion del informe. |
| [05-difusion/README.md](archivos/05-difusion/README.md) | [Abrir](../../../05-difusion/README.md) | Tema y preparacion de la difusion. |
| [06-presentaciones/README.md](archivos/06-presentaciones/README.md) | [Abrir](../../../06-presentaciones/README.md) | Indice y pautas de las presentaciones. |
| [06-presentaciones/guion-presentacion-avances.md](archivos/06-presentaciones/guion-presentacion-avances.md) | [Abrir](../../../06-presentaciones/guion-presentacion-avances.md) | Guion de avances y respaldo documental. |
| [06-presentaciones/presentacion/guion-version-mejorada.md](archivos/06-presentaciones/presentacion/guion-version-mejorada.md) | [Abrir](../../../06-presentaciones/presentacion/guion-version-mejorada.md) | Guion de la presentacion mejorada. |
| [06-presentaciones/presentacion/plan-de-presentacion.md](archivos/06-presentaciones/presentacion/plan-de-presentacion.md) | [Abrir](../../../06-presentaciones/presentacion/plan-de-presentacion.md) | Plan de preparacion de la presentacion. |
| [06-presentaciones/presentacion/presentacion-avances-grupo-7-mejorada.pptx](archivos/06-presentaciones/presentacion/presentacion-avances-grupo-7-mejorada.pptx) | [Abrir](../../../06-presentaciones/presentacion/presentacion-avances-grupo-7-mejorada.pptx) | PowerPoint completo con grafico bibliografico y notas. |
| [06-presentaciones/presentacion/presentacion-avances-grupo-7.pptx](archivos/06-presentaciones/presentacion/presentacion-avances-grupo-7.pptx) | [Abrir](../../../06-presentaciones/presentacion/presentacion-avances-grupo-7.pptx) | PowerPoint completo con sus notas. |
| [99-archivo/historial-asistente/base-del-proyecto.md](archivos/99-archivo/historial-asistente/base-del-proyecto.md) | [Abrir](../../../99-archivo/historial-asistente/base-del-proyecto.md) | Registro de contexto del asistente. |
| [README.md](archivos/README.md) | [Abrir](../../../README.md) | Presentacion del proyecto e indicaciones de continuidad. |

## Recuperar un archivo

Copiar el archivo elegido desde `archivos/` a la misma ruta relativa en la raíz del repositorio. Por ejemplo, para recuperar la base con el contenido conservado, ejecutar desde la raíz:

```powershell
Copy-Item -LiteralPath '99-archivo/historial/2026-11-01-enfoque-tres-habitos/archivos/04-informe/00-base-del-proyecto.md' -Destination '04-informe/00-base-del-proyecto.md'
```

La copia reemplaza ese archivo de trabajo. Guardar antes cualquier edición posterior que se quiera conservar. Para recuperar solo una parte del contenido, comparar ambas versiones e integrar los párrafos pertinentes en lugar de copiar el archivo completo.

## Revertir los 21 archivos juntos

El [parche de la edición](cambio-de-enfoque.patch) contiene únicamente los cambios temáticos de esos 21 archivos, incluidos los PowerPoint. No incluye esta carpeta de historial ni su incorporación al índice del archivo.

Desde la raíz del repositorio, comprobar primero que se pueda revertir:

```powershell
git apply --reverse --check -- '99-archivo/historial/2026-11-01-enfoque-tres-habitos/cambio-de-enfoque.patch'
```

Si la comprobación termina correctamente, aplicar la reversión cuando el equipo lo decida:

```powershell
git apply --reverse -- '99-archivo/historial/2026-11-01-enfoque-tres-habitos/cambio-de-enfoque.patch'
```

Después, revisar `git diff --stat` y `git diff --check`. Estos comandos modifican los archivos de trabajo; no crean commits, no preparan cambios ni alteran el historial de Git. Funcionan también después de confirmar la edición temática, siempre que los fragmentos afectados sigan siendo compatibles.

Si aparecen conflictos por ediciones posteriores, no forzar la aplicación: usar las copias completas para comparar y recuperar el contenido que corresponda. La comprobación de integridad de las copias se puede repetir comparando su SHA-256 con `manifest.json`.
