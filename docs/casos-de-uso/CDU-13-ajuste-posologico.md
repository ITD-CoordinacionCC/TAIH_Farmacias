# CDU-13 · Ajuste Posológico por Falla Renal/Hepática

| Campo | Valor |
|-------|-------|
| **ID** | CDU-13 |
| **Actor principal** | Farmacéutico Clínico |
| **Tipo de operación** | Lectura / Alerta |
| **Módulos involucrados** | Expediente Clínico |
| **Grupo funcional** | Seguridad farmacoterapéutica |
| **Microservicio** | `Farmacia.ValidacionClinica.Api` |
| **Rama de trabajo** | `feature/CDU-13-ajuste-posologico` |
| **Responsable** | @22041153ems |

## Descripción y efecto

Sugiere ajuste de dosis si la tasa de filtración glomerular o enzimas hepáticas presentan disfunción.

## Criterios de aceptación

- [ ] Obtiene la TFG / creatinina y las enzimas hepáticas del expediente.
- [ ] Sugiere un ajuste de dosis cuando hay disfunción.
- [ ] Registra si la sugerencia se aceptó o se rechazó.

## Flujo principal

1. _Por definir por el responsable del CDU._

## Flujos alternos / excepciones

- _Por definir._

## Definición de terminado

- [ ] Código en la rama del CDU con pruebas unitarias.
- [ ] Pull request hacia `develop` aprobado y con CI en verde.
- [ ] Documento del CDU actualizado (flujo principal y alternos).
