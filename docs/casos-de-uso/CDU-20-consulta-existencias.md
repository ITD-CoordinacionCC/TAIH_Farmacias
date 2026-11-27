# CDU-20 · Consulta Masiva de Existencias y Catálogo

| Campo | Valor |
|-------|-------|
| **ID** | CDU-20 |
| **Actor principal** | Médicos / Servicios |
| **Tipo de operación** | Lectura Masiva (High QPS) |
| **Módulos involucrados** | Servicios Clínicos |
| **Grupo funcional** | Inventario, red fría y abasto |
| **Microservicio** | `Farmacia.CatalogoInventario.Api` |
| **Rama de trabajo** | `feature/angelornelas16` |
| **Responsable** | @AngelOrnelas16 |

## Descripción y efecto

Consulta concurrente de stock por clave institucional optimizada en memoria/Redis para 80k usuarios.

## Criterios de aceptación

- [ ] Consulta por clave institucional usando caché L1 (memoria) y L2 (Redis).
- [ ] Las lecturas en caché no llegan a la base de datos.
- [ ] La caché se invalida cuando cambia el stock.

## Flujo principal

1. _Por definir por el responsable del CDU._

## Flujos alternos / excepciones

- _Por definir._

## Definición de terminado

- [ ] Código en la rama del CDU con pruebas unitarias.
- [ ] Pull request hacia `develop` aprobado y con CI en verde.
- [ ] Documento del CDU actualizado (flujo principal y alternos).
