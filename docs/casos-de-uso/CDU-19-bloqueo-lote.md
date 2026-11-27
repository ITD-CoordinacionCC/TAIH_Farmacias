# CDU-19 · Bloqueo y Retiro de Lote por Alerta Sanitaria

| Campo | Valor |
|-------|-------|
| **ID** | CDU-19 |
| **Actor principal** | Supervisor de Farmacia |
| **Tipo de operación** | Escritura (Inmovilización) |
| **Módulos involucrados** | Almacén General, Quirófano |
| **Grupo funcional** | Farmacovigilancia y alertas |
| **Microservicio** | `Farmacia.CatalogoInventario.Api` |
| **Rama de trabajo** | `feature/CDU-19-bloqueo-lote` |
| **Responsable** | @AngelOrnelas16 |

## Descripción y efecto

Bloquea sistémicamente e inmoviliza físicamente lotes con reporte de contaminación o retiro oficial.

## Criterios de aceptación

- [ ] El bloqueo del lote aplica de inmediato en todos los servicios.
- [ ] Un lote bloqueado no se puede dispensar.
- [ ] Registra la inmovilización física y al responsable.

## Flujo principal

1. _Por definir por el responsable del CDU._

## Flujos alternos / excepciones

- _Por definir._

## Definición de terminado

- [ ] Código en la rama del CDU con pruebas unitarias.
- [ ] Pull request hacia `develop` aprobado y con CI en verde.
- [ ] Documento del CDU actualizado (flujo principal y alternos).
