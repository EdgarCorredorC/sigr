# Convenciones de contribución

## Ramas
- `main`: rama estable (línea base).
- `develop`: integración.
- `feature/<modulo>-<descripcion>`: nuevas funcionalidades.
- `fix/<descripcion>`: corrección de errores.

## Commits (Conventional Commits)
`tipo(modulo): descripción` — tipos: `feat`, `fix`, `docs`, `chore`, `test`, `refactor`.
Ejemplo: `feat(reservas): agregar validación de fecha y hora`

## Flujo
1. Crear Issue.
2. Crear rama desde `develop`.
3. Pull Request hacia `develop`, revisado por otro integrante.
4. Los cambios a `main` solo mediante PR.

## Convenciones de código
- Nombres de archivos en minúscula con guiones: `crear-pedido.js`.
- Variables y funciones en camelCase; clases en PascalCase.
- Un módulo = una carpeta con sus rutas, controladores, servicios y modelos.
