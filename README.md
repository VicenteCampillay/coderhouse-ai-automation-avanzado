# coderhouse-ai-automation-avanzado

# Checkpoint 1 — Agente de Validación de Horas Extras
 
Un chatbot que recibe el reporte de un empleado sobre horas extras trabajadas y decide qué hacer con él: **aprobarlo**, **pedir un dato que falta** o **escalarlo** al área de personas.
 
## Cómo funciona
 
1. El empleado escribe su reporte en el chat.
2. El agente de IA lee el mensaje y, si necesita saber los límites o requisitos de ese tipo de hora extra, consulta una planilla de políticas antes de responder.
3. Según el caso, responde con una de cuatro decisiones: **aprobado**, **falta un dato**, **escalado** o **fuera de política**.
4. Si la decisión es aprobado, escalado o fuera de política, se envía automáticamente un correo con el resultado, a modo de registro. Si solo faltaba un dato, no se envía correo porque todavía no es una decisión final.
## Por qué está escrito así el prompt
 
Las instrucciones del agente están divididas en secciones claras (quién es, qué no puede hacer, qué debe lograr, y las reglas para decidir) para que sea difícil que se confunda o invente cosas que no están permitidas.
 
## Detalles pendientes
 
- El caso "falta un dato" no queda registrado por correo.
- Hay una configuración menor en la planilla que puede necesitar ajustarse a mano dentro de n8n.
## Archivo entregado
 
`checkpoint1_vicente_campillay.json`
