# ACME Retail — Restricciones del MVP

## Tiempo

- **Plazo del MVP:** 12 semanas máximo.
- El lanzamiento debe coincidir con el próximo periodo de ventas estacional.
- No hay margen para extensión — si una funcionalidad no cabe en 12 semanas, se difiere a una fase posterior.

## Capacidad de Desarrollo

- Equipo disponible: 1 Tech Lead, 3 desarrolladores, 1 QA.
- No se contempla contratación adicional ni outsourcing para el MVP.
- El equipo debe mantener operaciones de soporte sobre la plataforma actual en paralelo (~20% de su capacidad).
- Capacidad efectiva estimada para el MVP: **80% de un equipo de 5 personas durante 12 semanas.**

## Experiencia de Usuario

- **Mobile-first:** La experiencia móvil es la prioridad de diseño. Desktop se adapta desde mobile, no al revés.
- Tiempo de carga objetivo: < 3 segundos en conexión 4G.
- El flujo principal (descubrimiento → recomendación → compra) debe completarse en un máximo de 5 pasos.

## Seguridad

- Autenticación obligatoria para compras y acceso al historial de pedidos.
- La exploración del catálogo y las recomendaciones por navegación deben funcionar sin registro.
- Cumplimiento con estándares de protección de datos de pago (PCI DSS).
- Los datos personales del cliente no se comparten con terceros.

## Escalabilidad

- La arquitectura debe soportar un crecimiento de 3x en usuarios concurrentes sin rediseño.
- El motor de recomendaciones debe poder incorporar nuevos modelos o fuentes de datos sin modificar la experiencia del usuario.

## Estrategia de Producto

- **Las recomendaciones personalizadas son el diferenciador estratégico** — deben estar presentes en el MVP independientemente de las restricciones de capacidad.
- Las funcionalidades que no aporten directamente a conversión o retención se difieren a fases posteriores.
- El MVP debe ser suficiente para validar la hipótesis de negocio con clientes reales antes de escalar la inversión.

## Integraciones

- El MVP debe integrarse con el sistema de inventario existente de ACME (lectura).
- El sistema de gestión de pedidos (OMS) actual se mantiene — el MVP no lo reemplaza.
- No se requieren integraciones con sistemas de terceros en la primera fase.
