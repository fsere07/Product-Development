# Nuestro primer MVP

- **Usuario y situación:** estudiante de primer año que, al sentarse a estudiar, abre una app "por un minuto" y termina perdiendo el bloque completo sin darse cuenta de cuánto tiempo pasó.
- **Valor y acción central:** declarar qué apps va a evitar durante un bloque de estudio, correr ese bloque, autoreportar si lo sostuvo, y ver su propio historial para tomar conciencia de su patrón real (no solo en el momento de una prueba puntual).
- **Acceso o forma de ejecución:** https://claude.ai/artifact/MJyhJh9PeUUC7Eg1ZdeA4o — está publicado como privado; hay que compartirlo (Share → "Anyone with the link") antes de mandárselo a alguien fuera del equipo.
- **Recorrido:** entra → escribe su nombre/apodo y elige qué apps va a evitar + duración del bloque → corre el timer → al terminar se autoreporta ("sostuve el bloque" / "me distraje") → en la pestaña "Tu historial" ve su racha actual, % de bloques sostenidos y el detalle de cada sesión.

## Funciona / manual o simulado / fuera de alcance

| Categoría | Detalle |
|---|---|
| Funciona de verdad | Guardado de cada sesión en base de datos compartida real (capability `db` de Artifacts); cálculo de racha y % sostenido a partir de esas sesiones; historial filtrado por apodo (guardado en el dispositivo con `localStorage`) |
| Manual / simulado | El "bloqueo" de apps no es real — es un compromiso que la persona se autoimpone y autoreporta. No hay clasificación de contenido ni verificación técnica de que efectivamente evitó las apps declaradas |
| Fuera de alcance | Bloqueo real a nivel sistema operativo, notificaciones push, cuentas de usuario (el "apodo" no es una autenticación, dos personas podrían usar el mismo), integración con Instagram/TikTok reales |

Este MVP reutiliza la mecánica del instrumento de Clase 4 ([registro-experimento.md](registro-experimento.md)), pero le agrega la pestaña de historial personal — ese es el único valor nuevo respecto al instrumento de experimento, a propósito, para no salirse de la acción central acordada en [aprendizaje-y-mvp.md](aprendizaje-y-mvp.md).

- **Evidencia disponible y duda pendiente:** ninguna todavía — el MVP recién se construyó y publicó, nadie lo probó de punta a punta todavía. La duda sigue siendo la misma que el experimento de comportamiento: si alguien lo va a activar y sostener por su cuenta, más allá de la prueba inicial.
- **Qué medimos:** personas que completan el recorrido (activar → correr el bloque → autoreportar) y cuántas vuelven a abrir su historial en una sesión posterior — esa vuelta es la señal de que el historial les aporta algo, no solo el timer.

## Prueba e iteración

- **Quién probó (rol) y tarea:** _PENDIENTE — todavía no se hizo la prueba con otra persona._
- **Qué ocurrió y cómo lo sabemos:** _PENDIENTE_
- **Devolución concreta que dimos a la IA:** _PENDIENTE_
- **Cambio realizado y resultado de la nueva prueba:** _PENDIENTE_
- **Próximo ajuste:** _PENDIENTE — se define después de la primera prueba real._

> Como en `registro-experimento.md` y `registro-experimento-clase5.md`, estas secciones quedan sin completar a propósito: requieren que una persona real use el MVP y le dé al equipo una devolución concreta (qué hizo, qué esperaba, qué pasó, qué evidencia hay), tal como pide la guía de Clase 7. Inventar esa devolución sería fabricar evidencia sobre algo que todavía no ocurrió.
