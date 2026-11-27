# CDU-04 · Dispensación y Surtimiento Completo

| Campo | Valor |
|-------|-------|
| **ID** | CDU-04 |
| **Actor principal** | Farmacéutico |
| **Tipo de operación** | Escritura (ACID) |
| **Módulos involucrados** | Consulta Externa |
| **Grupo funcional** | Dispensación ambulatoria y vales |
| **Microservicio** | `Farmacia.Dispensacion.Api` |
| **Rama de trabajo** | `feature/CDU-04-dispensacion-completa` |
| **Responsable** | @BolstAlex |

## Descripción y efecto

Asigna lotes bajo norma PEPS/FIFO, descuenta stock del inventario activo y entrega al paciente.

## Criterios de aceptación

- [ ] Asigna los lotes por fecha de caducidad (PEPS/FIFO).
- [ ] El descuento de inventario es transaccional: se aplica completo o no se aplica.
- [ ] Usa concurrencia optimista (RowVersion) para que dos surtidos no tomen el mismo lote.
- [ ] Registra la entrega (clave, lote, cantidad) en el historial farmacológico.

## Flujo principal

1. _Por definir por el responsable del CDU._

## Flujos alternos / excepciones

- _Por definir._

## Definición de terminado

- [ ] Código en la rama del CDU con pruebas unitarias.
- [ ] Pull request hacia `develop` aprobado y con CI en verde.
- [ ] Documento del CDU actualizado (flujo principal y alternos).
