# CDU-08 · Preparación de Dosis Unitaria (SDU)

| Campo | Valor |
|-------|-------|
| **ID** | CDU-08 |
| **Actor principal** | Farmacéutico Clínico |
| **Tipo de operación** | Escritura (Batch 24h) |
| **Módulos involucrados** | Piso Hospitalario |
| **Grupo funcional** | Distribución hospitalaria |
| **Microservicio** | `Farmacia.Dispensacion.Api` |
| **Rama de trabajo** | `feature/bolstalex` |
| **Responsable** | @BolstAlex |

## Descripción y efecto

Arma cajetines individualizados por cama y horario de administración para pacientes internados.

## Criterios de aceptación

- [ ] Genera los cajetines por cama y horario a partir de las órdenes médicas vigentes.
- [ ] El proceso en lote de 24 h incorpora cambios y suspensiones de prescripción.
- [ ] Cada cajetín se identifica por paciente, cama y horario.

## Flujo principal

1. _Por definir por el responsable del CDU._

## Flujos alternos / excepciones

- _Por definir._

## Definición de terminado

- [ ] Código en la rama del CDU con pruebas unitarias.
- [ ] Pull request hacia `develop` aprobado y con CI en verde.
- [ ] Documento del CDU actualizado (flujo principal y alternos).
