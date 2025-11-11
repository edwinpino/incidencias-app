# DevSecOps Inicial – Checklist

| Ítem | Estado | Observaciones |
|---|---|---|
| No guardar contraseñas en código | ✅ | Se usarán variables de entorno |
| Variables de entorno configuradas | ✅ | `.env` local excluido por `.gitignore` |
| pip-audit ejecutado | ⬜ | Pendiente |
| gitleaks configurado | ⬜ | Se agrega en Sprint 2 |
| Revisión de dependencias en CI | ⬜ | Pendiente integración |

## Riesgos Identificados
1. Exposición accidental de contraseñas en repositorios.
2. Errores en migraciones o estructura de DB que afecten continuidad del servicio.
