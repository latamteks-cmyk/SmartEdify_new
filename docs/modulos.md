# SmartEdify_new
Gobernanza (Governance-Service): Administra la toma de decisiones y las asambleas del condominio de principio a fin. Se encarga de organizar las convocatorias, verificar el quórum y generar las actas con validez legal. Si el sistema de reglas falla temporalmente, cuenta con un modo de emergencia que permite realizar la asamblea sin interrupciones, validando todo posteriormente para no bloquear la operación.

Reglas y Normativas (Compliance-Service): Es el "juez" de la plataforma. Se asegura de que cualquier acción (reservar un área, hacer una asamblea, pagar) cumpla con las leyes del país y el reglamento interno del condominio. Funciona como un validador automático en tiempo real que garantiza que solo se permita hacer lo que es legal y correcto, manteniendo una copia de seguridad de las reglas para que el sistema siga funcionando incluso si hay problemas de conexión.

Reservas (Reservations-Service): Gestiona el uso de las áreas comunes (salas, parrillas, canchas). Controla la disponibilidad, verifica si el residente cumple los requisitos para reservar (por ejemplo, estar al día con los pagos o respetar el aforo máximo), aplica los cobros correspondientes de forma automática y maneja todo el proceso desde la solicitud hasta la cancelación o el ingreso al lugar.

Mantenimiento y Activos (Asset-Management-Service): Controla el inventario físico y el estado de las instalaciones. Sirve para reportar daños, programar reparaciones y hacer seguimiento a los equipos e inspecciones utilizando códigos QR en las distintas ubicaciones del condominio.

Finanzas (Finance-Service): Maneja la contabilidad y el dinero. Calcula las cuotas de mantenimiento, registra los pagos, administra el flujo de caja y genera los reportes financieros y fiscales necesarios para la correcta administración económica del lugar.

Nóminas (Payroll-Service): Administra el pago de los empleados del condominio. Calcula los sueldos, aplica las deducciones por beneficios u obligaciones legales y emite los recibos de pago, conectándose directamente con las instituciones tributarias correspondientes.

Cumplimiento Laboral (HR-Compliance-Service): Protege al condominio en su rol de empleador. Monitorea que los contratos, condiciones laborales y obligaciones con los trabajadores estén siempre en regla según las leyes laborales del país.

Notificaciones (Notifications-Service): Es el canal de comunicación. Se encarga de enviar todos los avisos, alertas y mensajes a los residentes y administradores, ya sea por correo electrónico, notificaciones en el celular o mensajes internos.

Documentos (Documents-Service): Actúa como el archivo oficial y seguro del condominio. Almacena documentos importantes de forma inalterable y permite la firma electrónica legal exclusivamente para papeles oficiales (como resoluciones o actas), asegurando que solo puedan firmar quienes tengan los cargos autorizados (como el presidente o secretario).

Transmisión (Streaming-Service): Facilita la participación a distancia. Permite transmitir en vivo las asambleas, registrando legalmente quién se conectó, a qué hora y validando su asistencia para las reuniones en formato híbrido.
