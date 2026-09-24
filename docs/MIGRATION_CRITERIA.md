# Criterios de migración a Sixbell-Legacy

Antes de transferir un repositorio se debe responder:

## Identidad

- ¿Qué cliente y producto representa?
- ¿Existe un repositorio reemplazante?
- ¿El nombre puede inducir a una clasificación incorrecta?

## Operación

- ¿Existe dependencia productiva?
- ¿Existen despliegues activos?
- ¿Tiene infraestructura, DNS, certificados, jobs o integraciones asociadas?
- ¿SAC u otro equipo todavía presta soporte?

## Ownership

- ¿Existe responsable técnico?
- ¿Existe responsable de negocio?
- ¿La solución fue transferida a un cliente o tercero?

## Seguridad

- ¿Se revisaron secretos y credenciales?
- ¿Existen workflows de GitHub Actions?
- ¿Existen artefactos, packages o releases requeridos?
- ¿Hay hallazgos de seguridad pendientes?

## Decisión

El resultado debe ser uno de:

- permanecer en Sixbell;
- migrar como `LEGACY-SUPPORTED`;
- migrar y archivar como `LEGACY-FROZEN`;
- migrar como `TRANSFERRED`;
- migrar como `CLOSED`;
- mantener como `DELETE-CANDIDATE` hasta validación.

## Regla

No realizar migraciones masivas sin validar primero el procedimiento con un piloto de pocos repositorios inequívocamente clasificados.
