# IA Tools

## informar_pago

- Configuración: "Registra la notificación de un pago y prepara la conversación para ser transferida a Atención al Cliente."
- Parámetros de la Herramienta:
  - `dni`: Número de documento del titular (DNI, CUIT o CUIL). requerido: text
  - `nombre_titular`: Apellido y nombre completo del titular del servicio. requerido: text
  - `comprobante_pago`: Comprobante oficial emitido o compartido desde la app bancaria/billetera virtual o una captura de pantalla del pago. requerido: file
- Acciones de la Herramienta:
  - Asigna a la memoria 'skill.llm.is_transfer'='true'
  - Asigna a la memoria 'departamento'='atencion_al_cliente'
  - Asigna la etiqueta 'Informa Pago'
  - Responde: "Genera el Resumen de la solicitud:# IA Tools
