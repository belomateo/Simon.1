# Simón · Gestión integral

Demo interactiva en español para un petshop con local, depósito y veterinaria. HTML, CSS y JavaScript sin dependencias de compilación.

## Demo pública

https://belomateo.github.io/simon-petshop-demo/

## Ejecutar

Abrir `index.html` o servir la carpeta del proyecto con cualquier servidor estático. Los datos ficticios se guardan en localStorage del navegador. Configuración permite exportar y restablecer los datos.

## Recorridos

- Atención → Crear pedido → Ventas → Cobrar → Stock y métricas actualizados.
- Agenda → Reservar turno → Registrar atención → Historia clínica y seguimiento.
- Depósito → Transferir al local → Consultar disponibilidad desde atención.
- Campañas → Seleccionar productos con mayor stock → Descuento → Simular envío a suscriptos → Descargar catálogo HTML imprimible.

Los turnos duran 40 minutos con intervalos de 10. Horarios de inicio: 09:00 a 16:30. La agenda bloquea superposiciones. Los encargues no reservan stock; el stock se valida y descuenta al cobrar.

## Alcance de la demo

WhatsApp, Gmail, ARCA, agente y recordatorios están simulados. El agente usa reglas locales, no un modelo de IA. Los adjuntos registran nombres; no transmiten archivos. Los recordatorios se ejecutan manualmente dentro de la demo. No hay envíos externos, facturas fiscales, recetas válidas, credenciales, backend, autenticación ni permisos de seguridad reales. El selector de roles controla vistas para presentación. El gráfico semanal contiene datos ilustrativos; las métricas de hoy se calculan sobre los registros.

Los datos no se sincronizan entre equipos. Para producción: backend, base de datos, autenticación y autorización, auditoría, copias de seguridad, servicios reales y almacenamiento seguro de secretos. Nunca ingresar datos personales reales ni credenciales en esta demo pública.

La marca y colores se utilizan como referencia proporcionada para esta presentación. Los recursos visuales de marca no se incluyen como licencia de uso comercial.
