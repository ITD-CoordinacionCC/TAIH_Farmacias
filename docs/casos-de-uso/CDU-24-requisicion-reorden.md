# CDU-24 · Generación de Requisición por Punto de Reorden

| Campo | Valor |
|-------|-------|
| **ID** | CDU-24 |
| **Actor principal** | Sistema Automatizado |
| **Tipo de operación** | Lectura / Generación |
| **Módulos involucrados** | Almacén General |
| **Grupo funcional** | Inventario, red fría y abasto |
| **Microservicio** | `Farmacia.CatalogoInventario.Api` |
| **Rama de trabajo** | `feature/CDU-24-requisicion-reorden` |
| **Responsable** | @AngelOrnelas16 |

## Descripción y efecto

Calcula automáticamente necesidades de reposición según Consumo Promedio Diario (CPD).

## Criterios de aceptación

- [ ] Calcula el Consumo Promedio Diario (CPD) por clave.
- [ ] Genera la requisición cuando la existencia llega al punto de reorden.
- [ ] Envía la requisición a Almacén General.

## Flujo principal

1. _Por definir por el responsable del CDU._

## Flujos alternos / excepciones

- _Por definir._

## Definición de terminado

- [ ] Código en la rama del CDU con pruebas unitarias.
- [ ] Pull request hacia `develop` aprobado y con CI en verde.
- [ ] Documento del CDU actualizado (flujo principal y alternos).
