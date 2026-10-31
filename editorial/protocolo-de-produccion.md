# Protocolo editorial de producción — Temporada 1

## Principios
La finalidad es producir una temporada completa, coherente, disfrutable en audio y verificable contra las fuentes de verdad. **El creador no leerá los textos narrativos hasta terminar la temporada.** Un PR mergeado representa incorporación del **borrador**, no aprobación literaria final ni cambio automático de canon.

## Antes de escribir un episodio
1. Verificar `main`, PR abiertos y siguiente número disponible. Nunca duplicar una rama o episodio pendiente.
2. Leer completo el mapa de 30 episodios, el segmento relevante de sinopsis y las reglas de Biblia 1.0.
3. Leer al menos dos episodios previos completos y sus controles editoriales; ampliar a episodios anteriores donde haya pistas, promesas, causalidad o continuidad de personajes.
4. Revisar los registros editoriales y el documento de continuidad. Si hay lagunas, registrarlas como **pendientes**, sin inventar retrospectivamente.
5. Preparar una **microescaleta de trabajo** interna: escena, focalizador, objetivo, oposición, decisión, consecuencia, evidencia y efecto sobre tramas. No es obligatorio versionar cada microescaleta.

## Durante la redacción
- Prosa narrativa original en español, tercera persona limitada, estructura coral ya aprobada.
- Un focalizador por escena; cambio de POV solo tras corte visible.
- Cada episodio debe cambiar una situación y terminar con un gancho causal justificado, no solo una amenaza vaga.
- Equilibrar investigación documental con escenas físicas, vida cotidiana, conflictos políticos, ingeniería y relaciones humanas.
- No explicar al lector lo que todavía no puede saber; no hacer que el narrador mienta sobre lo que un personaje focalizador sí sabe.
- Cada elemento de magia o tecnología debe admitir preguntas de energía, soporte, límites, costo, operadores y jurisdicción.
- No resolver mediante coincidencias repetidas, «magia nueva», viajes temporales ni destrucción o restauración arbitraria de memoria.

## Verificación previa al PR
- **Causalidad:** ¿cada giro depende de algo sembrado?
- **Cronología:** ¿horas, traslados, distancias, antecedentes y secuencias son compatibles?
- **Conocimiento:** ¿cada persona sabe solo lo que pudo aprender?
- **Documentos:** ¿origen, custodia, autoridad, falsificación posible y valor probatorio?
- **Reglas:** ¿conservación del Pulso, materiales y límites de Tránsito?
- **Jurisdicción:** ¿quién puede autorizar, detener, registrar, requisar y publicar?
- **Audio:** ¿lugares, cambios de voz y pistas comprensibles sin apoyo visual?
- **Personajes:** ¿metas, contradicciones, costo de decisión, evolución de relaciones?
- **Revelaciones:** ¿se respeta el momento previsto en el mapa?
- **Longitud:** contar palabras de forma explícita; estimar duración solo como aproximación.

## Archivos que entrega cada episodio
- `temporadas/temporada-01/episodios/NN-titulo-normalizado.md`: texto completo, POV y estado de borrador.
- `temporadas/temporada-01/episodios/NN-control-editorial.md`: función dramática, verificación, pista y soporte, criterios de audio, problemas pendientes.
- Actualizaciones puntuales a los registros de `editorial/` **solo si aparece un hecho nuevo o cambia el estado de un hilo**. Evitar duplicar la sinopsis integral.
- Un PR contra `main` con resumen estrictamente **sin spoilers** y advertencia de que el diff contiene narrativa.

## Registro de cambios
Las alteraciones a decisiones **APROBADAS** se escalan al creador. Decisiones menores delegadas se registran como «decisión editorial de guion — revisable», nunca como «aprobación explícita». Documentar qué episodios deben revisarse. No sobrescribir silenciosamente episodios ya integrados.

## Final de temporada: fases separadas
1. **Escritura** de 30 primeros borradores.
2. **Auditoría global** de causalidad, cronología, arcos, economía narrativa, revelaciones, consistencia de vocabulario y puntos de vista.
3. **Edición literaria y sonora**: ritmo, redundancias, lectura en voz alta cronometrada, diferenciación de voces, efectos de sonido sugeridos y consistencia de duración.
4. **Entrega al creador** de una versión de lectura integral por primera vez; solo entonces compartir resumen de trama, sinopsis y texto.
5. **Producción sonora/publicación**: etapa separada, sin asumir que se contrató ni publicó en Pocket FM.

## Criterio de «temporada finalizada»
No declarar la temporada finalizada solo porque existen 30 archivos. Requiere revisión integral, pendientes críticos resueltos, consistencia comprobada y versión de lectura preparada.