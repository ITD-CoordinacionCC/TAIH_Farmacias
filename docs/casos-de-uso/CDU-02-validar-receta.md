# CDU-02 · Validar Autenticidad y Estado de Receta

| Campo | Valor |
|-------|-------|
| **ID** | CDU-02 |
| **Actor principal** | Farmacéutico / Sistema |
| **Tipo de operación** | Lectura / Validación |
| **Módulos involucrados** | Consulta Externa, Urgencias |
| **Grupo funcional** | Derechohabiencia y receta |
| **Microservicio** | `Farmacia.Dispensacion.Api` |
| **Rama de trabajo** | `feature/CDU-02-validar-receta` |
| **Responsable** | @BolstAlex |

## Descripción y efecto

Verifica folio único, fecha de prescripción, estatus no surtido y cédula profesional del médico.

## Criterios de aceptación

- [ ] Rechaza folios duplicados o ya surtidos.
- [ ] Valida que la fecha de prescripción esté dentro de la vigencia de la receta.
- [ ] Valida la cédula profesional del médico prescriptor.
- [ ] Todo rechazo devuelve un motivo claro a Consulta Externa / Urgencias.

## Flujo principal

1. _Por definir por el responsable del CDU._

## Flujos alternos / excepciones

- _Por definir._

## Definición de terminado

- [ ] Código en la rama del CDU con pruebas unitarias.
- [ ] Pull request hacia `develop` aprobado y con CI en verde.
- [ ] Documento del CDU actualizado (flujo principal y alternos).
