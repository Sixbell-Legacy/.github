# Gobierno de Sixbell-Legacy

## Objetivo

Separar del ciclo de desarrollo activo aquellos repositorios que requieren conservación o soporte controlado, sin perder trazabilidad técnica ni histórica.

## Reglas

1. Un repositorio sólo ingresa a Sixbell-Legacy después de una clasificación explícita.
2. La antigüedad, inactividad o nomenclatura del repositorio no son evidencia suficiente para clasificarlo como Legacy.
3. Todo repositorio debe tener owner técnico y estado de ciclo de vida conocido, o quedar marcado como pendiente de validación.
4. Los repositorios `LEGACY-FROZEN`, `TRANSFERRED` y `CLOSED` deben quedar archivados cuando no exista una dependencia operativa que impida hacerlo.
5. Los repositorios `LEGACY-SUPPORTED` permanecen editables sólo para equipos autorizados.
6. No se desarrollan nuevas funcionalidades en repositorios Legacy sin una reclasificación formal.
7. La transferencia de un repositorio debe preservar historial Git, tags, releases y referencias necesarias para trazabilidad.

## Fuente de clasificación

La clasificación inicial se obtiene del assessment de repositorios de SixbellComponentes y debe considerar al menos:

- cliente;
- producto;
- actividad reciente;
- estado contractual o del servicio;
- dependencias productivas;
- infraestructura asociada;
- responsable técnico;
- responsable de negocio;
- riesgos de seguridad;
- evidencia de transferencia, cierre o reemplazo.

## Excepción TMP

`TMP` puede corresponder al nombre de un producto/aplicativo desarrollado por Sixbell. No debe utilizarse como indicador automático de repositorio temporal.
