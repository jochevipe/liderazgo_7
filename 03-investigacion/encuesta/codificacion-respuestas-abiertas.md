# Codificación de las respuestas abiertas sobre alimentación saludable

**Fecha:** 9 de noviembre de 2026.

**Estado actualizado:** el equipo confirmó el 09/11/2026 adoptar las **cuatro menciones explícitas de oferta/acceso y documentar la corrección**. Se mantienen las reglas y asignaciones trazables de este anexo: T=14, C=6 y O=4. La confirmación no acredita revisión independiente por varios codificadores ni cálculo de concordancia.

Este anexo respalda la sección 6 del [análisis y resultados](analisis-y-resultados.md). Su fuente es P9 de [respuestas.csv](respuestas.csv), no las imágenes o una selección de respuestas de la presentación. Hay 22 respuestas no vacías y 6 vacías.

## 1. Pregunta y contexto

El [cuestionario](cuestionario.pdf), página 4, pregunta: «¿Cuál es la principal dificultad que encuentras en la vida universitaria para mantener una alimentación saludable?». Es opcional e incluye ejemplos de falta de tiempo, oferta en casinos/quioscos y costos.

Los ejemplos pueden orientar las respuestas. Los recuentos describen menciones dentro de estas respuestas, no la prevalencia de barreras en toda la población ni prioridades surgidas sin sugerencias del formulario.

## 2. Reglas de clasificación

| Código | Categoría | Regla de inclusión | Exclusiones y cautelas |
| --- | --- | --- | --- |
| T | Tiempo | Mención explícita de tiempo o tiempos disponibles. | Organización o dificultad para cocinar no se convierten por sí solas en tiempo si la respuesta no lo menciona. |
| C | Costo o recursos económicos | Mención explícita de precio, costos o falta de dinero. | No se atribuyen problemas económicos a otras respuestas. |
| O | Oferta, disponibilidad o acceso | Mención explícita de oferta en casinos, oferta universitaria no saludable o falta de alimentos al alcance. | La tentación de comprar comida no implica por sí sola falta de oferta o acceso. |

- Una respuesta puede recibir más de un código; se cuenta como máximo una vez en cada categoría.
- Se conservan otras menciones en una columna de observaciones sin convertirlas en categorías cerradas. Esta codificación no pretende agotar todos los temas de las respuestas.
- `R01` corresponde al primer registro de datos, fila 2 del CSV; en general, la fila del CSV es el número de respuesta más uno. Estos identificadores permiten ubicar el registro y no identifican personas.
- Los extractos se muestran con espacios y saltos de línea simplificados. Los originales completos se conservan en el CSV.

## 3. Asignaciones por registro

| Registro | Fila CSV | Respuesta o extracto | Códigos | Otras menciones o cautelas |
| --- | ---: | --- | --- | --- |
| R02 | 3 | «una mezcla entre el precio de los alimentos y la motivación para hacerlo» | C | La respuesta completa también menciona comer ante ansiedad o estrés. |
| R03 | 4 | «falta de tiempo y dificultad para cocinar» | T | Habilidad o dificultad práctica para cocinar. |
| R04 | 5 | «Falta de dinero» | C | — |
| R05 | 6 | «Falta de tiempo y organización respecto a mis comidas.» | T | Organización de comidas. |
| R07 | 8 | «Los tiempos, muchas veces no se pueden coordinar ambas cosas a la vez, por lo que uno recurre a los más rápido.» | T | Coordinación y recurso a alternativas rápidas. |
| R08 | 9 | «Tiempo/ánimo» | T | Ánimo. |
| R09 | 10 | «costos y falta de tiempo» | C, T | — |
| R10 | 11 | «Los precios» | C | — |
| R11 | 12 | «Tiempo y costos» | T, C | — |
| R12 | 13 | «costos» | C | — |
| R13 | 14 | «Falta de tiempo» | T | — |
| R14 | 15 | «Tiempo» | T | — |
| R15 | 16 | «La tentación de comprar comidas» | Sin T, C u O | Tentación; no se infiere falta de oferta o acceso. |
| R18 | 19 | «falta de tiempo» | T | — |
| R19 | 20 | «oferta en casinos» | O | — |
| R20 | 21 | «tiempo» | T | — |
| R22 | 23 | «falta de tiempo» | T | — |
| R23 | 24 | «Falta de tiempo» | T | — |
| R24 | 25 | «Falta de tiempo» | T | — |
| R25 | 26 | «Ofertas no saludables en la universidad como snacks o comidas completas.» | O | — |
| R26 | 27 | «Yo diría la falta de alimentos a mi alcance y mi poca voluntad propia.» | O | Voluntad propia. |
| R28 | 29 | «Oferta en casinos y falta de tiempo» | O, T | — |

Los registros sin respuesta a P9 son **R01, R06, R16, R17, R21 y R27**. No se imputan motivos ni se incluyen en el denominador 22.

## 4. Recuentos y diferencia respecto de la presentación

| Categoría | Registros asignados | n | % de las 22 respuestas |
| --- | --- | ---: | ---: |
| Tiempo | R03, R05, R07, R08, R09, R11, R13, R14, R18, R20, R22, R23, R24, R28 | 14 | 63,6 |
| Costo | R02, R04, R09, R10, R11, R12 | 6 | 27,3 |
| Oferta o acceso | R19, R25, R26, R28 | 4 | 18,2 |

La presentación informa **14, 6 y 5** menciones, respectivamente, y señala que muestra 18 de las 22 respuestas. El análisis de este anexo usa las 22 originales. Los dos primeros recuentos se reproducen; el tercero fue corregido a **cuatro** por decisión del equipo el 09/11/2026.

No se encontró una asignación documentada que identifique el quinto caso de oferta. R15 podría explicar una diferencia si se hubiera utilizado una categoría más amplia de entorno o estímulos de compra, pero esa explicación es una hipótesis de revisión, no una reconstrucción confirmada del criterio original.

**Decisión confirmada del equipo, 09/11/2026:** «Usar las 4 menciones explícitas y documentar la corrección». El resultado adoptado es **O=4 (18,2 % de 22)**, en R19, R25, R26 y R28; R15 no se incorpora a O. El valor cinco se conserva arriba como antecedente de la presentación, no como resultado vigente. La presentación externa no se modifica en este encargo y deberá sincronizarse cuando el equipo actualice sus diapositivas.
