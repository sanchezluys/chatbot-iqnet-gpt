# IA Tools

## informar_pago

- Configuración: "se usa para notificar un pago, que luego será gestionado por el departamento correspondiente"
- Parámetros de la Herramienta:
  - `dni`: numero de documento puede ser DNI, CUIT o CUIL. requerido: text
  - `monto_pago`: monto, en pesos argentinos. requerido: number
  - `fecha_pago`: fecha del pago. requerido: date
  - `foto_pago`: foto o imagen del pago, debe ser una imagen o archivo pdf, jpeg, jpg. requerido: file
- Acciones de la Herramienta:
  - Asigna a la memoria 'informa_pago_monto'={{monto_pago}}
  - Asigna a la memoria 'informa_pago_fecha'={{fecha_pago}}
  - Asigna a la memoria 'informa_pago_dni'={{dni}}
  - Asigna a la memoria 'informa_pago_foto'={{foto_pago}}
  - Responde:
    - "indicar que su pago será gestionado por el área encargada con los siguientes datos y que puede demorar en ser acreditado en sistema hasta 72 horas hábiles:
      - dni: {{dni}}
      - fecha: {{fecha_pago}}
      - monto: {{monto_pago}}"
  - Asigna a la memoria 'skill.llm_is_transfer'='true'
  - Asigna a la memoria 'departamento'='atencion_al_cliente'
  - Marcar la conversación con estado ABIERTO
