# CDU-25 · Recepción Técnica de Lotes desde Almacén

| Campo | Valor |
|-------|-------|
| **ID** | CDU-25 |
| **Actor principal** | Encargado de Farmacia |
| **Tipo de operación** | Escritura (Ingreso) |
| **Módulos involucrados** | Almacén General |
| **Grupo funcional** | Inventario, red fría y abasto |
| **Microservicio** | `Farmacia.CatalogoInventario.Api` |
| **Rama de trabajo** | `feature/CDU-25-recepcion-lotes` |
| **Responsable** | @AngelOrnelas16 |

## Descripción y efecto

Verifica físicamente contra remisión: lote, caducidad, empaque, registro sanitario y temperatura.

## Criterios de aceptación

- [ ] Verifica lote, caducidad, empaque, registro sanitario y temperatura contra la remisión.
- [ ] Un rechazo genera un acta de rechazo técnico.
- [ ] Los lotes aceptados entran al inventario.

## Flujo principal

1. _Por definir por el responsable del CDU._

## Flujos alternos / excepciones

- _Por definir._

## Definición de terminado

- [ ] Código en la rama del CDU con pruebas unitarias.
- [ ] Pull request hacia `develop` aprobado y con CI en verde.
- [ ] Documento del CDU actualizado (flujo principal y alternos).
