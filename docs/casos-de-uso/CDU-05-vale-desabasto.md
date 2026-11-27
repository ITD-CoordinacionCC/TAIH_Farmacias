# CDU-05 · Emisión de Vale de Medicamento por Desabasto

| Campo | Valor |
|-------|-------|
| **ID** | CDU-05 |
| **Actor principal** | Farmacéutico / Sistema |
| **Tipo de operación** | Escritura (Compensación) |
| **Módulos involucrados** | Consulta Externa, Almacén |
| **Grupo funcional** | Dispensación ambulatoria y vales |
| **Microservicio** | `Farmacia.Dispensacion.Api` |
| **Rama de trabajo** | `feature/bolstalex` |
| **Responsable** | @BolstAlex |

## Descripción y efecto

Genera vale con folio oficial y vigencia cuando una clave del cuadro básico carece de existencia física.

## Criterios de aceptación

- [ ] Detecta cuando una clave prescrita no tiene existencia física.
- [ ] Genera un vale con folio oficial, código de barras y fecha de vigencia.
- [ ] Devuelve el folio del vale a Consulta Externa.

## Flujo principal

1. _Por definir por el responsable del CDU._

## Flujos alternos / excepciones

- _Por definir._

## Definición de terminado

- [ ] Código en la rama del CDU con pruebas unitarias.
- [ ] Pull request hacia `develop` aprobado y con CI en verde.
- [ ] Documento del CDU actualizado (flujo principal y alternos).
