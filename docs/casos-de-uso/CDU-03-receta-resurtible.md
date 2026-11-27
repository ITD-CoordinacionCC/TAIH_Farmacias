# CDU-03 · Procesar Receta Resurtible (Crónicos)

| Campo | Valor |
|-------|-------|
| **ID** | CDU-03 |
| **Actor principal** | Paciente / Farmacéutico |
| **Tipo de operación** | Lectura / Escritura |
| **Módulos involucrados** | Consulta Externa, Expediente |
| **Grupo funcional** | Derechohabiencia y receta |
| **Microservicio** | `Farmacia.Dispensacion.Api` |
| **Rama de trabajo** | `feature/CDU-03-receta-resurtible` |
| **Responsable** | @BolstAlex |

## Descripción y efecto

Controla entregas mensuales programadas (entrega 1, 2 o 3) para pacientes con enfermedades crónicas.

## Criterios de aceptación

- [ ] Identifica qué entrega corresponde (1, 2 o 3) del periodo trimestral.
- [ ] Impide surtir antes de la fecha programada o después de terminado el trimestre.
- [ ] Actualiza el contador de entregas en la receta.

## Flujo principal

1. _Por definir por el responsable del CDU._

## Flujos alternos / excepciones

- _Por definir._

## Definición de terminado

- [ ] Código en la rama del CDU con pruebas unitarias.
- [ ] Pull request hacia `develop` aprobado y con CI en verde.
- [ ] Documento del CDU actualizado (flujo principal y alternos).
