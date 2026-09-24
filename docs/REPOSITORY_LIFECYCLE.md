# Ciclo de vida de repositorios

| Estado | Organización | Escritura | Archive | Uso |
|---|---|---:|---:|---|
| ACTIVE | Sixbell | Sí | No | Desarrollo activo |
| MAINTENANCE | Sixbell | Sí | No | Mantenimiento de solución vigente |
| LEGACY-SUPPORTED | Sixbell-Legacy | Restringida | No | Soporte de solución legada |
| LEGACY-FROZEN | Sixbell-Legacy | No | Sí | Conservación histórica |
| TRANSFERRED | Sixbell-Legacy | No | Sí, salvo excepción | Solución transferida |
| CLOSED | Sixbell-Legacy | No | Sí | Proyecto/servicio cerrado |
| DELETE-CANDIDATE | Pendiente | No | Según caso | Evaluación antes de eliminar |

## Transiciones

```text
ACTIVE -> MAINTENANCE -> LEGACY-SUPPORTED -> LEGACY-FROZEN
                              |
                              +-> TRANSFERRED
                              |
                              +-> CLOSED
```

Una transición hacia Legacy debe quedar respaldada por el assessment o por una decisión explícita del owner responsable.
