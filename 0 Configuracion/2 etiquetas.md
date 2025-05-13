# Etiquetas Inteligentes del Chatbot IQ Net (v2.0)

- Si la respuesta del LLM indica que se está gestionando una mudanza o traslado del servicio, asignar la etiqueta 'Mudanzas y Traslados'
- Si la respuesta del LLM indica que se está informando o notificando un pago ya realizado, asignar la etiqueta 'Informa Pago'
- Si la respuesta del LLM indica que se está gestionando una solicitud de suspensión del servicio por parte del cliente, asignar la etiqueta 'Solicita Suspensión'
- Si la respuesta del LLM indica que se está brindando asistencia técnica por averías, fallas en el servicio o problemas de configuración, asignar la etiqueta 'Asistencia Técnica'
- Si la respuesta del LLM indica que se está diagnosticando o solucionando un problema específico de lentitud, intermitencia o falta de conexión a Internet, asignar la etiqueta 'Problema de Conexión'
- Si la respuesta del LLM indica que se está gestionando una solicitud para contratar o solicitar un nuevo servicio de IQ Net, asignar la etiqueta 'Contratar Servicio'
- Si la respuesta del LLM indica que se está respondiendo una consulta general sobre facturación (cómo ver la factura, fechas de vencimiento, conceptos, etc.), asignar la etiqueta 'Consulta Factura'
- Si la respuesta del LLM indica que se está gestionando una actualización de la información personal del cliente (teléfono, dirección, email, etc.), asignar la etiqueta 'Actualiza Datos'
- Si la respuesta del LLM indica que se está gestionando un cambio de plan o servicio solicitado por el cliente, asignar la etiqueta 'Cambio de Plan'
- Si la respuesta del LLM indica que se está informando sobre la disponibilidad del servicio en una zona geográfica específica, asignar la etiqueta 'Consulta Cobertura'
- Si la respuesta del LLM indica que se están proporcionando los horarios de atención al cliente (oficinas o chat), asignar la etiqueta 'Consulta Horarios'
- Si la respuesta del LLM indica que se está respondiendo a una queja, reclamo o expresión de insatisfacción por parte del cliente, asignar la etiqueta 'Reclamo'
- Si la respuesta del LLM indica que se está informando el saldo actual de la cuenta del cliente, asignar la etiqueta 'Consulta Saldo'
- Si la respuesta del LLM indica que se están proporcionando los datos bancarios (CBU, alias, número de cuenta) para que el cliente pueda realizar un pago, asignar la etiqueta 'Consulta CBU'
- Si la respuesta del LLM indica que se está transfiriendo la conversación a un agente humano o a otro departamento, asignar la etiqueta 'Transferencia Agente'
- Si la respuesta del LLM indica que no se pudo encontrar información relevante en la base de conocimiento o que se requiere asistencia adicional, asignar la etiqueta 'No Resuelve'

---

## Listado

| Id  | Etiqueta              | Uso                                                                                                                                                                                                |
|-----|-----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1   | Mudanzas y Traslados  | Se asigna cuando la respuesta del LLM indica que se está gestionando una solicitud de traslado del servicio a una nueva ubicación.                                                                |
| 2   | Informa Pago          | Se asigna cuando la respuesta del LLM indica que se está informando o notificando un pago ya realizado por el cliente.                                                                             |
| 3   | Solicita Suspensión    | Se asigna cuando la respuesta del LLM indica que se está gestionando una solicitud de suspensión del servicio por parte del cliente.                                                               |
| 4   | Asistencia Técnica    | Se asigna cuando la respuesta del LLM indica que se está brindando asistencia técnica por averías, fallas en el servicio o problemas de configuración.                                             |
| 5   | Problema de Conexión  | Se asigna cuando la respuesta del LLM indica que se está diagnosticando o solucionando un problema específico de lentitud, intermitencia o falta de conexión a Internet.                               |
| 6   | Contratar Servicio    | Se asigna cuando la respuesta del LLM indica que se está gestionando una solicitud para contratar o solicitar un nuevo servicio de IQ Net.                                                           |
| 7   | Consulta Factura      | Se asigna cuando la respuesta del LLM indica que se está respondiendo una consulta general sobre facturación (cómo ver la factura, fechas de vencimiento, conceptos, etc.).                           |
| 8   | Actualiza Datos        | Se asigna cuando la respuesta del LLM indica que se está gestionando una actualización de la información personal del cliente (teléfono, dirección, email, etc.).                                 |
| 9   | Cambio de Plan        | Se asigna cuando la respuesta del LLM indica que se está gestionando un cambio de plan o servicio solicitado por el cliente.                                                                      |
| 10  | Consulta Cobertura    | Se asigna cuando la respuesta del LLM indica que se está informando sobre la disponibilidad del servicio en una zona geográfica específica.                                                            |
| 11  | Consulta Horarios     | Se asigna cuando la respuesta del LLM indica que se están proporcionando los horarios de atención al cliente (oficinas o chat).                                                                    |
| 12  | Reclamo               | Se asigna cuando la respuesta del LLM indica que se está respondiendo a una queja, reclamo o expresión de insatisfacción por parte del cliente.                                                         |
| 13  | Consulta Saldo        | Se asigna cuando la respuesta del LLM indica que se está informando el saldo actual de la cuenta del cliente.                                                                                           |
| 14  | Consulta CBU          | Se asigna cuando la respuesta del LLM indica que se están proporcionando los datos bancarios (CBU, alias, número de cuenta) para que el cliente pueda realizar un pago.                                |
| 15  | Transferencia Agente | Se asigna cuando la respuesta del LLM indica que se está transfiriendo la conversación a un agente humano o a otro departamento.                                                                      |
| 16  | No Resuelve          | Se asigna cuando la respuesta del LLM indica que no se pudo encontrar información relevante en la base de conocimiento o que se requiere asistencia adicional.                                         |