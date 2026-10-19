# Nexo Gestión — prototipo inicial

Este paquete contiene una demostración web adaptable a móvil y escritorio.

## Cómo abrir
- Descomprime el ZIP.
- Abre `index.html` en un navegador moderno.
- Los datos se guardan en el almacenamiento local del navegador del dispositivo.

## Funciones de esta demo
- Resumen diario.
- Registro de ventas y formas de pago.
- Productos editables.
- Inventario básico y recetas compartidas.
- Compras y proveedores como texto.
- Gastos, pagos y movimientos de caja.
- Cierre con comparación de efectivo contado y esperado.
- Exportación e importación de datos JSON.
- Configuración del tipo de negocio y moneda.

## Límites importantes
Esta es una demo local, no una plataforma SaaS de producción. No incluye usuarios, sincronización en la nube, aislamiento multiempresa, recuperación de contraseña, suscripciones, facturación fiscal ni integraciones de pago. Las recetas y costos de ejemplo deben validarse antes de usar los resultados para tomar decisiones. La lógica de consumo de ingredientes es básica y debe ser auditada antes de usarse con inventario real.

## Próxima etapa de desarrollo
1. Repositorio Git y entorno de desarrollo.
2. Backend con autenticación y base de datos PostgreSQL.
3. Separación estricta de datos por empresa y rol, con políticas RLS.
4. Transacciones atómicas para ventas, recetas e inventario.
5. Pruebas de caja, reportes, importación y aislamiento entre clientes.
6. Despliegue web, copias de seguridad y monitoreo.
7. Suscripciones y portal de administración.
