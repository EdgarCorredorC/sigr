# SIGR – Sistema Integral de Gestión de Restaurante

Línea base del código fuente de una aplicación web para gestionar pedidos, reservas, menú, caja y reportes de cualquier restaurante.

> Proyecto académico – Tecnológica del Oriente (AA2: Taller Grupal – Línea Base).
> Hecho por: _Edgar Fernando Corredor Córdoba_

## Módulos
| Módulo | Descripción |
|---|---|
| Autenticación | Clientes, meseros y administrador |
| Menú digital | CRUD de platos y categorías |
| Pedidos | Registro y seguimiento en tiempo real |
| Reservas | Por fecha y hora |
| Caja y facturación | Cierre de caja |
| Reportes | Ventas diarias |

## Estructura del repositorio
```
sigr/
├── backend/            # API REST (módulos en src/modules)
├── frontend/           # Interfaz web
├── database/           # migrations, seeds, schema
├── deploy/             # docker, jenkins
├── docs/               # arquitectura, requisitos, manuales, evidencias
├── .github/            # plantillas de Issues y PR
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
└── README.md
```

## Clonar y ejecutar
```bash
git clone https://github.com/EdgarCorredorC/sigr.git
cd sigr
cp .env.example .env
```
Los pasos de instalación y ejecución se completarán al definir el stack tecnológico (ver `docs/manuales/manual-despliegue.md`).

## Control de versiones
- Rama estable: `main`
- Línea base: tag `v1.0.0-baseline`
- Convenciones: ver [CONTRIBUTING.md](CONTRIBUTING.md)
- Historial de cambios: ver [CHANGELOG.md](CHANGELOG.md)

## Herramientas de soporte
GitHub (versionado), GitHub Issues (mejoras y bugs), Jenkins (opcional, CI futura).

## Licencia
MIT – ver [LICENSE](LICENSE).
