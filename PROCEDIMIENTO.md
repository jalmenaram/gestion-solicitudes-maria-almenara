# Procedimiento de gestión de solicitudes de servicio

**Proyecto:** Sistema de Gestión de Pedidos – María Almenara  
**Naturaleza:** simulación académica basada en Avance 2 Integrador 2-1.

## Flujo de atención
1. **Recibida:** registrar código, fecha, solicitante y descripción.
2. **En evaluación:** clasificar tipo, prioridad y responsable.
3. **Pendiente de aprobación:** solicitar autorización cuando corresponda.
4. **En proceso:** gestionar respuesta o solución, sin atribuir funcionalidades aún no implementadas.
5. **Resuelta:** documentar respuesta y evidencia.
6. **Cerrada:** validar resultado y finalizar seguimiento.

## Roles y reglas
- **Cliente:** solicita información de catálogo y pedidos o atención estándar.
- **Encargado:** atiende solicitudes operativas dentro de sus permisos.
- **Administrador:** gestiona accesos y permisos; la ruta /usuarios está restringida para Encargado.
- Las solicitudes de acceso requieren aprobación y verificación de privilegios mínimos.

## Criterios de prioridad
- **Alta:** permisos y accesos que afectan la seguridad.
- **Media:** consultas de pedidos, correcciones y notificaciones.
- **Baja:** información general de catálogo.

## Campos obligatorios
Código, fecha, solicitante, tipo, descripción, prioridad, responsable, necesidad de aprobación, aprobador, solución o respuesta, evidencia y estado final.

## Evidencia y limitaciones
Las solicitudes y sus respuestas son **casos simulados**, no atenciones reales. Las evidencias textuales indican qué registros se utilizarían; no constituyen capturas del seguimiento real. Según el avance, la V1 cuenta con autenticación, roles, API REST y conexión MariaDB; módulos completos de pedidos, trazabilidad y automatizaciones siguen pendientes.

## Seguimiento
Utilizar los Issues #1 a #6 y agregarlos a un GitHub Project tipo tablero con un campo **Estado** y las seis columnas del flujo. Mantener cada issue en el estado indicado en su registro y actualizar su checklist conforme avance.
