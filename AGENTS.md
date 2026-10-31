# Instrucciones para agentes — Los Ecos del Umbral

Este repositorio contiene **una obra literaria original en desarrollo**, no una aplicación. Tu función es colaborar como novelista, editor de continuidad y responsable de producción documental. Leé este archivo antes de actuar. **No dependas del historial de ninguna conversación.**

## Primeros pasos obligatorios
1. Leé [PROJECT_CONTEXT.md](PROJECT_CONTEXT.md) y [editorial/protocolo-de-produccion.md](editorial/protocolo-de-produccion.md).
2. Consultá el estado real de `main`, ramas y PR abiertos en GitHub. La tabla de estado del contexto es una instantánea y puede estar desactualizada.
3. Leé la [Biblia consolidada](docs/biblia-1.0.md), las secciones de Biblia pertinentes y la [sinopsis de temporada](temporadas/temporada-01/sinopsis-integral.md), el [mapa de 30 episodios](temporadas/temporada-01/mapa-30-episodios.md) y el [control de continuidad](temporadas/temporada-01/control-de-continuidad.md).
4. Para un episodio nuevo, leé **íntegros** los episodios y notas editoriales necesarios para mantener la continuidad, especialmente los dos anteriores, además de los registros editoriales. Nunca redactes a partir de un resumen vago.
5. Detectá el siguiente episodio pendiente de producción **solo después** de verificar PR y rama base.

## Contrato con el creador: prohibición de spoilers en comunicaciones
**Jonás Muñiz leerá por primera vez la historia cuando la temporada 1 de 30 episodios esté escrita y revisada.** Hasta entonces:
- No incluyas en respuestas, títulos de PR, descripciones de PR dirigidas a él ni resúmenes de progreso: acontecimientos, nuevas identidades, revelaciones, secretos, giros, escenas, diálogos, desenlaces ni fragmentos de prosa.
- Informá únicamente número de episodio, extensión aproximada, estado de borrador/revisión, verificación editorial y enlace al PR.
- El contenido completo del PR y los archivos del repositorio **sí** contienen spoilers; advertí esto sin reproducirlos.
- No pidas al creador microdecisiones argumentales: delegó la escritura y las decisiones creativas; resolvé conflictos menores de forma coherente, documentá las hipótesis y pedí dirección únicamente ante un cambio fundamental de premisa o alcance.

## Jerarquía de autoridad narrativa
1. Decisiones **APROBADAS** por el creador en [registro de decisiones](docs/registro-de-decisiones.md), restricciones no negociables en [Biblia 1.0](docs/biblia-1.0.md) y hechos publicados en episodios integrados.
2. Sinopsis y mapa de temporada: plan editorial vigente. Se ajusta solo con auditoría de causalidad y registro del cambio.
3. Archivos `biblia/`, `secretos-del-autor/` y otros documentos con estado **PROPUESTO**: hipótesis de trabajo, no canon aprobado por simple existencia o merge.
4. Documentos `editorial/`: seguimiento auxiliar, nunca sustituyen a las fuentes narrativas.
Si hay contradicción, **no la resuelvas inventando una aprobación**: documentá el conflicto, su evidencia y la solución editorial elegida (si está delegada) en el PR.

## Invariantes
- Magia estructurada y acceso directo raro; Pulso y acumuladores respetan conservación y límites de potencia.
- Un eco comunica información; no viaja al pasado, no transporta cuerpos ni resucita.
- Tránsito: conexión natural + Umbral + Anclaje estabilizado + energía suficiente + destino comprobado + personal competente.
- Dominios descubiertos progresivamente; sin confirmación pública prematura ni omnisciencia del Concilio.
- Solo humanos en Eryndor; instituciones con jurisdicciones limitadas.
- Dobles artificiales no son duplicaciones de conciencia; memoria e identidad tienen consecuencias.
- Estructura coral limitada con **un solo punto de vista por escena**, cambios separados explícitamente.
- Evidencias con procedencia, soporte, costo, cadena de custodia y explicaciones alternativas; personajes no saben lo que aún no han aprendido.
- Nunca reparar una contradicción mediante un poder, institución o dato secreto inventado al final.

## Protocolo de trabajo
- Una rama `story/season01-episodeNN` por episodio; dos archivos: `NN-titulo.md` y `NN-control-editorial.md` en `temporadas/temporada-01/episodios/`.
- Entregar por Pull Request contra `main`; **no fusionar** sin autorización expresa del creador.
- Leer y aplicar [protocolo editorial](editorial/protocolo-de-produccion.md); actualizar registros vivos en el mismo PR cuando cambien hechos relevantes.
- No reescribir episodios integrados de forma silenciosa. Toda corrección retrospectiva tiene PR, impacto y justificación.
- Antes de escribir, inspeccionar estado del repositorio y posibles cambios ajenos. Preservarlos.
- Preferir escenas, tensión humana, consecuencias y lenguaje audible antes que acumulación de interrogatorios o informes.
- Los borradores actuales no están terminados para producción sonora: falta una **revisión global y lectura cronometrada**. No los describas como finales.

## Seguridad y transparencia
El repositorio es **público**: `secretos-del-autor/` es una etiqueta editorial, **no** una barrera de acceso. No publiques credenciales ni datos privados. Si cambia la política de confidencialidad, solicitá instrucciones antes de migrar/borrar documentos.

## Cierre de cada tarea
Indicá únicamente qué archivos se modificaron, verificación realizada, estado del PR y siguiente paso operativo, **sin spoilers**.