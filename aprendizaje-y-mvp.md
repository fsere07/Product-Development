# Aprendizaje y MVP — Clase 6

## Lo que entiendo de su experimento

Tienen dos experimentos diseñados a partir del [lean-product-canvas.md](lean-product-canvas.md) ("Procrastinación académica y redes sociales — 1er año"):

1. **Modo estudio** (Clase 4, hipótesis de comportamiento) — diseño en el propio canvas, registro en [registro-experimento.md](registro-experimento.md).
2. **Reglas de clasificación** (Clase 5, hipótesis de factibilidad) — diseño en [diseno-experimento.md](diseno-experimento.md), registro en [registro-experimento-clase5.md](registro-experimento-clase5.md).

- **Querían comprobar:**
  - Modo estudio: si los estudiantes activan y sostienen voluntariamente un "modo estudio" Wizard of Oz durante 2 semanas, o si pasa lo mismo que con la app que Martina instaló y desinstaló.
  - Reglas de clasificación: si un estudiante puede definir sus propias reglas de "ocio vs. académico" y aplicarlas de forma consistente ante contenido ambiguo, sin IA clasificando.
- **El criterio era:**
  - Modo estudio: más del 40% de sesiones con activación sostenida (fracaso: menos del 20%, o abandono total antes de la semana 2).
  - Reglas de clasificación: configurar en menos de 5 min y clasificar correctamente al menos 4 de 6 escenarios.
- **Construyeron:** los dos instrumentos funcionales, ahora publicados con almacenamiento compartido real:
  - Modo estudio: https://claude.ai/artifact/1nVzFAtkuLUiHGcThD1ecW
  - Reglas de clasificación: https://claude.ai/artifact/BgiCS7w4zdCwdKsu2UNAfH
- **El resultado registrado:** ninguno todavía. Los dos archivos de registro siguen con las secciones de ejecución, evidencia y aprendizajes marcadas `_PENDIENTE_` — no hay sesiones reales cargadas en ninguno de los dos instrumentos.

## Chequeo rápido

- Hipótesis definida antes de probar: **Sí** (las dos)
- Criterio definido antes de probar: **Sí** (las dos)
- Hay resultados u observaciones: **No**
- Estado de la iteración: **falta completar la prueba** — el diseño y el instrumento están listos; falta la ejecución con participantes reales. El plan de reclutamiento ya está armado en [reclutamiento.md](reclutamiento.md), incluyendo el piloto interno que debe correrse antes de invitar a los 5 participantes de reglas de clasificación.

---

## 2. Resultado

| Qué pasó | Cómo lo sabemos |
|---|---|
| — | Todavía no hay sesiones registradas en ninguno de los dos instrumentos |

- Resultado frente al criterio: **todavía no sabemos**
- Algo que salió distinto de lo esperado: no aplica todavía — no hubo ejecución

## 3. Aprendizaje

- **Aprendimos que:** todavía no reunimos suficiente evidencia para responder ninguna de las dos preguntas de aprendizaje. Lo que sí avanzó en esta etapa fue el diseño y la construcción de los instrumentos, no su ejecución con gente real.
- **Todavía no sabemos si:** los estudiantes van a activar y sostener el "modo estudio" de forma voluntaria, ni si las reglas simples que cada uno define alcanzan para clasificar contenido ambiguo sin ayuda.

## 4. Decisión

- **Elegimos:** Seguir probando.
- **Porque:** la prueba todavía no llegó a la cantidad de participantes ni al tiempo acordado (0 de 8-10 en modo estudio; 0 de 5 + piloto en reglas de clasificación). No es un problema del diseño ni de la prueba — es que todavía no se ejecutó con gente real.
- **Próximo paso:** correr el reclutamiento ya redactado en [reclutamiento.md](reclutamiento.md) — mandar los dos links a los participantes, empezando por el piloto interno de reglas de clasificación — y volver a esta clase cuando haya datos reales para analizar.

## 5. Punto de partida del MVP

- **Usuario:** estudiante de primer año que procrastina tareas académicas usando redes sociales durante bloques que había destinado a estudiar.
- **Situación:** se sienta a estudiar, abre una app "por un minuto" y pierde el bloque completo sin darse cuenta de cuánto tiempo pasó.
- **Valor que queremos entregar:** que la persona tome conciencia de su propio patrón de sostenimiento (o no) de los bloques de estudio que se propone, sin depender de bloqueo real de apps.
- **Una sola cosa que el MVP debe permitir hacer:** declarar qué va a evitar en un bloque de estudio, correr el bloque, autoreportar si lo sostuvo, y ver su propio historial de cumplimiento.
- **Qué vamos a medir cuando lo use una persona:** si activa el modo estudio antes de un bloque real (no solo como prueba puntual) y si vuelve a abrir su historial después.

> Nota: este punto de partida retoma la idea ya diseñada como "Modo estudio inteligente" en el canvas (Sección 5) — es la propuesta para empezar a construir en la Clase 7 en paralelo a seguir corriendo el experimento de comportamiento, no una confirmación de que la solución funciona. Ver [mvp.md](mvp.md) para la primera versión construida.
