# Los Ecos del Umbral
## Temporada 2 · Episodio 47: El interruptor que obedecía al revés

**Estado:** borrador narrativo 0.1. **Focalización:** Sera Nhal, tercera persona limitada.

***

La lámpara no se apagó cuando Nel pulsó el botón rojo.

Sera Nhal estaba a punto de autorizar el primer ciclo del banco de baja carga corregido. El acumulador seguía desconectado y la mesa solo recibía corriente de una pequeña fuente de prueba para verificar los mandos. Al pulsar la parada, debía apagarse una luz testigo. Permaneció encendida.

—Repetilo —dijo Sera.

Nel retiró el dedo y lo apoyó otra vez. Nada cambió.

En el taller esperaban dos especialistas, un inspector externo y una reserva energética contratada por horas. La prueba tenía una ventana breve: si no la utilizaban, habría que pagarla igualmente. Sera había pedido comprobar primero el corte sin energía de ensayo; Nel se había quejado de que aquella repetición era innecesaria.

Ahora no decía nada.

—Nadie conecte la reserva —ordenó Sera—. Retirad la llave de habilitación y anotad la hora.

Un técnico colocó el candado en la entrada de potencia. El inspector comprobó que los terminales estratégicos continuaban ausentes, igual que en los ensayos anteriores. No había vínculo con un Anclaje ni acceso a una instalación de la Red. Aun así, el defecto podía hacer que el banco aplicara más carga que la que su propio diseño había autorizado.

—¿Es el botón? —preguntó Nel.

—No sabemos si es el botón, el contacto o la lógica que interpreta la parada.

La palabra *parada* figuraba en cuatro hojas del protocolo. Si todos habían asumido que significaba lo mismo sin comprobar la conexión física, el problema no cabía dentro de una simple pieza averiada.

Sera dejó el formulario de inicio sin firmar.

El ensayo quedaba suspendido antes del primer impulso.

***

Para localizar la falla hicieron una prueba de continuidad con la fuente de potencia retirada.

El botón funcionaba. Sus contactos cambiaban de estado y el cable hasta el módulo de control estaba intacto. El error aparecía al otro extremo: el circuito que debía reconocer la orden utilizaba una referencia eléctrica alimentada por el mismo convertidor cuyo funcionamiento tenía que interrumpir.

—Si el convertidor cae, la señal de parada queda flotando —dijo Nel.

Sera miró la resistencia que el esquema dibujaba hacia una referencia segura. Estaba instalada al otro lado del aislador, donde no cumplía su función durante una pérdida de alimentación. La lógica podía interpretar la ausencia de referencia como permiso en lugar de bloqueo.

—Con la fuente de prueba lo estamos viendo en pequeño —dijo.

Nel se inclinó sobre el plano.

—Pero el disparador de potencia tiene otro fusible.

—Ese fusible limita una corriente determinada. No convierte una orden de aborto en un circuito independiente.

El inspector pidió el libro de montaje. Una corrección reciente, escrita a mano, había cambiado la posición de la resistencia. Estaba firmada por Nel y revisada por una técnica de otro turno. No había sido ocultada; el dibujo original y la pieza real podían compararse.

—Yo hice la modificación —dijo Nel.

—Y alguien la revisó —respondió Sera—. Tenemos que investigar por qué los dos aceptamos un esquema que no era seguro.

Él levantó la voz.

—No llegamos a encender nada.

—Porque comprobamos la parada antes.

La respuesta lo silenció.

Sera preservó fotografías, número de pieza, esquema de versión y resultado del ensayo de continuidad. Prohibió corregir el cableado en ese momento. El inspector necesitaba registrar primero la condición encontrada, no el aspecto que habría tenido si nadie se hubiera equivocado.

Un técnico preguntó si podían continuar con una carga aún menor.

Sera negó.

—Una carga pequeña no repara un aborto que puede no responder. El criterio de parada se ha incumplido. No hay una segunda interpretación conveniente.

***

La decisión vació el taller.

El personal de apoyo tendría que cobrar las horas pactadas sin haber efectuado el ensayo. La reserva energética regresaría al depósito con una tasa por transporte y disponibilidad. El laboratorio externo había desplazado a un especialista que no podía quedarse otra jornada.

Talia Mer llamó cuando recibió la suspensión.

—¿Han dañado el banco? —preguntó.

—No aplicamos el impulso. Detectamos una dependencia de alimentación entre el mando de parada y el módulo que debía cortar. Conservamos la configuración.

—¿Afecta las curvas que obtuvisteis antes?

Sera separó las hojas.

—Las dos curvas de baja carga de la versión anterior siguen siendo observaciones sobre entrada, calor y retorno, con sus incertidumbres. No sirven como validación de esta arquitectura de seguridad. Tampoco prueban que el aborto hubiera funcionado si lo hubiéramos necesitado.

—Eso hará que el informe sea más difícil de presentar.

—Será más difícil defenderlo si omitimos el defecto.

Talia aceptó pedir una revisión de ingeniería independiente, sin convertirla en licencia para una prueba real de retorno. El veto operativo sobre el Anexo Occidental continuaba sustentado por mediciones y competencia propias; aquel banco no lo alteraba.

Nel esperó a que terminara la comunicación.

—Van a decir que fui yo —murmuró.

Sera había trabajado lo suficiente con él para reconocer el miedo. Un error de montaje podía costarle una sanción, pero también podía esconder un fallo de revisión que permaneciera dispuesto a repetirse con cualquier otro técnico.

—El acta dirá qué modificaste, quién revisó y qué no detectamos —respondió—. No te voy a borrar del expediente. Tampoco voy a fingir que el resto del equipo no tuvo responsabilidad en aprobar el protocolo.

Nel respiró lentamente.

—¿Podré participar en la corrección?

—Sí, con supervisión distinta y pruebas en frío. La decisión final no será tuya ni mía a solas.

Fuera, un carro esperaba llevarse el acumulador. La cuadrilla no preguntó quién había fallado. Quería saber cuánta carga quedaba y si podían utilizarla en otro servicio.

Sera entregó la lectura exacta.

***

Esa noche el laboratorio parecía más pequeño.

Sin equipos encendidos, el banco era una suma de cables, resistencias y preguntas. Sera preparó un plano nuevo: la parada tendría una ruta física independiente de la alimentación de prueba, con contactos que interrumpieran por defecto si se perdía la referencia. Un testigo separado mostraría el estado real del corte. Antes de cualquier pulso, dos personas de turnos distintos tendrían que verificar el circuito y un observador externo documentaría la respuesta.

No escribió que el rediseño fuese seguro. Escribió que debía demostrarlo.

El inspector devolvió su primera nota. Señalaba que el error podía haberse detectado al comparar esquema, montaje y prueba de pérdida de energía. Ningún ensayo previo había registrado ese escenario específico. No era una conspiración ni un accidente inevitable: era una comprobación omitida.

Sera leyó la frase sin tacharla.

En el margen del cuaderno añadió el costo de la jornada: horas de taller, traslado, material de fijación y un día de retraso. Recordó al funcionario que le había pedido resultados rápidos porque la ciudad pagaba cada día de suspensión de rutas.

La presión era real. No transformaba un circuito incorrecto en uno aceptable.

Nel regresó para buscar su abrigo. Se detuvo frente al candado rojo.

—Pensé que encontraríamos una manera de sustituir a una persona —dijo.

—Todavía podemos buscarla. Pero no empezaremos por pedirle a una persona que compense lo que no sabemos construir.

Él bajó la mirada hacia el plano de la parada independiente.

—¿Y si el próximo diseño también falla?

—Lo registraremos y volveremos a corregirlo. Siempre que lo encontremos antes de poner a alguien en riesgo.

Sera cerró el libro de pruebas con el resultado de la jornada marcado en tinta oscura:

«Ensayo abortado. Condición de seguridad no demostrada».

No era una derrota escondida.

Era el único resultado que podían firmar sin mentir.

***Fin del episodio 47.***