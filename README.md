# Sixbell Legacy

Repositorio de gobierno de la organización **Sixbell-Legacy**.

Esta organización conserva código y activos técnicos que ya no pertenecen al ciclo normal de desarrollo de Sixbell, pero que deben mantenerse por soporte, trazabilidad, auditoría, continuidad operacional o transferencia histórica.

## Principios

- **Legacy no significa eliminable.**
- Ningún repositorio se mueve aquí sólo por antigüedad o por su nombre.
- Todo repositorio debe tener una clasificación de ciclo de vida explícita.
- Los repositorios congelados deben quedar archivados.
- Los repositorios aún soportados mantienen escritura sólo para los responsables autorizados.
- Un repositorio trasladado a Legacy no debe utilizarse para iniciar nuevas funcionalidades sin una reclasificación formal.

## Estados de ciclo de vida

- `LEGACY-SUPPORTED`: sistema legado con soporte o dependencia productiva vigente.
- `LEGACY-FROZEN`: conservación histórica; sin evolución.
- `TRANSFERRED`: solución transferida a un cliente, tercero u otra unidad.
- `CLOSED`: proyecto o servicio cerrado.
- `DELETE-CANDIDATE`: candidato a eliminación sujeto a validación previa.

## Gobierno

Ver:

- [Gobierno Legacy](docs/LEGACY_GOVERNANCE.md)
- [Ciclo de vida de repositorios](docs/REPOSITORY_LIFECYCLE.md)
- [Criterios de migración](docs/MIGRATION_CRITERIA.md)
- [Baseline de seguridad](docs/SECURITY_BASELINE.md)
- [Modelo de ownership](docs/OWNERSHIP_MODEL.md)

> La clasificación final de los repositorios proviene del assessment de SixbellComponentes. La presencia de prefijos o sufijos como `TMP` no debe interpretarse automáticamente como temporalidad.
