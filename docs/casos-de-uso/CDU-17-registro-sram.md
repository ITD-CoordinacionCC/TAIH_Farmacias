# CDU-17 · Registro de Sospecha de Reacción Adversa (SRAM)

| Campo | Valor |
|-------|-------|
| **ID** | CDU-17 |
| **Actor principal** | Médico / Farmacéutico |
| **Tipo de operación** | Escritura (Evento) |
| **Módulos involucrados** | Expediente Clínico |
| **Grupo funcional** | Farmacovigilancia y alertas |
| **Microservicio** | `Farmacia.ValidacionClinica.Api` |
| **Rama de trabajo** | `feature/CDU-17-registro-sram` |
| **Responsable** | @22041153ems |

## Descripción y efecto

Captura incidentes adversos: fármaco, lote, manifestaciones clínicas, gravedad y desenlace.

## Criterios de aceptación

- [ ] Captura fármaco, lote, manifestaciones clínicas, gravedad y desenlace.
- [ ] Vincula la notificación al expediente del paciente.
- [ ] Publica el evento para farmacovigilancia.

## Flujo principal

1. _Por definir por el responsable del CDU._

## Flujos alternos / excepciones

- _Por definir._

## Definición de terminado

- [ ] Código en la rama del CDU con pruebas unitarias.
- [ ] Pull request hacia `develop` aprobado y con CI en verde.
- [ ] Documento del CDU actualizado (flujo principal y alternos).
