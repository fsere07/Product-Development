# Pruebas y mejoras del MVP — Clase 8

> Estado al 2026-10-19: tarea, métricas y protocolo definidos **antes de probar**. Todavía no se probó con ninguna persona, así que todo lo que depende de participantes figura como pendiente o "no medido". Las decisiones marcadas como *propuesta* las confirma el equipo.

## 1. Equipo, fecha, usuario, problema y acceso

- **Equipo:** Juan José y equipo (completar integrantes).
- **Fecha:** 2026-10-19
- **Usuario:** estudiante de primer año.
- **Problema:** posterga tareas académicas porque abre redes sociales cuando se sienta a estudiar, y pierde el bloque sin darse cuenta (3 entrevistas: E1, E2, E3 — ver [lean-product-canvas.md](lean-product-canvas.md)).
- **Acceso al MVP (versión inicial, v1):** https://claude.ai/artifact/MJyhJh9PeUUC7Eg1ZdeA4o — pendiente: activar Share para que otros puedan abrirlo. Detalle en [mvp.md](mvp.md).

### Reconstrucción del recorrido

1. **Nuestro usuario tiene el problema de** postergar tareas académicas **cuando** se sienta a estudiar y abre Instagram o TikTok "por un minuto".
2. **La hipótesis más riesgosa era** que los estudiantes activen voluntariamente un "modo estudio" antes de estudiar y lo sostengan.
3. **Para probarla hicimos** un instrumento Wizard of Oz ([modo-estudio-tracker.html](modo-estudio-tracker.html)) y otro de factibilidad ([reglas-clasificacion-tracker.html](reglas-clasificacion-tracker.html)).
4. **Observamos que** las entrevistas muestran el mismo patrón. De los experimentos, 0 sesiones registradas: **pendiente** (ver [aprendizaje-y-mvp.md](aprendizaje-y-mvp.md)).
5. **Por eso decidimos** seguir probando y arrancar un MVP en paralelo.
6. **Nuestro MVP permite** armar un bloque de estudio declarando qué apps evitar, autorreportar si se sostuvo y ver el historial propio, **y todavía necesitamos comprobar** si alguien lo usa por su cuenta en bloques reales.

## 2. Tarea principal

*Propuesta, a confirmar por el equipo.*

- **Consigna para el participante (sin decir dónde tocar):** "Vas a ponerte a estudiar 25 minutos y querés evitar Instagram y TikTok. Usá esta herramienta para armar ese bloque, estudiá y después fijate cómo te fue."
- **Dónde empieza:** el participante abre el link del MVP.
- **Resultado observable (tarea completada):** activó un bloque, lo cerró autorreportando el resultado y después abrió "Tu historial" y ve ese bloque listado.
- **Real / manual / simulado:** el guardado y el historial son reales. El bloqueo de apps es simulado: es un compromiso autoimpuesto, no bloquea nada.
- **Qué cuenta como ayuda del equipo:** cualquier indicación sobre dónde tocar o qué significa algo. Si el equipo ayuda, la persona completa, pero **no** de forma autónoma.
- **Cuándo termina el intento:** éxito (llega a ver su historial con el bloque), abandono (dice que no sigue) o límite acordado de 30 minutos.
- **Aviso sobre el tiempo:** el MVP exige un mínimo de 25 min para que un bloque cuente como sostenido. El equipo decide si la prueba se hace durante un bloque de estudio real o si prefiere agregar un bloque corto de prueba, lo que sería un cambio del MVP y obligaría a identificar la versión.

## 3. Las tres métricas (definidas antes de probar)

*Criterios exploratorios, propuestos.*

| Métrica | Cómo medirla | Fuente | Criterio exploratorio | Qué decisión informa |
|---|---|---|---|---|
| **Éxito de la tarea** | Completan / intentan | Observación manual en el registro | 4 de 5 completan | Si es menos, se mira en qué paso se traban y se prioriza ese paso |
| **Autonomía** | Completan sin ayuda / intentan | Observación manual en el registro | 4 de 5 sin ayuda | Si es menos, se mejoran textos e interacciones del paso con más ayudas |
| **Valor** | Bloques de estudio planificados que se completan en una semana | Base del MVP (sesiones guardadas, campo `sustained`) + dato de cuántos planeaba cada persona | Más del 40% de los bloques planificados, en línea con el criterio del canvas | Si no se alcanza, se revisa el mecanismo antes de agregar funciones |

**Reglas de conteo:** se cuenta el primer intento por persona y versión; los reintentos se registran aparte. Se incluyen abandonos y fallas. Si nadie intentó, se escribe "no medido".

**Valor — limitación conocida:** el MVP solo guarda los bloques que se terminan, no los que alguien planeó y nunca arrancó. Mientras no se sepa cuántos planeaba cada persona, el valor queda **"no medido"**.

**Prueba posterior de valor:** con 3 a 5 estudiantes de primer año (segmento real); en su rutina, sin el equipo presente; durante una semana desde la prueba; contando los bloques que planeaban (preguntándoselo al cierre) contra los que quedaron sostenidos en el historial. Responsable y fecha: *por definir por el equipo*.

## 4. Registro de participantes — versión v1 (inicial)

Compañeros fuera del segmento sirven para detectar dificultades de uso; **no** demuestran demanda ni valor para el usuario real. La IA no cuenta como participante.

| ID | ¿Pertenece al segmento? | Versión | ¿Intentó? | ¿Completó? | ¿Sin ayuda? | Valor y unidad / no medido | Dificultad y ayuda recibida |
|---|---|---|---|---|---|---|---|
| U1 | Pendiente | v1 | Pendiente | Pendiente | Pendiente | no medido | Pendiente |
| U2 | Pendiente | v1 | Pendiente | Pendiente | Pendiente | no medido | Pendiente |
| U3 | Pendiente | v1 | Pendiente | Pendiente | Pendiente | no medido | Pendiente |

*(Agregar U4 y U5 si se consiguen. Si participan menos de 3, anotar cuántos fueron y reconocer la limitación.)*

### Protocolo de la prueba

1. Explicar el contexto y la consigna de la sección 2.
2. Dejar que la persona lo intente sin indicaciones paso a paso.
3. Observar dónde duda, se equivoca o abandona, y anotar cualquier ayuda dada.
4. Al terminar, preguntar qué esperaba y qué le resultó confuso.

Roles (facilita, observa, registra): *por asignar*.

## 5. Dificultad priorizada

**Pendiente.** Se completa después de la primera ronda con datos reales, separando hecho, posible causa y mejora, y priorizando una sola dificultad por cuánto bloquea, cuántas veces aparece y el esfuerzo de corregirla.

## 6. Cambio implementado y verificación técnica

**Pendiente.** Depende de la dificultad priorizada. Se conservará la v1 y se identificará la nueva versión como v2.

## 7. Comparación antes / después

| Métrica | Antes (v1): cantidad y resultado | Después (v2): cantidad y resultado | Qué aprendimos y qué limita la comparación |
|---|---|---|---|
| Éxito | Pendiente | Pendiente | Pendiente |
| Autonomía | Pendiente | Pendiente | Pendiente |
| Valor | no medido | no medido | Pendiente |

## 8. Próxima incertidumbre

- **Incertidumbre:** si un estudiante lo activa por su cuenta en bloques reales, más allá de una prueba guiada.
- **Acción más barata:** pasar el link a 3 a 5 compañeros y pedirles un bloque real de estudio, registrando cada resultado.
- **Responsable y momento:** *por definir por el equipo*.
