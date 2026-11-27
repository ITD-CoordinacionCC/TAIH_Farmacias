# CDU-10 · Conciliación y Devolución de Medicación

| Campo | Valor |
|-------|-------|
| **ID** | CDU-10 |
| **Actor principal** | Enfermería de Piso / Quirófano |
| **Tipo de operación** | Escritura (Reingreso) |
| **Módulos involucrados** | Piso Hospitalario, Quirófano |
| **Grupo funcional** | Distribución hospitalaria |
| **Microservicio** | `Farmacia.Dispensacion.Api` |
| **Rama de trabajo** | `feature/22041153ems` |
| **Responsable** | @22041153ems |

## Descripción y efecto

Reintegra al stock fármacos no administrados por alta, cambio de indicación o sobrante de cirugía.

## Criterios de aceptación

- [ ] Registra el motivo de la devolución (alta, cambio de indicación o sobrante).
- [ ] Solo reintegra al stock si el empaque está íntegro y la caducidad es válida.
- [ ] Emite acuse de devolución al servicio que devuelve.

## Flujo principal

1. _Por definir por el responsable del CDU._

## Flujos alternos / excepciones

- _Por definir._

## Definición de terminado

- [ ] Código en la rama del CDU con pruebas unitarias.
- [ ] Pull request hacia `develop` aprobado y con CI en verde.
- [ ] Documento del CDU actualizado (flujo principal y alternos).
