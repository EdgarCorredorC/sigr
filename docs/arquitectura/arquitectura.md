# Arquitectura (línea base)

Aplicación web en capas:

- **Frontend:** interfaz para clientes, meseros y administrador.
- **Backend:** API REST organizada por módulos.
- **Base de datos:** relacional; migraciones y semillas en `/database`.

## Módulos
| Módulo | Responsabilidad |
|---|---|
| auth | Usuarios, roles (cliente, mesero, administrador), login |
| menu | CRUD de platos y categorías |
| pedidos | Registro y seguimiento de pedidos en tiempo real |
| reservas | Reservas por fecha y hora |
| caja | Cierre de caja y facturación |
| reportes | Reportes de ventas diarios |
