# Análisis y resultados de la encuesta de alimentación y bienestar emocional

**Fecha de documentación y comprobación:** 9 de noviembre de 2026.

**Estado actualizado:** análisis descriptivo integrado en [metodología](../../04-informe/04-metodologia.md) y [resultados/discusión](../../04-informe/05-resultados-y-discusion.md), para revisión humana. El equipo confirmó contexto de convocatoria y corrección de oferta a cuatro menciones. No acredita aprobación académica ni cierre de todas las actividades del proyecto.

Se analizaron 28 respuestas con consentimiento registrado. Los recuentos cuantitativos examinados en la presentación coinciden con los datos originales. La muestra describe hábitos y percepciones; permite explorar relaciones entre respuestas, pero no demostrar efectos causales ni generalizar a todos los universitarios. La clasificación de oferta/acceso se adoptó con cuatro menciones explícitas por confirmación del equipo el 09/11/2026.

## 1. Fuentes y alcance del registro

- **Datos:** [respuestas.csv](respuestas.csv) [1], utilizado como base de los cálculos. Contiene una cabecera y 28 registros, con 10 columnas: marca temporal y nueve preguntas. Se conserva el orden original.
- **Instrumento:** [cuestionario.pdf](cuestionario.pdf) [2], consultado para identificar preguntas, opciones, extremos de escalas y carácter opcional de la pregunta abierta.
- **Presentación revisada:** [Google Slides del Grupo 7](https://docs.google.com/presentation/d/1rYNkAdvOsKViEXgj7YNpkpBYTqQ7FZmNchjxMbJNwdI/edit) [3], contenido y notas consultados el 09/11/2026. Tenía 11 diapositivas activas y 16 omitidas durante la exposición; este registro distingue ambas partes.

Este documento reúne resultados antes dispersos entre los datos, la presentación y la revisión del repositorio. Su alcance es documentar los cálculos, su interpretación y los límites; incorpora las confirmaciones disponibles de convocatoria, sin modificar el instrumento. Los detalles aún desconocidos se conservan como pendientes.

### Comprobaciones sobre los archivos

- Los 28 registros indican «Sí, acepto participar» y tienen completas las preguntas cerradas P2–P8.
- P9 tiene 22 respuestas no vacías y 6 vacías. Su denominador de análisis es 22, no 28.
- Se compararon las 29 filas y 10 columnas de CSV y [Excel](respuestas.xlsx), sin reordenar registros. Coinciden tras normalizar espacios, representaciones numéricas y fechas. Las marcas temporales numéricas de Excel se convirtieron a fecha y hora, con tolerancia inferior a un segundo respecto del CSV.
- No se eliminaron registros ni se alteraron los archivos originales. Que un registro esté completo y tenga consentimiento no permite comprobar identidad, elegibilidad universitaria o independencia de las respuestas.

**Versión del CSV utilizada, SHA-256:** `64781817468df07f00eb8f7caef24f00600b1afe003a488fb3ca2e5cc4276014`. Si cambia ese archivo, deben recalcularse estos resultados.

## 2. Criterios de cálculo e interpretación

Los números P1–P9 corresponden a las preguntas del PDF. La marca temporal no se cuenta como pregunta.

1. Cada registro representa una respuesta recibida. Para P1–P8 se usan los 28 registros disponibles; P9 se analiza entre las 22 respuestas no vacías.
2. Los porcentajes se calculan como `100 × recuento / denominador` y se presentan con un decimal. Pueden no sumar exactamente 100 % por redondeo.
3. Para los cruces se agrupan los puntajes **4–5** y **1–3** de las escalas pertinentes. Son agrupaciones exploratorias para describir esta muestra, no umbrales clínicos validados. El grupo 1–3 incluye la respuesta intermedia 3 y no se denomina «estrés bajo».
4. Para P4 se agrupan **3–4 y 5 o más veces por semana** frente a **menos de una y 1–2 veces por semana**. La pregunta reúne snacks ultraprocesados, bebidas azucaradas y comida rápida; no permite atribuir el resultado a un producto por separado.
5. Se documentan frecuencias y dos tablas de contingencia. No se realizaron pruebas de significación, intervalos de confianza, modelos ajustados ni controles de posibles factores de confusión. Los cruces no fueron registrados previamente como un plan confirmatorio.
6. La comparación con la literatura es conceptual y exploratoria. Una coincidencia de dirección no equivale a replicar un estudio con instrumentos y participantes distintos.

## 3. Registros y composición de la muestra

Las marcas temporales observadas van del **30/10/2026 a las 14:15:31** al **01/11/2026 a las 16:59:32**, con la indicación `GMT-3` del CSV. Este intervalo describe los registros recibidos; no acredita por sí solo las fechas oficiales de apertura y cierre del formulario ni el lugar de residencia de los participantes.

### P1 Consentimiento

Los 28 registros indican aceptación: **28/28, 100 %**.

### P2 Etapa de la carrera

| Respuesta | n | % de 28 |
| --- | ---: | ---: |
| Primer año | 2 | 7,1 |
| Segundo o tercer año | 5 | 17,9 |
| Cuarto año o superior / egreso | 20 | 71,4 |
| Posgrado | 1 | 3,6 |

La categoría más frecuente es cuarto año o superior / egreso. Posgrado se conserva como categoría separada. La composición debe tenerse presente al interpretar los resultados: no es una distribución equilibrada por etapa académica.

La participación se presenta como voluntaria y anónima en el instrumento. **Confirmación del equipo, 09/11/2026:** Google Forms, convocatoria a estudiantes de PUCV y ausencia de criterios concretos. Google Forms es la herramienta, no el canal específico de invitación, que sigue sin documentar. No se verifican afiliación, campus o residencia de cada registro; no se presupone muestreo aleatorio ni representatividad.

## 4. Distribuciones de las preguntas cerradas

Resultados calculados desde [1]. En todas estas tablas el denominador es 28.

### P3 Regularidad del desayuno

| Respuesta | n | % |
| --- | ---: | ---: |
| Rara vez o nunca, 0–1 día por semana | 4 | 14,3 |
| Ocasionalmente, 2–3 días por semana | 5 | 17,9 |
| Frecuentemente, 4–5 días por semana | 6 | 21,4 |
| Todos o casi todos los días, 6–7 días por semana | 13 | 46,4 |

La categoría más frecuente es **todos o casi todos los días**, con 13 respuestas. No debe resumirse como «todos los días» sin conservar el «casi», porque la categoría también incluye seis días por semana.

### P4 Frecuencia del conjunto de productos preguntado

| Respuesta | n | % |
| --- | ---: | ---: |
| Menos de 1 vez por semana | 5 | 17,9 |
| 1–2 veces por semana | 8 | 28,6 |
| 3–4 veces por semana | 9 | 32,1 |
| 5 o más veces por semana | 6 | 21,4 |

En conjunto, **15/28, 53,6 %**, declaran consumir alguno de los productos agrupados tres o más veces por semana. El cuestionario no permite determinar cuál de esos productos consumen ni estimar porciones o calidad global de la dieta.

### P5 Alimentación en respuesta a emociones

Extremos de la escala: **1 = casi nunca; 5 = muy frecuentemente**. La pregunta menciona estrés, ansiedad o aburrimiento en lugar de hambre física; no mide esas emociones por separado.

| Puntaje | n | % |
| --- | ---: | ---: |
| 1 | 6 | 21,4 |
| 2 | 5 | 17,9 |
| 3 | 6 | 21,4 |
| 4 | 6 | 21,4 |
| 5 | 5 | 17,9 |

Hay **11/28, 39,3 %**, en 4–5 y otros **11/28, 39,3 %**, en 1–2. Los 6 restantes marcaron 3. Estas respuestas no constituyen un diagnóstico ni una puntuación de una escala validada de comer emocional.

### P6 Estrés habitual durante el período académico

Extremos: **1 = muy bajo; 5 = muy alto**.

| Puntaje | n | % |
| --- | ---: | ---: |
| 1 | 1 | 3,6 |
| 2 | 2 | 7,1 |
| 3 | 12 | 42,9 |
| 4 | 9 | 32,1 |
| 5 | 4 | 14,3 |

El puntaje más frecuente es 3. El grupo 4–5 reúne **13/28, 46,4 %**. Esta agrupación describe estrés autorreportado; no es una clasificación clínica.

### P7 Fatiga o falta de energía persistente

Extremos: **1 = casi nunca; 5 = casi a diario**.

| Puntaje | n | % |
| --- | ---: | ---: |
| 1 | 2 | 7,1 |
| 2 | 9 | 32,1 |
| 3 | 10 | 35,7 |
| 4 | 5 | 17,9 |
| 5 | 2 | 7,1 |

Los puntajes 4–5 reúnen **7/28, 25,0 %**. La respuesta no identifica la causa de la fatiga ni permite atribuirla a la alimentación.

### P8 Percepción de la influencia de la alimentación en el ánimo

Extremos: **1 = nada; 5 = muchísimo**.

| Puntaje | n | % |
| --- | ---: | ---: |
| 1 | 0 | 0,0 |
| 2 | 1 | 3,6 |
| 3 | 11 | 39,3 |
| 4 | 11 | 39,3 |
| 5 | 5 | 17,9 |

Los puntajes 4–5 reúnen **16/28, 57,1 %**. Es una percepción declarada, no la medición de un efecto de la alimentación en el ánimo. La pregunta usa la expresión «impacta directamente», lo que puede orientar la atribución del participante; no corresponde usarla como prueba independiente de causalidad.

## 5. Cruces exploratorios

### 5.1 Estrés y alimentación en respuesta a emociones

**Procedencia:** cruce ya incluido en una diapositiva de conclusiones omitida de la exposición, y en sus notas, en [3]. Recalculado desde [1] el 09/11/2026.

| Puntaje de estrés P6 | P5 en 4–5 | P5 en 1–3 | Total del grupo | % con P5 en 4–5 |
| --- | ---: | ---: | ---: | ---: |
| 4–5 | 8 | 5 | 13 | 61,5 |
| 1–3 | 3 | 12 | 15 | 20,0 |
| Total | 11 | 17 | 28 | 39,3 |

**Interpretación:** dentro de esta muestra, la proporción que declara comer por emociones con puntajes 4–5 es mayor entre quienes marcan estrés 4–5. La diferencia descriptiva es de **41,5 puntos porcentuales**. No se establece dirección temporal, significación estadística ni causalidad.

Existe además proximidad entre las preguntas: P5 menciona explícitamente estrés entre los motivos para comer y P6 pregunta por estrés habitual. Esto hace pertinente el cruce, pero limita su interpretación como evidencia independiente de una relación entre dieta y salud emocional.

### 5.2 Frecuencia de productos y estrés

**Procedencia:** comparación complementaria calculada durante la revisión del 09/11/2026. No estaba presentada como este cruce en [3]; no debe atribuirse al análisis original de la exposición.

| Frecuencia en P4 | P6 en 4–5 | P6 en 1–3 | Total del grupo | % con P6 en 4–5 |
| --- | ---: | ---: | ---: | ---: |
| 3 o más veces por semana | 9 | 6 | 15 | 60,0 |
| Menos de 3 veces por semana | 4 | 9 | 13 | 30,8 |
| Total | 13 | 15 | 28 | 46,4 |

**Interpretación:** el grupo que declara mayor frecuencia del conjunto de productos tiene una mayor proporción de estrés 4–5. La diferencia descriptiva es de **29,2 puntos porcentuales**. Su dirección es compatible con el antecedente sobre snacks y estrés [4], pero no replica su medición ni demuestra que el consumo cause estrés. También podría haber influencia del estrés sobre la conducta alimentaria o factores compartidos no medidos.

## 6. Respuestas abiertas P9

La pregunta abierta es opcional y pregunta por la principal dificultad para mantener una alimentación saludable. Incluye ejemplos de falta de tiempo, oferta en casinos/quioscos y costos. Por ello, las menciones no deben interpretarse como categorías surgidas de una pregunta completamente libre de sugerencias.

El [anexo de codificación](codificacion-respuestas-abiertas.md) registra las 22 respuestas no vacías mediante identificadores de fila, reglas y extractos. Se permiten varias categorías por respuesta.

| Categoría | Recuento en la presentación | Recuento con las reglas explícitas del anexo | % de 22 según el anexo |
| --- | ---: | ---: | ---: |
| Tiempo | 14 | 14 | 63,6 |
| Costo o recursos económicos | 6 | 6 | 27,3 |
| Oferta, disponibilidad o acceso a alimentos | 5 | 4 | 18,2 |

Los recuentos de tiempo y costo se reproducen. Para oferta/acceso se identifican cuatro menciones explícitas. La presentación no contiene una tabla de asignaciones que permita reconstruir con certeza su quinto caso. Una respuesta alude a «la tentación de comprar comidas», pero este registro no la equipara automáticamente con falta de oferta o acceso.

**Decisión confirmada del equipo, 09/11/2026:** adoptar las **cuatro menciones explícitas de oferta/acceso** y documentar la corrección. El resultado vigente es 4/22 (18,2 %), R19/R25/R26/R28; cinco es el antecedente de la presentación, aún sin modificar externamente. Las categorías no son excluyentes, no agotan todos los temas y sus porcentajes no tienen que sumar 100 %.

## 7. Relación con la investigación preliminar

### San Martín y colaboradores, 2024

El estudio con 802 universitarios del sur de Chile [4] ya estaba registrado como **F10** en la [revisión inicial](../revision-inicial.md). Usó DASS-21 y un cuestionario validado de hábitos alimentarios. Reportó asociaciones de snacks con estrés, desayuno con ansiedad y verduras con depresión.

- **Conexión que puede explorarse:** frecuencia de los productos preguntados y estrés, mediante la tabla 5.2. La dirección observada es compatible con el antecedente, con instrumentos y muestras distintos.
- **Aspectos que nuestra encuesta no contrasta:** no pregunta por verduras ni mide ansiedad o depresión con instrumentos específicos. P5 menciona ansiedad entre ejemplos de emociones, pero no mide su nivel. La frecuencia de desayuno por sí sola no comprueba el vínculo con ansiedad del artículo.
- **Límite de comparación:** no se deben comparar los porcentajes del cuestionario propio con prevalencias DASS-21 como si midieran lo mismo. Tampoco se documentó que el formulario del grupo fuera una adaptación validada de ese estudio.

### Sánchez Bizama y colaboradores, 2020

El estudio de estilos de ingesta en universitarios chilenos [5], registrado como **F08**, aporta el concepto de comer emocional. Empleó una versión adaptada del DEBQ, con varias preguntas por subescala. P5 se relaciona con ese concepto, pero es una sola pregunta y no permite comparar puntuaciones ni clasificar estilos como el instrumento del artículo.

### Marco de referencia actual

El [marco de referencia actualizado](../../04-informe/03-marco-de-referencia.md) integra F08, F09, F10 y la evidencia de barreras e intervenciones. Wickham y Francis aportan contexto, pero nuestra encuesta no mide frutas/verduras, síntomas depresivos ni cambios tras una intervención.

F10 y F08 se incorporaron al marco y la discusión por su proximidad conceptual. La [matriz de evidencia](../matriz-brechas-y-evidencia.md) explicita la conexión y sus límites. No se agregan recomendaciones clínicas ni se presume que coincidencia temática confirme esos estudios.

## 8. Correspondencia con la presentación

Las posiciones siguientes corresponden al orden de Google Slides observado el 09/11/2026, no a los números decorativos escritos en las diapositivas.

| Contenido | Situación observada | Resultado de la comprobación |
| --- | --- | --- |
| Muestra, desayuno, alimentación emocional y percepción del ánimo | Diapositivas activas 4–8 | Recuentos correctos; porcentajes redondeados. Mantener las etiquetas y los límites del cuestionario. |
| Barreras de alimentación saludable | Diapositiva activa 9 | Tiempo y costo reproducibles; oferta corregida a cuatro menciones explícitas por decisión del equipo, documentando las cinco históricas. |
| Frecuencia de productos, estrés y fatiga | Diapositivas omitidas 18, 20 y 21 | Recuentos cuantitativos correctos. |
| Cruce entre estrés y comer por emociones | Diapositiva omitida 24 | Reproducible: 8/13 frente a 3/15. Las notas lo identifican como exploratorio, sin prueba estadística. |
| Cruce entre frecuencia de productos y estrés | No presentado como cruce | Cálculo complementario de esta revisión; 9/15 frente a 4/13. |

La exposición activa presenta principalmente distribuciones separadas. El cruce de la sección 5.1 permite explicar de forma más directa una relación entre respuestas, siempre con las limitaciones registradas.

## 9. Síntesis para integrar al informe

En los 28 registros analizados se observan hábitos alimentarios y percepciones heterogéneas. Trece participantes declaran desayunar todos o casi todos los días; quince consumen alguno de los productos agrupados tres o más veces por semana. Dieciséis consideran que la alimentación influye mucho en su ánimo, lo que describe una percepción y no un efecto demostrado.

Los cruces muestran diferencias descriptivas: comer por emociones con puntajes 4–5 aparece en 8 de 13 registros con estrés 4–5, frente a 3 de 15 entre los demás. El estrés 4–5 aparece en 9 de 15 registros con frecuencia de productos de tres o más veces por semana, frente a 4 de 13 en el grupo de menor frecuencia. Estos hallazgos permiten formular preguntas para profundizar la relación entre alimentación y bienestar emocional, sin atribuir causalidad, significación estadística ni representatividad.

Entre las 22 respuestas abiertas, el tiempo es la barrera más mencionada con las reglas documentadas. La clasificación vigente incluye cuatro menciones explícitas de oferta/acceso, confirmadas por el equipo; la presentación histórica conserva cinco hasta su actualización.

## 10. Estado de integración y pendientes

- Confirmados por el equipo: Google Forms, invitación a estudiantes PUCV, ausencia de criterios concretos y adopción de cuatro menciones explícitas de oferta/acceso.
- Integrados: metodología, resultados/discusión, marco, propuesta y conclusiones; las referencias IEEE del informe están unificadas. Este anexo conserva su lista local [1]–[5], separada de la numeración del informe.
- Pendientes metodológicos: canal específico de invitación, número de invitados, apertura/cierre oficial y verificación de afiliación/independencia. Las marcas temporales no sustituyen esos datos.
- Mantener explícitos los cortes exploratorios 4–5/1–3 y sus límites; revisar resultados y conclusiones como equipo.
- Sincronizar las diapositivas con la corrección de oferta cuando se autorice su actualización; no se modificó la presentación externa.

## Referencias

[1] Grupo 7, «Respuestas de la encuesta de hábitos de alimentación y bienestar emocional», archivo [respuestas.csv](respuestas.csv), registros del 30 oct. al 1 nov. de 2026. Consultado: 9 nov. 2026. Copia equivalente en [Excel](respuestas.xlsx), según la comparación documentada en la sección 1.

[2] Grupo 7, «Encuesta: Hábitos de Alimentación y Bienestar Emocional», [cuestionario en PDF](cuestionario.pdf), nueve preguntas. Consultado: 9 nov. 2026.

[3] Grupo 7, «presentacion-avances-grupo-7-mejorada», [Google Slides](https://docs.google.com/presentation/d/1rYNkAdvOsKViEXgj7YNpkpBYTqQ7FZmNchjxMbJNwdI/edit), texto, estado de diapositivas y notas. Consultado: 9 nov. 2026.

[4] R. San Martin et al., «Asociaciones entre conducta alimentaria y síntomas de salud mental en universitarios: un estudio transversal», *Revista Chilena de Nutrición*, vol. 51, no. 6, pp. 459–467, 2024, doi: [10.4067/S0717-75182024000600459](https://doi.org/10.4067/S0717-75182024000600459). [Texto original en SciELO](https://www.scielo.cl/scielo.php?pid=S0717-75182024000600459&script=sci_arttext&tlng=pt). Consulta ampliada de métodos, resultados y discusión: 9 nov. 2026. Ficha F10 en la [revisión inicial](../revision-inicial.md).

[5] J. Sánchez Bizama et al., «Estilos de ingesta de estudiantes universitarios chilenos: ¿qué hay de nuevo?», *Nutrición Hospitalaria*, vol. 37, no. 4, pp. 807–813, 2020, doi: [10.20960/nh.02656](https://doi.org/10.20960/nh.02656). [PDF original](https://scielo.isciii.es/pdf/nh/v37n4/0212-1611-nh-37-4-807.pdf). Consulta inicial del resumen e instrumento, ampliada a métodos, resultados y discusión del PDF durante la consolidación del 9 nov. 2026. Ficha F08 en la [revisión inicial](../revision-inicial.md).
