# Lean Product Canvas — Procrastinación académica y redes sociales (1er año)

> Este canvas contiene hipótesis. La evidencia surgirá de observar y experimentar.

## 1. Problema de negocio

Los estudiantes de primer año procrastinan tareas académicas por uso de redes sociales (evidenciado en 3 entrevistas: 1.5 a 2+ horas diarias, estudio nocturno, culpa recurrente), lo que **(Supuesto)** podría traducirse para la universidad en menor rendimiento académico y mayor riesgo de abandono en el primer año. Todavía necesitamos comprobar si la universidad ya mide o le preocupa esta relación.

**Evidencia:** entrevistas a Martina (19, Psicología 2°año), Franco (20, Ingeniería 1°año) y Camila (18, Comunicación 1°año).

**Supuesto pendiente de validar:** vínculo real entre esta procrastinación y métricas institucionales (notas, deserción).

## 2. Resultados de negocio

Aumentar el tiempo promedio de estudio sin interrupciones por redes sociales, desde pendiente de medir (estimado ~20-30 min según entrevistas) hasta 45-50 min continuos, en 8 semanas.

## 3. Usuarios y clientes

| Rol | Respuesta | Estado |
|---|---|---|
| Usuario | Estudiantes de primer año (perfil similar a Martina, Franco y Camila) | Evidencia (entrevistas) |
| Cliente | La universidad | Definido por el equipo |
| Decisor | Área de bienestar estudiantil / secretaría académica de la universidad | Supuesto — no validado |
| Influenciador | Docentes de materias con alta tasa de procrastinación y/o centro de estudiantes | Supuesto |

## 4. Necesidades y resultados del usuario

Cuando estoy estudiando un tema difícil o aburrido, quiero resistir el impulso de revisar el celular sin perder la posibilidad de usarlo para cosas de la facultad (WhatsApp de la comisión, campus virtual), para poder terminar una sesión de estudio sin culpa ni ansiedad después.

*Evidencia: los 3 entrevistados describen el mismo patrón (escape ante dificultad, mezcla de uso académico/ocio, culpa posterior).*

## 5. Ideas de solución

Alternativas consideradas:
1. Información/decisión — Panel de fricción (dashboard de tiempo perdido por app).
2. Automatización/inteligencia — Modo estudio inteligente (seleccionada).
3. Coordinación/transacción — Sesiones acompañadas (body-doubling virtual).

### Modo estudio inteligente

- Propuesta: asistente que detecta cuándo el estudiante entra a apps de ocio (Instagram/TikTok) durante un bloque de estudio declarado, y bloquea solo el scroll de ocio, no el uso académico (WhatsApp, campus virtual).
- Valor para el usuario: menos interrupciones sin perder acceso a lo académico.
- Tecnología central: clasificación de contenido/apps en tiempo real (inicialmente por reglas simples, no IA compleja).
- Datos necesarios: qué apps/contenidos son "ocio" vs "académico" para cada usuario.
- Riesgo principal: clasificación mal calibrada puede generar la misma ansiedad que llevó a Martina a desinstalar su app de bloqueo.
- Prototipo inicial: Wizard of Oz — el estudiante define manualmente qué apps bloquear por bloque, sin IA real todavía.
- Dependencias: ninguna física; depende de permisos de accesibilidad del sistema operativo para bloquear apps (a validar en Caja 8/factibilidad).
- Estado: idea no validada.

## 6. Hipótesis principales

### Hipótesis de problema
Creemos que los estudiantes de primer año procrastinan por mezclar apps académicas y de ocio.
Lo sabremos si más del 60% de una encuesta a estudiantes de primer año reporta el mismo patrón.

### Hipótesis de valor
Creemos que un modo de estudio que distinga ocio de uso académico dentro de la misma app ayudará a aumentar el tiempo de estudio ininterrumpido.
Lo sabremos si los usuarios de prueba reportan sesiones más largas sin interrupción.

### Hipótesis de comportamiento
Creemos que los estudiantes activarán voluntariamente este modo antes de estudiar.
Lo sabremos si más del 40% de una lista de espera prueba la función al menos 3 veces en dos semanas.

### Hipótesis de factibilidad
Creemos que podemos distinguir uso "de ocio" vs "académico" dentro de la misma app con reglas simples definidas por el usuario, sin IA compleja.
Lo sabremos si un prototipo Wizard of Oz funciona sin fricción para al menos 5 usuarios de prueba.

## 7. Lo más importante por aprender

¿Los estudiantes realmente van a activar y sostener el uso de un "modo estudio" de forma voluntaria, o va a pasar lo mismo que con la app que instaló y desinstaló Martina?

*Se priorizó la hipótesis de comportamiento: mayor incertidumbre (ya hay evidencia de que soluciones similares fracasaron) y mayor impacto (si nadie la usa, no importa cuán bien funcione la tecnología).*

## 8. Experimento mínimo

- Hipótesis que prueba: comportamiento
- Objetivo: ver si estudiantes activan y sostienen un "modo estudio" simple
- Tipo de experimento: prueba de activación con prototipo Wizard of Oz
- Herramienta: Google Form (para configurar apps a bloquear) + recordatorio manual por WhatsApp
- Participantes: 8-10 estudiantes de primer año
- Duración: 2 semanas
- Tarea: activar el "modo estudio" antes de cada sesión y reportar si lo sostuvieron
- Datos necesarios: registro de activaciones + auto-reporte de cumplimiento
- Métrica: % de sesiones de estudio declaradas donde efectivamente activaron el modo
- Criterio de éxito: más del 40% de sesiones con activación sostenida
- Criterio de fracaso: menos del 20%, o abandono total antes de la semana 2
- Aprendizaje esperado: si el problema real es de motivación/activación más que de tecnología
- Limitaciones: no mide impacto real en notas ni en la universidad; muestra chica y auto-reportada
