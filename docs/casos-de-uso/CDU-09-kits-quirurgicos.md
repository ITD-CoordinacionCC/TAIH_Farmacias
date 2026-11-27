# CDU-09 · Despacho de Kits Quirúrgicos y Anestesia

| Campo | Valor |
|-------|-------|
| **ID** | CDU-09 |
| **Actor principal** | Instrumentista / Anestesiólogo |
| **Tipo de operación** | Escritura (Transaccional) |
| **Módulos involucrados** | Quirófano |
| **Grupo funcional** | Distribución hospitalaria |
| **Microservicio** | `Farmacia.Dispensacion.Api` |
| **Rama de trabajo** | `feature/bolstalex` |
| **Responsable** | @BolstAlex |

## Descripción y efecto

Entrega canastillas con insumos y anestésicos específicos según el tipo de intervención programada.

## Criterios de aceptación

- [ ] Arma el kit según el tipo de intervención programada.
- [ ] Registra los narcóticos asignados al anestesiólogo.
- [ ] Concilia el kit contra la hoja de consumo real transoperatorio.

## Flujo principal

1. _Por definir por el responsable del CDU._

## Flujos alternos / excepciones

- _Por definir._

## Definición de terminado

- [ ] Código en la rama del CDU con pruebas unitarias.
- [ ] Pull request hacia `develop` aprobado y con CI en verde.
- [ ] Documento del CDU actualizado (flujo principal y alternos).
