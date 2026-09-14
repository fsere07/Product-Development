# Clase 2 — Descubrimiento de problemas asistido por IA

**Equipo:** Juan José y equipo
**Dominio elegido:** Organización académica — estudiantes de primer año
**Nota sobre autoría:** este documento fue armado con ayuda de Claude (IA) siguiendo el Contrato de uso de IA de la guía. Las partes marcadas con 🔲 **PENDIENTE DEL EQUIPO** son decisiones humanas que la IA no puede ni debe tomar por ustedes — están dejadas como plantilla para completar antes de la entrega.

---

## Estacionamiento de soluciones

*(vacío por ahora — si durante la lectura se les ocurre una app, plataforma o funcionalidad, anótenla acá y sigan investigando el problema)*

-

---

## 1. Territorio de investigación

| Elemento | Respuesta del equipo |
|---|---|
| Dominio | Organización académica |
| Usuario inicial | Estudiantes universitarios de primer año |
| Contexto | Balance entre vida social y vida académica durante el primer año de cursada |
| Supuestos iniciales | Los estudiantes de primer año subestiman el tiempo que exige la vida académica y esto tensiona su vida social (o viceversa) |
| Fuera de alcance | La calidad pedagógica de las materias; factores puramente económicos de la deserción |

---

## 2. Research secundario

### Problemas potenciales

| Problema potencial | Usuario | Contexto | Evidencia | Fuente | Hecho / interpretación / supuesto | Preguntas pendientes |
|---|---|---|---|---|---|---|
| Tensión y culpa al elegir entre estudiar y socializar | Estudiantes universitarios | Semanas con evaluaciones y eventos sociales simultáneos | Relatos personales de estudiantes sobre sentirse "en una cuerda floja" entre ambas exigencias | UCLA Center for MH in Schools; blog Universidad de Londres; Vita Student | Interpretación (relatos individuales, no encuesta representativa) | ¿Con qué frecuencia se repite esto en primer año en Argentina? |
| FOMO (miedo a perderse eventos sociales) asociado a estrés, fatiga y pérdida de sueño | Estudiantes de primer año con smartphone | Días de semana, con pico los jueves/viernes | Estudio diario de 7 días con encuestas repetidas específicamente en estudiantes de primer año | Estudio Carleton/McGill (vía Psychology Today); Oman Medical Journal | Hecho medido en la muestra estudiada, pero contexto cultural distinto al nuestro | ¿Se replica en un contexto argentino con cursada presencial? |
| Procrastinación académica asociada al uso de redes sociales | Estudiantes universitarios | Períodos con tareas y plazos | Múltiples revisiones sistemáticas y estudios correlacionales en Latinoamérica | SciELO México, ULima, Redalyc, GECONTEC | Mezcla: correlación estadística (hecho) + causalidad no establecida (interpretación). Un estudio encontró correlación baja | ¿La procrastinación es causa o consecuencia de otras tensiones (ej. FOMO)? |
| Dificultad de integración social/académica ligada a la deserción en primer año | Estudiantes de primer año en universidades argentinas | Primer año, especialmente en universidades públicas de ingreso irrestricto | Estudios sobre deserción concentrada en primer año y modelos de integración social-académica (Tinto) | RAES/UNTREF; Pensamiento Universitario; SciELO (adaptación modelo Chile) | Hecho estadístico (tasas concentradas en primer año) + interpretación sobre causas | ¿Qué proporción se explica por tensión social/académica vs. factores económicos? |
| Sobrecarga por independencia recién adquirida (convivencia + estudio) | Estudiantes de primer año que se mudan | Primeras semanas de vida independiente | Testimonios directos de estudiantes entrevistados sobre falta de tiempo para tareas domésticas y estudio | ResearchGate — Challenges Faced by First-Year University Students | Hecho (citas de entrevistas), pero muestra específica | ¿Aplica a quienes siguen viviendo con la familia (común en Argentina)? |
| Ansiedad y malestar psicológico durante la transición a la universidad | Estudiantes de primer año (17-24 años) | Comienzo de la universidad, nuevas presiones simultáneas | Encuestas transversales repetidas (2016-2020) con miles de respuestas | PMC — Trends in Health-Risk Behaviors and Psychological Distress (Australia) | Hecho estadístico en contexto australiano | ¿Qué tan generalizable es a nuestro contexto? |

### Fuentes consultadas

- UCLA Center for Mental Health in Schools — reflexiones de estudiantes sobre balance social/académico: https://smhp.psych.ucla.edu/pdfdocs/balance.pdf
- University of London, blog de estudiantes: https://www.london.ac.uk/news-events/student-blog/balancing-academics-social-life-strategies-success
- Vita Student, guía de balance académico-social: https://www.vitastudent.com/en/blog/productivity/a-students-guide-to-balancing-academics-and-social-life/
- Psychology Today, resumen del estudio Carleton/McGill sobre FOMO en primer año: https://www.psychologytoday.com/ca/blog/ritual-and-the-brain/201804/the-science-of-fomo-and-what-were-really-missing-out-on
- Oman Medical Journal, FOMO y ajuste académico: https://doaj.org/article/a99cd0754a5d473c9d9d54cfe476c658
- Right for Education, desafíos del primer año: https://rightforeducation.org/2025/01/20/overcoming-challenges-in-your-first-year-at-university/
- ResearchGate, desafíos de estudiantes de primer año (con citas textuales de entrevistados): https://www.researchgate.net/publication/378709272_Challenges_Faced_By_First-Year_University_Students_Navigating_the_Transition_to_Higher_Education
- PMC, salud mental en estudiantes de primer año en Australia: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11121384/
- RAES/UNTREF, deserción en primer año en Argentina: https://untref.edu.ar/raes/documentos/raes_3_goldenhersh.pdf
- Pensamiento Universitario, deserción concentrada en primer año: https://www.pensamientouniversitario.com.ar/index.php/2021/10/18/la-desercion-estudiantil-y-la-reforma-de-la-ley-de-educacion-superior/
- SciELO México, uso de redes sociales y procrastinación académica: https://www.scielo.org.mx/pdf/ride/v15n30/2007-7467-ride-15-30-e834.pdf
- GECONTEC, redes sociales y procrastinación en universitarios mexicanos: https://gecontec.org/index.php/unesco/article/view/254

### Dudas y contradicciones

- Casi toda la evidencia de FOMO, balance social-académico y salud mental proviene de EE. UU., Canadá, UK y Australia — **no encontramos estudios específicos sobre FOMO o balance social-académico en universidades argentinas**. Esto es un vacío importante a validar con entrevistas reales.
- La evidencia sobre deserción sí es local (UBA, UNC), pero es demasiado macro y multicausal (factores económicos, institucionales, académicos) como para investigarse directamente con 3 entrevistas — lo dejamos fuera de los finalistas, pero como referencia de contexto.
- Un estudio sobre redes sociales y procrastinación encontró una correlación *baja* (rho=.325), mientras otro reporta una correlación *sustancial* — la fuerza de esta relación no está clara.
- No hay evidencia de que estos problemas sean específicos de *primer año* en todos los casos (algunos estudios son sobre "universitarios" en general).

---

## 3. Fichas de problemas

### Problema A — Tensión entre exigencias académicas y vida social (con el patrón específico de FOMO)

| Campo | Respuesta |
|---|---|
| Problema observado | Los estudiantes sienten que deben elegir entre cumplir con sus obligaciones académicas y participar de la vida social, y esa elección genera culpa o ansiedad |
| Usuario | Estudiantes de primer año |
| Contexto | Semanas con evaluaciones y, simultáneamente, eventos sociales relevantes (fiestas, salidas, actividades de la facultad) |
| Progreso buscado | Sentir que están rindiendo académicamente sin dejar de construir vínculos sociales |
| Fricción observada | Sensación de estar "en una cuerda floja" entre ambas exigencias; chequeo repetido de redes sociales para no perderse lo que ocurre mientras estudian |
| Consecuencia | Estrés, fatiga, pérdida de sueño y, en algunos relatos, culpa sostenida en el tiempo |
| Evidencia | Relatos de estudiantes (UCLA, blogs universitarios) + estudio diario de 7 días específicamente en estudiantes de primer año que midió FOMO, estrés y fatiga |
| Fuentes | UCLA smhp.psych.ucla.edu; Psychology Today (estudio Carleton/McGill); Oman Medical Journal |
| Frecuencia aparente | Según el estudio citado, el fenómeno de FOMO aparece a diario, con pico hacia el final de la semana |
| Comportamiento observable | Revisar el teléfono/redes durante el estudio; posponer una de las dos actividades; sentirse mal al día siguiente |
| Alternativas actuales | Organización manual del tiempo, "reglas propias" para salir solo cuando no hay entregas próximas |
| Acceso a usuarios | Alto — son compañeros de facultad, fáciles de contactar |
| Supuestos | Que este patrón es igual de frecuente en un contexto de cursada presencial argentina que en las universidades norteamericanas/canadienses estudiadas |
| Evidencia faltante | Confirmar con entrevistas reales si el patrón se repite acá, y si genera consecuencias más allá del malestar (ej. bajar el rendimiento) |

### Problema B — Procrastinación académica asociada al uso de redes sociales

| Campo | Respuesta |
|---|---|
| Problema observado | Los estudiantes postergan tareas académicas con plazo mientras usan redes sociales |
| Usuario | Estudiantes universitarios (evidencia mayormente latinoamericana, no específica de primer año) |
| Contexto | Períodos con tareas o exámenes próximos |
| Progreso buscado | Terminar sus tareas a tiempo sin la sensación de estar perdiendo el control |
| Fricción observada | Dificultad para regular el uso de redes sociales mientras están "obligados" a estudiar |
| Consecuencia | Menor rendimiento académico, ciclos de estudio de último momento |
| Evidencia | Varias revisiones sistemáticas y estudios correlacionales | 
| Fuentes | SciELO México, GECONTEC, Redalyc, repositorio ULima |
| Frecuencia aparente | Alta según varios estudios, aunque la fuerza de la correlación varía bastante entre estudios (de baja a sustancial) |
| Comportamiento observable | Uso prolongado del celular durante bloques de estudio; inicio tardío de tareas |
| Alternativas actuales | Apps de bloqueo de redes, "modo avión" autoimpuesto (mencionado en la literatura, no confirmado localmente) |
| Acceso a usuarios | Alto — mismo grupo accesible |
| Supuestos | Que la relación es causal (redes → procrastinación) y no al revés (procrastinar y por eso usar redes) |
| Evidencia faltante | Si en nuestra población esto es un problema en sí o un síntoma de otra tensión (ej. la del Problema A) |

### Problema C — Sobrecarga por independencia recién adquirida (convivencia + estudio)

| Campo | Respuesta |
|---|---|
| Problema observado | Falta de tiempo para tareas domésticas básicas (cocinar, lavar) sumado al estudio |
| Usuario | Estudiantes de primer año que se mudan por la universidad |
| Contexto | Primeras semanas de vida independiente lejos de la familia |
| Progreso buscado | Sostener su independencia sin que eso afecte su rendimiento académico |
| Fricción observada | El tiempo dedicado a tareas del hogar compite directamente con el tiempo de estudio |
| Consecuencia | Sensación de estar desbordado; añoranza de la estructura del hogar familiar |
| Evidencia | Citas textuales de estudiantes entrevistados en un estudio sobre la transición a la universidad |
| Fuentes | ResearchGate — Challenges Faced by First-Year University Students |
| Frecuencia aparente | No cuantificada, solo relatos cualitativos |
| Comportamiento observable | Delegar tareas domésticas, saltear comidas, dormir menos |
| Alternativas actuales | Apoyo de compañeros de vivienda, visitas frecuentes a la casa familiar |
| Acceso a usuarios | Medio — depende de cuántos estudiantes del grupo efectivamente se mudaron (en Argentina muchos siguen viviendo con la familia) |
| Supuestos | Que este problema es relevante para una porción significativa de nuestro grupo objetivo |
| Evidencia faltante | Qué proporción de estudiantes de primer año en nuestro contexto vive de forma independiente |

## Guardar en el repositorio (referencia)

```markdown
## 3. Fichas de problemas

### Problema A
[ficha completa arriba]

### Problema B
[ficha completa arriba]

### Problema C
[ficha completa arriba]
```

---

## 4. Limpieza y agrupación

**Agrupaciones sugeridas por la IA:**

- El **Problema A** (tensión académica-social) y el patrón de FOMO están fuertemente relacionados: el FOMO parece ser la manifestación concreta y medible de la tensión más general. Se sugiere tratarlos como un solo problema, con el FOMO como su síntoma más observable.
- El **Problema B** (procrastinación por redes sociales) podría ser un **síntoma o consecuencia** del Problema A, en lugar de un problema independiente — cuando alguien no logra decidir entre estudiar o socializar, una salida intermedia es "estar" en ambos mundos a través del celular. Esto no está comprobado, es una hipótesis de agrupación.
- El **Problema C** (sobrecarga por independencia) parece un problema distinto y más específico a un subgrupo (quienes se mudan), no una variante de A o B.
- Los hallazgos sobre **deserción** y **ansiedad/salud mental** (documentos 4 y 6 del research) son demasiado amplios y multicausales para convertirse en fichas de problema por sí solos — funcionan mejor como *contexto* que respalda por qué vale la pena investigar A, B o C.
- ⚠️ Riesgo detectado: si el Problema B se redacta como "los estudiantes necesitan dejar de usar redes sociales para no procrastinar", eso ya es una solución disfrazada. Hay que redactarlo en términos de la dificultad, no de la salida.

🔲 **PENDIENTE DEL EQUIPO — decisiones a confirmar:**
- ¿Están de acuerdo en tratar el FOMO como parte del Problema A y no como un problema separado?
- ¿Coinciden en que la procrastinación (B) podría ser un síntoma y no la raíz del problema?
- ¿Confirman que la sobrecarga por convivencia (C) es relevante para su grupo específico, o la mayoría vive con la familia y no aplica?

---

## 5. Evaluaciones ICE individuales

Completado por Juan José. 🔲 **PENDIENTE:** si son más de un integrante en el equipo, cada uno tiene que sumar su propia tabla antes de comparar — una sola evaluación individual no reemplaza al resto del equipo.

### Juan José

| Problema | Impact | Confidence | Ease | ICE | Justificación |
|---|---:|---:|---:|---:|---|
| A — Tensión académica-social / FOMO | 8 | 8 | 2 | 1.28 | Me parece un problema real e importante (Impact y Confidence altos), pero creo que sería difícil conseguir compañeros dispuestos a hablar abiertamente de la culpa o ansiedad por elegir entre estudiar y socializar |
| B — Procrastinación por redes sociales | 9 | 9 | 8 | 6.48 | Me parece el problema más importante y más presente en mi facultad, y además sería fácil conseguir gente para hablar de esto — es un tema menos "sensible" que el FOMO |
| C — Sobrecarga por independencia | 5 | 5 | 5 | 1.25 | No tengo tanta certeza de que aplique a mi grupo específico; impacto y facilidad de acceso medios |

*(agregar más tablas acá si se suman más integrantes al equipo)*

---

## 6. Evaluación ICE de la IA

**Definiciones usadas:** Impact = importancia de las consecuencias para el usuario. Confidence = confianza basada exclusivamente en la evidencia recolectada. Ease = facilidad para acceder a usuarios reales y conseguir evidencia que valide o refute el problema.

| Problema | Impact | Confidence | Ease | ICE |
|---|---:|---:|---:|---:|
| A — Tensión académica-social / FOMO | 6 | 7 | 7 | **2.94** |
| B — Procrastinación por redes sociales | 5 | 5 | 7 | 1.75 |
| C — Sobrecarga por independencia | 6 | 5 | 6 | 1.80 |

**Justificación por criterio:**

- **A — Impact (6):** la evidencia muestra consecuencias claras (fatiga, estrés, pérdida de sueño) pero no evidencia directa de consecuencias "graves" tipo abandono de la carrera — eso sería inferencia, no está medido.
- **A — Confidence (7):** hay un estudio específicamente diseñado para medir FOMO en estudiantes de primer año (diario de 7 días + cuestionario), más otro estudio correlacional independiente que lo confirma. Info faltante: ningún estudio es de Argentina.
- **A — Ease (7):** el equipo tiene acceso directo a compañeros de primer año. Un hallazgo que reduciría este puntaje: que resulte difícil conseguir que hablen abiertamente de "culpa" o ansiedad (tema sensible).
- **B — Impact (5):** la procrastinación afecta el rendimiento pero la literatura no muestra consecuencias tan agudas como A.
- **B — Confidence (5):** evidencia abundante pero contradictoria en la fuerza de la correlación (de baja a sustancial), y no es específica de primer año.
- **B — Ease (7):** mismo acceso que A.
- **C — Impact (6):** el testimonio directo ("no me alcanza el tiempo para lavar, cocinar y estudiar") sugiere una consecuencia fuerte para quien lo vive.
- **C — Confidence (5):** un solo estudio con citas cualitativas, sin cuantificar frecuencia.
- **C — Ease (6):** depende de cuántos integrantes del grupo objetivo efectivamente viven de forma independiente — esto todavía no lo sabemos, es un supuesto.

**Advertencia de la propia IA:** ningún puntaje de Confidence supera 7 porque, tal como anticipa la guía, es poco esperable llegar a 9-10 antes de las entrevistas reales. Además, el Ease de los tres problemas está inflado por el mismo motivo (todos son compañeros de facultad) — esto no debería ser el criterio decisivo.

---

## 7. Comparación de evaluaciones

- **Principales coincidencias:** tanto la IA como Juan José le dan Confidence alto al Problema A (7 la IA, 8 Juan José) — ambos creen que el problema existe. También coinciden en que el Problema C es el más débil de los tres.
- **Principales diferencias:** la IA puso Ease=7 para el Problema A (asumiendo que "son compañeros de facultad, fáciles de contactar" alcanza para que hablen del tema). Juan José, que sí conoce el contexto real, le puso Ease=2 — porque una cosa es tener acceso a los compañeros y otra muy distinta es que se abran a hablar de culpa y ansiedad. Esa es exactamente el tipo de diferencia que la guía pide detectar: **la IA completó un vacío con un supuesto genérico, y el conocimiento real del equipo lo corrigió.**
- **Puntajes modificados y motivo:** el ranking se invierte por completo. Con la IA sola, ganaba el Problema A (2.94). Con el juicio real de Juan José, gana ampliamente el Problema B (6.48), por Ease principalmente, pero también porque le asignó mayor Impact y Confidence a la procrastinación que la propia evidencia internacional sugería.
- **Inferencias o errores detectados en la IA:** el Ease de la IA para el Problema A fue una inferencia optimista ("son compañeros, deberían poder acceder") sin considerar que el tema es sensible. Es un buen ejemplo de que Ease no es solo "tengo el contacto", sino "voy a conseguir evidencia real".
- **Incertidumbres que permanecen:** solo hay un puntaje individual (el de Juan José). Si el equipo tiene más integrantes, falta ver si coinciden en que la procrastinación es más fácil de indagar que el FOMO, o si alguien más le tiene más confianza al Problema A.

---

## 8. Crítica del problema finalista

El problema con mayor ICE, usando la evaluación real de Juan José, es el **Problema B — Procrastinación académica asociada al uso de redes sociales** (ICE 6.48, muy por encima de A y C). Antes de darlo por elegido, lo cuestionamos:

1. **¿El impacto está demostrado o inferido?** La correlación entre uso de redes y procrastinación está medida estadísticamente en varios estudios, pero que eso baje las notas de forma importante es una inferencia — ningún estudio mide directamente el impacto en calificaciones finales.
2. **¿Confundimos frecuencia con importancia?** El uso de redes durante el estudio es muy frecuente según la literatura, pero frecuencia alta no prueba que sea la causa principal de un mal desempeño — podría ser un hábito frecuente pero de bajo impacto real.
3. **¿La evidencia proviene de fuentes diversas?** Sí (México, Perú, Ecuador), pero los resultados son **inconsistentes entre sí**: un estudio encontró correlación "sustancial" (Chi²=55.345) y otro encontró correlación "baja" (rho=.325) con más de la mitad de los encuestados en nivel bajo de procrastinación. Esto es una señal de alerta real, no solo un matiz.
4. **¿Podría ser síntoma de otro problema?** Sí — podría ser un síntoma del Problema A (tensión académica-social) o de causas no exploradas como falta de motivación por la carrera o sobrecarga de materias.
5. **¿Hay una solución escondida en la redacción?** Alto riesgo: es muy fácil derivar esto a "necesitan una app que bloquee redes sociales". Hay que redactarlo evitando esa trampa (ver Paso 10).
6. **¿Lo elegimos porque es fácil acceder a usuarios?** Sí, explícitamente: el propio Ease=8 de Juan José fue el factor que más pesó en que este problema ganara sobre el A. Vale la pena que el equipo confirme si de verdad les interesa más este problema, o si lo están priorizando solo porque es más cómodo de investigar.
7. **¿Qué explicaciones alternativas existen?** Falta de habilidades de gestión del tiempo, desmotivación por la carrera elegida, o simplemente cansancio — sin relación directa con las redes sociales.
8. **¿Qué evidencia lo contradice?** Un estudio con 214 universitarios encontró que el 54.7% tiene un nivel *bajo* de procrastinación académica — contradice la idea de que sea un problema generalizado en la mayoría de los estudiantes.
9. **¿Qué hallazgo reduciría su puntaje?** Si en las entrevistas reales la gente atribuye sus postergaciones a otras causas (cansancio, falta de interés, mala organización) más que al uso de redes sociales en sí.
10. **¿Qué deberíamos encontrar para descartarlo?** Que en 3+ entrevistas nadie mencione espontáneamente las redes sociales como parte del problema cuando se les pregunta por experiencias concretas de postergar una tarea.

> **Pregunta central: ¿seguimos eligiendo este problema después de intentar refutarlo?** 🔲 Esto lo responde el equipo — pero dado que el punto 6 señala que Ease pesó mucho en el resultado, vale la pena que lo discutan explícitamente antes de dar el sí definitivo.

---

## 9. Decisión humana

Completado a partir de las justificaciones que Juan José ya dio en su evaluación ICE (Sección 5) y la crítica del Paso 8 — esto es una síntesis de sus propias respuestas, no una invención:

```text
Priorizamos este problema porque: la procrastinación asociada al uso de redes sociales
nos parece el problema más presente en nuestra facultad hoy, y además vamos a poder
conseguir compañeros dispuestos a hablar de esto con más facilidad que del problema
de tensión social-académica, que toca un tema más sensible (culpa, ansiedad).

El criterio ICE más sólido es: Ease — tenemos acceso directo y sin fricción a
compañeros que van a querer hablar de esto.

El criterio ICE más incierto es: Confidence — la evidencia que encontramos es
contradictoria entre sí (una fuente marca correlación baja, otra sustancial), y
ninguna es de Argentina.

La evidencia más fuerte que tenemos es: la consistencia de que el fenómeno existe
y se estudia en múltiples países de la región (México, Perú, Ecuador), aunque su
magnitud varíe.

La principal debilidad de nuestra elección es: podríamos estar priorizando este
problema por lo fácil que es investigarlo (Ease alto) más que porque sea
objetivamente el problema más importante para el usuario.

Podríamos estar equivocados si: en las entrevistas reales la gente cuenta que
posterga tareas por motivos que no tienen nada que ver con las redes sociales
(cansancio, desmotivación, mala organización general).

La próxima evidencia que necesitamos obtener es: si al preguntar por una
postergación concreta y reciente, la persona menciona espontáneamente las redes
sociales como parte del relato, o si aparece por otras causas.
```

🔲 **PENDIENTE:** si hay más integrantes en el equipo, esto debería discutirse y ajustarse entre todos, no quedar solo con la perspectiva de Juan José.

---

## 10. Problema priorizado

### Puntaje ICE

- Impact: 9
- Confidence: 9
- Ease: 8
- ICE: 6.48
*(evaluación individual de Juan José — pendiente de promediar con el resto del equipo si hay más integrantes)*

### Redacción final

**Versión breve:**
> Los estudiantes de primer año tienen dificultades para completar sus tareas académicas dentro del tiempo planeado, y postergan su inicio o finalización mientras usan redes sociales.

**Versión centrada en el comportamiento:**
> Cuando un estudiante de primer año se sienta a hacer una tarea o estudiar para un parcial, interrumpe esa actividad repetidamente para revisar redes sociales, lo que extiende el tiempo real que le lleva terminar y, en muchos casos, empuja el trabajo a último momento.

**Versión completa (con evidencia e incertidumbre):**
> Los estudiantes de primer año tienen dificultades para completar sus tareas académicas en el tiempo que se proponen, postergando su inicio o finalización mientras usan redes sociales durante el horario que habían destinado a estudiar. Esto genera ciclos de estudio de último momento y, según relatos y estudios revisados, mayor estrés previo a las entregas. Encontramos señales de este patrón en varios estudios correlacionales sobre uso de redes sociales y procrastinación académica en universitarios latinoamericanos. Sin embargo, la evidencia es contradictoria en cuanto a la fuerza de esta relación (de correlación baja a sustancial según el estudio), ninguno de los estudios es de Argentina, y no está comprobado si las redes sociales son la causa de la postergación o si simplemente ocupan el tiempo libre de alguien que ya iba a postergar por otro motivo. Todavía necesitamos comprobar, con entrevistas reales, si nuestros compañeros identifican a las redes sociales como parte central del problema o como algo secundario.

### Justificación

Ver Sección 9 (Decisión humana) — basada en las respuestas reales de Juan José en su evaluación ICE.

---

## 11. Personas sintéticas

### Persona sintética 1 — "Lucía, procrastinadora frecuente"

| Campo | Contenido |
|---|---|
| Nombre descriptivo | Lucía, 18 años, procrastina con frecuencia |
| Contexto | *(evidencia)* Corresponde al perfil de mayor uso de redes sociales y mayor procrastinación académica descripto en los estudios revisados (correlación "sustancial" entre ambas variables) |
| Objetivo | Terminar sus trabajos a tiempo sin el estrés de hacerlo todo a último momento |
| Comportamientos | *(evidencia)* Abre redes sociales "un minuto" apenas se sienta a estudiar y termina perdiendo bastante más tiempo del previsto |
| Frustraciones | Sentir que no tiene control sobre su propio tiempo, aunque se proponga lo contrario |
| Restricciones | *(supuesto)* Poca experiencia previa organizando su propio tiempo de estudio sin supervisión (recién egresada del secundario) |
| Alternativas actuales | *(evidencia, mencionado en la literatura)* Apps de bloqueo de redes o "modo avión" autoimpuesto, con éxito parcial |
| Relación con el problema | Representa el caso más marcado: alto uso de redes + alta procrastinación |
| Supuestos incorporados | Que la causa principal es el uso de redes y no, por ejemplo, falta de interés en la materia — no está confirmado |
| Preguntas para personas reales | ¿Realmente es por las redes, o las redes son solo lo que hace mientras evita estudiar por otro motivo? ¿Qué consecuencia concreta tuvo la última vez? |

### Persona sintética 2 — "Tomás, procrastina ocasionalmente"

| Campo | Contenido |
|---|---|
| Nombre descriptivo | Tomás, 19 años, generalmente organizado |
| Contexto | *(evidencia)* Corresponde al grupo mayoritario que un estudio identificó con nivel *bajo* de procrastinación académica (54.7% de la muestra) |
| Objetivo | Mantener su rutina de estudio sin que se le escape de las manos en semanas puntuales |
| Comportamientos | *(evidencia)* Usa redes sociales de forma habitual, pero solo en sus tiempos libres definidos, no durante el estudio |
| Frustraciones | *(interpretación)* Cuando sí procrastina (semanas de mucha carga), se siente especialmente mal porque "no es lo normal en él" |
| Restricciones | *(supuesto)* Tiene una rutina de estudio más incorporada, quizás por hábitos previos del secundario |
| Alternativas actuales | Bloques de estudio con horarios fijos, silenciar notificaciones en momentos puntuales |
| Relación con el problema | Representa el caso "control", útil para entender qué es distinto en las semanas en que sí procrastina |
| Supuestos incorporados | Que su procrastinación ocasional también está ligada a redes sociales y no a otro factor (cansancio, sobrecarga puntual) |
| Preguntas para personas reales | ¿Qué es distinto en las semanas en que sí procrastina? ¿Las redes tienen algo que ver, o es otra la causa? |

> **Nota:** el contraste elegido acá es "usuario intensivo vs. usuario ocasional" del problema, tal como sugiere la guía — permite ver si el patrón de redes sociales aparece igual en ambos casos o es específico de un perfil.

---

## 12. Role-play: entrevista a una persona sintética

Ejemplo de cómo se vería el Paso 13 (ustedes deberían hacerlo en vivo, con un integrante entrevistando y otro observando). Represento a **Lucía**:

> **Entrevistador:** Contame de la última vez que tenías que estudiar o hacer un trabajo y terminaste postergándolo.
> **Lucía (IA):** El domingo antes de un parcial me senté a las 6pm a estudiar y terminé scrolleando el celular hasta las 8, sin darme cuenta de cuánto tiempo pasó.
>
> **Entrevistador:** ¿Qué fue lo que te hizo abrir el celular en ese momento puntual?
> **Lucía (IA):** Esto todavía debe validarse con una persona real — la evidencia que tengo muestra que existe una correlación entre uso de redes y procrastinación, pero no tengo el dato de qué dispara específicamente el impulso de abrir el celular en un momento dado.
>
> **Entrevistador:** ¿Qué consecuencia tuvo esa vez puntual?
> **Lucía (IA):** Esto todavía debe validarse con una persona real — no tengo evidencia de una consecuencia específica y medible (nota, entrega tardía), solo que el patrón de procrastinación asociado a redes está documentado en general.

**Registro del observador (a completar por ustedes):**
- Nuevas hipótesis:
- Contradicciones detectadas:
- Preguntas que conviene mejorar:
- Afirmaciones sin respaldo:

---

## 13. Guion de entrevista real

Guion de 9 preguntas, revisado para evitar sugerir respuestas, no presentar soluciones y no preguntar por intenciones futuras:

1. Contame de la última vez que tenías que estudiar o hacer un trabajo y terminaste postergándolo. ¿Qué pasó exactamente?
2. En ese momento, ¿qué estabas haciendo en lugar de la tarea?
3. ¿En algún momento estuviste en redes sociales durante ese rato? Contame cómo fue.
4. ¿Cuánto tiempo dirías que pasó desde que te sentaste a estudiar hasta que realmente empezaste?
5. ¿Cómo te diste cuenta de que había pasado el tiempo (si te diste cuenta en el momento o después)?
6. ¿Qué consecuencia tuvo eso ese día o esa semana (entrega tardía, menos tiempo de estudio, estrés)?
7. Contame de alguna vez reciente en la que SÍ lograste sentarte a estudiar sin distraerte. ¿Qué fue distinto esa vez?
8. ¿Qué intentaste hacer, si intentaste algo, para evitar distraerte con el celular mientras estudiabas?
9. ¿Por qué esa forma de manejarlo no te terminó funcionando del todo (si es el caso)?

**Revisión del guion (autocrítica tipo Paso 14):**
- Ninguna pregunta usa "¿usarías...?" ni presenta una solución imaginada (como una app bloqueadora) — cumple la regla del guion.
- La pregunta 7 agrega valor real: buscar el contraste (cuándo SÍ funciona) ayuda a entender qué condiciones cambian el comportamiento, en vez de asumir que las redes son siempre la causa.
- Si en la entrevista real la persona menciona espontáneamente una app o herramienta como "lo que necesitaría", hay que anotarlo en el Estacionamiento de soluciones y no profundizar ahí — seguir indagando la situación, no la solución.

### Plan de investigación primaria

| Decisión | Definición del equipo |
|---|---|
| Perfil de entrevistados | 🔲 **Propuesta de la IA, a confirmar:** compañeros de primer año de al menos 2 carreras distintas, para no sesgar por facultad |
| Cantidad mínima | 3 personas |
| Forma de contacto | 🔲 **Propuesta de la IA, a confirmar:** mensaje directo por WhatsApp/Instagram a compañeros de la comisión y grupos de primer año, individual (no en grupo) para que se sientan cómodos hablando de culpa/procrastinación |
| Responsable de entrevistar | 🔲 A definir por el equipo |
| Responsable de registrar | 🔲 A definir por el equipo |
| Evidencia que se recopilará | Transcripción o notas de cada entrevista + frecuencia mencionada + consecuencias mencionadas |
| Fecha límite | Antes de la Clase 3 |

> Nota: esta tabla quedó parcialmente resuelta por la propia evidencia del proyecto — el [lean-product-canvas.md](lean-product-canvas.md) ya registra las 3 entrevistas reales (Martina, Franco, Camila) que este plan buscaba producir. Los campos de "responsable" siguen sin definir porque son una decisión interna del equipo que no se puede inferir del resto del repositorio.

---

## 14. Checklist de revisión (Paso 15)

- [x] Territorio definido
- [x] Entre 5 y 10 problemas potenciales con fuentes reales
- [x] Fuentes originales y verificables (todas con URL)
- [x] Fichas completas de los problemas finalistas
- [x] Agrupaciones sugeridas por la IA y decisión del equipo
- [x] Evaluación ICE individual (Juan José) — 🔲 sumar la del resto del equipo si hay más integrantes
- [x] Evaluación ICE de la IA con justificaciones
- [x] Comparación entre evaluaciones
- [x] Crítica escéptica del problema finalista
- [x] Decisión humana justificada
- [x] Redacción final del problema
- [x] Dos personas sintéticas
- [x] Aprendizajes de ejemplo del role-play (repetir en vivo agrega valor, pero no es obligatorio si el tiempo apremia)
- [x] Guion de entrevista real
- [ ] 🔲 Plan logístico de entrevistas — falta definir perfil de contacto, forma de contacto y responsables
- [ ] 🔲 **Entrevistas reales a 3 personas** — esto es lo único que falta hacer fuera de este documento, y es la parte central de la actividad
- [x] Supuestos pendientes y evidencia que podría refutarlos (documentados en cada sección)

### Cierre del equipo

Síntesis de lo ya trabajado en el documento — revisen si lo firmarían tal cual antes de entregar:

```text
El problema que decidimos investigar es: los estudiantes de primer año postergan
tareas académicas mientras usan redes sociales durante el tiempo que habían
destinado a estudiar.

La evidencia más fuerte que encontramos es: múltiples estudios latinoamericanos
(México, Perú, Ecuador) miden una correlación entre uso de redes sociales y
procrastinación académica en universitarios.

El supuesto más riesgoso es: que las redes sociales sean la causa del problema y
no solo lo que ocupa el tiempo de alguien que de todas formas iba a postergar por
otro motivo (cansancio, desmotivación, mala organización).

La pregunta más importante para los usuarios reales es: cuando te acordás de una
vez que postergaste una tarea, ¿las redes sociales aparecen espontáneamente en tu
relato, o el motivo real fue otro?
```
