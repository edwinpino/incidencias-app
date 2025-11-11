# Arquitectura Mínima

Cliente (Swagger UI)
|
FastAPI (Backend)
|
SQLAlchemy / Pydantic
|
PostgreSQL (Podman)


## Componentes
| Componente | Tecnología |
|-----------|------------|
| Lenguaje | Python 3.10+ |
| Framework web | FastAPI |
| ORM | SQLAlchemy |
| Validación | Pydantic |
| BD | PostgreSQL 16 |
| Contenedores | Podman |
| CI | GitHub Actions |

## Justificación
- FastAPI permite desarrollo rápido y documentación automática.
- PostgreSQL es robusto y estándar en sector público.
- Podman evita daemon root y alinea con lineamientos de software libre.
