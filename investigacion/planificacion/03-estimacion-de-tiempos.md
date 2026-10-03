# 3. Estimación de tiempo de cada tarea

Corresponde a ppt-9, diapositiva 6: "Estimar el tiempo de cada una de las actividades, considerando holgura para imprevistos y responsables de c/u". **Estado:** versión 1, completa. Las cifras son **estimaciones**: no son horas trabajadas y quedan sujetas a la [validación del equipo](README.md#validación-del-equipo).

**Criterios:**
- **Duración** son los días corridos que la tarea ocupa en la [Gantt](05-carta-gantt.md). Se calcula como **trabajo estimado + holgura**.
- **Holgura** son los días de margen para imprevistos incluidos al final de cada tarea.
- **Responsable** es quien responde por la tarea (A en la [RACI](04-matriz-raci.md)).
- **HH** son las horas-persona totales de la tarea, sumando a todas las personas que participan ([detalle por persona](06-presupuesto-hh.md)).

| ID | Tarea | Inicio | Fin | Trabajo (días) | Holgura (días) | Duración (días) | Responsable (A) | HH |
| --- | --- | --- | --- | :---: | :---: | :---: | --- | :---: |
| T01 | Lluvia de ideas | 05/10 | 09/10 | 4 | 1 | 5 | José Villamayor | 13 |
| T02 | Objetivo de trabajo | 10/10 | 14/10 | 4 | 1 | 5 | Claudio Toledo | 5 |
| T03 | Planificación validada | 12/10 | 16/10 | 4 | 1 | 5 | Rodolfo Fernández | 5 |
| T04 | Revisión inicial | 12/10 | 18/10 | 5 | 2 | 7 | Álvaro Catalán | 5 |
| T05 | Definición del problema | 19/10 | 23/10 | 4 | 1 | 5 | Claudio Toledo | 7 |
| T06 | Marco teórico | 22/10 | 31/10 | 8 | 2 | 10 | Álvaro Catalán | 9 |
| T07 | Marco metodológico | 26/10 | 03/11 | 7 | 2 | 9 | Isidora Osorio | 8 |
| T08 | Presentación de avances | 28/10 | 01/11 | 4 | 1 | 5 | Rodolfo Fernández | 9 |
| T09 | Aplicación del instrumento | 04/11 | 09/11 | 5 | 1 | 6 | Isidora Osorio | 7 |
| T10 | Análisis de resultados | 10/11 | 13/11 | 3 | 1 | 4 | Isidora Osorio | 8 |
| T11 | Propuesta de solución | 14/11 | 17/11 | 3 | 1 | 4 | José Villamayor | 7 |
| T12 | Informe de investigación | 04/11 | 20/11 | 14 | 3 | 17 | Claudio Toledo | 14 |
| T13 | Publicación digital | 04/11 | 15/11 | 10 | 2 | 12 | Paula Eguileor | 10 |
| T14 | Campaña de difusión | 12/11 | 21/11 | 8 | 2 | 10 | Paula Eguileor | 7 |
| T15 | Interacción con audiencia | 04/11 | 21/11 | 15 | 3 | 18 | Rodolfo Fernández | 7 |
| T16 | Presentación final | 18/11 | 22/11 | 4 | 1 | 5 | Álvaro Catalán | 10 |
| T17 | Coordinación y seguimiento | 05/10 | 23/11 | Continua | — | 50 | José Villamayor | 42 |
| | **Total** | | | | | | | **173** |

**Hitos fijos:** presentación de avances el **02/11**, al día siguiente del fin de T08, y presentación final el **23/11**, al día siguiente del fin de T16.

## Ruta crítica y riesgos

- **Ruta crítica (propuesta):** T05 → T06 → T07 → T09 → T10 → T11 → T16. Un atraso en el método (T07) atrasa la recolección, el análisis y la propuesta.
- **Noviembre es la parte más ajustada.** Entre el 02/11 y el 23/11 coinciden la recolección, el análisis, el informe, la publicación, la campaña y la interacción. Para dar margen, la plataforma (T13) y la modalidad de interacción (T15) se eligen la semana del 04/11, y la redacción del informe parte con las secciones que ya estén listas.
- **Si no se recolectan datos (T09):** T10 se apoya en las fuentes revisadas, el calendario de noviembre gana unos 6 días y el presupuesto baja 7 HH.
- La fecha de entrega del Avance 1 no está confirmada. Si es antes del 09/10, hay que adelantar T01.
