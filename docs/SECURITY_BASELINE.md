# Baseline de seguridad

## Organización

Configuración objetivo inicial:

- Base permission de miembros: `Read`.
- Creación de repositorios por miembros: deshabilitada.
- Forking de repositorios privados: deshabilitado.
- GitHub Actions: deshabilitado o restringido por defecto.
- Owners: grupo reducido.
- Repositorios: privados salvo excepción aprobada.

## Antes de migrar un repositorio

1. Identificar workflows de GitHub Actions.
2. Revisar secretos, tokens, claves y credenciales expuestas.
3. Identificar dependencias productivas.
4. Identificar packages y artefactos utilizados por sistemas activos.
5. Revisar integraciones/webhooks cuando corresponda.
6. Confirmar visibilidad del repositorio destino.
7. Definir si debe quedar archivado.

## Repositorios congelados

Un repositorio `LEGACY-FROZEN` debe quedar en modo archivado una vez terminada la validación, impidiendo modificaciones accidentales.

## Repositorios soportados

Un `LEGACY-SUPPORTED` puede permanecer sin archivar, pero el acceso de escritura debe otorgarse explícitamente al equipo responsable.
