# CDU-01 · Validar Vigencia de Derechos (IMSS)

| Campo | Valor |
|-------|-------|
| **ID** | CDU-01 |
| **Actor principal** | Farmacéutico / Sistema |
| **Tipo de operación** | Lectura (Externa) |
| **Módulos involucrados** | Consulta Externa, Trabajo Social |
| **Grupo funcional** | Derechohabiencia y receta |
| **Microservicio** | `Farmacia.Dispensacion.Api` |
| **Rama de trabajo** | `feature/CDU-01-validar-vigencia-derechos` |
| **Responsable** | @BolstAlex |

## Descripción y efecto

Valida que el paciente cuente con cobertura activa mediante NSS o CURP antes de autorizar el surtido.

## Criterios de aceptación

- [ ] Consulta el NSS o la CURP contra el servicio de vigencia de derechos.
- [ ] Si el paciente no tiene vigencia, se bloquea el surtido y se muestra el motivo.
- [ ] Cada consulta queda registrada en la bitácora con usuario, fecha y resultado.

## Flujo principal

1. _Por definir por el responsable del CDU._

## Flujos alternos / excepciones

- _Por definir._

## Definición de terminado

- [ ] Código en la rama del CDU con pruebas unitarias.
- [ ] Pull request hacia `develop` aprobado y con CI en verde.
- [ ] Documento del CDU actualizado (flujo principal y alternos).
