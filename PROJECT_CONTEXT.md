# Contexto operativo persistente — Los Ecos del Umbral

> Documento de **transferencia entre sesiones**. No reemplaza la Biblia narrativa ni el registro de decisiones. **Sin spoilers en los mensajes dirigidos al creador.**

## Identidad y objetivo
- **Obra:** *Los Ecos del Umbral*, ficción original en prosa orientada a adaptación sonora episódica (Pocket FM es referencia de formato, sin contrato de distribución).
- **Género:** fantasía multiversal, misterio, intriga y conspiración.
- **Universo:** completamente propio, no adaptación licenciada de Magic: The Gathering.
- **Temporada 1:** 30 episodios planificados. El creador **no quiere leer ninguno hasta terminar y revisar los 30**.
- **Responsabilidad creativa:** delegada al agente para decisiones y desarrollo coherentes. El creador conserva revisión final de la temporada.
- **Entrega:** ramas y PR a `main` en `jonasmz/theThreshold`; el agente no hace merge por cuenta propia.

## Fotografía de estado (verificada al preparar este documento)
| Entregable | Estado constatado |
|---|---|
| Biblias 0.2–0.6 y consolidación candidata 1.0 | Integradas en `main` |
| Sinopsis integral y mapa de temporada 01 (30 episodios) | Integrados en `main` |
| Episodios 01–09 y controles editoriales | Integrados en `main` |
| Episodio 10 y auditoría del bloque 01–10 | **PR #16 abierto**, sin merge confirmado |
| Episodios 11–30 | No escritos en la instantánea |
| Revisión final, lectura cronometrada y producción de audio | Pendientes |

**IMPORTANTE:** el estado cambia. Antes de trabajar, verificá [PR #16](https://github.com/jonasmz/theThreshold/pull/16), PR abiertos y árbol de `main`; no crees un duplicado del episodio 10. Si #16 está integrado, la próxima tarea narrativa es **episodio 11**. Este PR de transferencia se basa en `main` y no incluye el contenido pendiente de #16.

## Mapa de fuentes: leer según tarea
| Necesidad | Fuente autoritativa |
|---|---|
| Decisiones explícitas y estatus de aprobación | [docs/registro-de-decisiones.md](docs/registro-de-decisiones.md) |
| Reglas consolidadas | [docs/biblia-1.0.md](docs/biblia-1.0.md) |
| Cosmología y magia | [biblia/01-cosmologia.md](biblia/01-cosmologia.md), [biblia/02-sistema-de-magia.md](biblia/02-sistema-de-magia.md), [biblia/09-reglas-operativas.md](biblia/09-reglas-operativas.md) |
| Instituciones, geografía y economía | [biblia/03-geografia-y-sociedad.md](biblia/03-geografia-y-sociedad.md), [biblia/04-politica-y-economia.md](biblia/04-politica-y-economia.md) |
| Personajes, relaciones y voz | [biblia/05-personajes.md](biblia/05-personajes.md), [biblia/07-red-de-relaciones.md](biblia/07-red-de-relaciones.md), [biblia/08-puntos-de-vista-y-voz.md](biblia/08-puntos-de-vista-y-voz.md) |
| Verdad oculta / causalidad | [secretos-del-autor/](secretos-del-autor/) (carpeta pública con spoilers) |
| Resolución y ritmo de temporada | [sinopsis-integral.md](temporadas/temporada-01/sinopsis-integral.md), [mapa-30-episodios.md](temporadas/temporada-01/mapa-30-episodios.md) |
| Continuidad y borradores | [control-de-continuidad.md](temporadas/temporada-01/control-de-continuidad.md), [episodios/](temporadas/temporada-01/episodios/) |
| Método y registros de trabajo | [editorial/](editorial/) |

## Calidad y límites actuales
- Los episodios 01–10 son/serán **borradores narrativos**, no guiones de locución definitivamente editados.
- Su longitud varía aproximadamente entre 2.200 y 3.200 palabras; **no** extrapolar automáticamente el objetivo de 5.000 palabras de otra propuesta sobre MTG.
- La duración en audio es estimativa, **no** cronometrada.
- La revisión final debe detectar repeticiones de escenas administrativas, consistencia de cronología, procedencia de pistas y diferenciación de voces.
- La Biblia 1.0 se autodefine **candidata**; estados provisionales siguen provisionales aun después de fusionar PR.

## Política de comunicación
En cada PR y conversación, informar solamente: episodio, cantidad aproximada de palabras, control editorial, archivos afectados, enlace y necesidad de merge. **No copiar trama ni pistas en la comunicación al creador.**

## Cómo retomar en una nueva sesión de Codex
1. Abrir el repositorio en su directorio raíz.
2. Pedir: «Leé AGENTS.md y PROJECT_CONTEXT.md. Verificá `main` y PR abiertos. Continuá la producción del próximo episodio siguiendo el protocolo. PR sin merge automático y respuesta libre de spoilers».
3. Revisar la respuesta final solo como **reporte operativo**; el texto de la historia está disponible en el PR pero el creador eligió no leerlo.
4. Después del merge, abrir una sesión nueva si conviene: la continuidad reside en Git y en los documentos, no en el historial del chat.

## Mantenimiento de este archivo
Actualizar la fotografía de estado **cuando cambie un bloque importante** (por ejemplo, episodios 10/20/30 o cierre de fase), no necesariamente en cada episodio. Los registros granulares están en `editorial/`.