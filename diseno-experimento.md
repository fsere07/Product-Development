# Diseño del experimento — Clase 5

## Evidencia de partida
- 3 entrevistas (Martina, Franco, Camila) confirman el patrón de mezclar apps de ocio y académicas en la misma sesión de estudio.
- Riesgo identificado: Martina ya instaló y desinstaló una app de bloqueo — señal de que una solución con fricción puede ser abandonada.
- El instrumento de Clase 4 (hipótesis de comportamiento) está construido pero su piloto de 2 semanas todavía no se ejecutó con participantes reales — no aporta evidencia nueva a esta clase.
- Hipótesis de problema, valor y factibilidad seguían sin ningún experimento corrido.

## Pregunta de aprendizaje elegida
¿Un estudiante puede configurar por su cuenta reglas simples de "ocio vs. académico" y aplicarlas de forma consistente ante contenido ambiguo, sin ayuda y sin IA clasificando?

*(Decisión humana: se priorizó la hipótesis de factibilidad porque no depende del piloto de 2 semanas de comportamiento y puede resolverse en una sola sesión corta.)*

## Experimento elegido
Sesión combinada de configuración + clasificación:
1. El participante escribe, en sus propias palabras, qué considera "ocio" y qué considera "académico".
2. Aplica esas reglas para clasificar 6 situaciones ambiguas de uso real de apps (Instagram, WhatsApp, TikTok, campus virtual), diseñadas por el equipo con una clasificación esperada conocida.

*(Decisión humana: se descartó la entrevista moderada 1:1 por costo/tiempo en esta clase; se combinó el formulario de configuración con la clasificación de escenarios para cubrir ambas preguntas — fricción de armar las reglas y si esas reglas alcanzan ante ambigüedad real — en una sola sesión de ~20 min.)*

## Partes reales y simuladas
- **Real:** las reglas que cada participante define son propias, no sugeridas. La clasificación que hace es su decisión real.
- **Simulado:** los 6 escenarios son textos redactados por el equipo (no hay contenido real extraído de las apps de cada participante).

## Alcance mínimo
| Categoría | Contenido |
|---|---|
| Imprescindible | Formulario de reglas, 6 escenarios con cronómetro, registro de clasificación/tiempos/abandono |
| Simulable | Los 6 escenarios (texto fijo, no contenido real de apps) |
| Fuera de alcance | Bloqueo real de apps, integración con Instagram/TikTok reales, clasificación por IA |

## Contrato experimental

| Campo | Definición |
|---|---|
| Hipótesis | Un estudiante puede definir reglas simples y aplicarlas de forma consistente ante contenido ambiguo, sin IA. |
| Aprendizaje | Si la fricción de configurar + la ambigüedad real rompen el supuesto de que "reglas simples alcanzan". |
| Participantes | 5 estudiantes de primer año, perfil similar a Martina/Franco/Camila. |
| Acción/resultado | Tiempo y abandonos al configurar reglas; clasificación de 6 escenarios ambiguos con esas reglas. |
| Métrica | Tiempo de configuración + % de escenarios clasificados según la clasificación esperada por el diseño del escenario. |
| Criterio de éxito | Configura sin abandonar en menos de 5 min, y clasifica correctamente al menos 4 de 6. |
| Criterio de fracaso | Abandona, tarda más de 10 min, o clasifica correctamente 2 o menos de 6. |
| Duración | Sesión única de ~20 min por participante, completable en 1-2 días. |
| Limitación | No mide sostenimiento en el tiempo (eso es la hipótesis de comportamiento). No mide generalización a apps o contenidos fuera de los 6 escenarios probados. |

## Instrumento funcional
`reglas-clasificacion-tracker.html` — web app que guía la configuración de reglas y la clasificación de los 6 escenarios, y guarda cada sesión en almacenamiento compartido para ver los resultados agregados en la pestaña "Resultados".
