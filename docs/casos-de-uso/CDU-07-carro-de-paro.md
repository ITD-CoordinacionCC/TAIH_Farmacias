# CDU-07 · Suministro Urgente a Carro de Paro / Shock

| Campo | Valor |
|-------|-------|
| **ID** | CDU-07 |
| **Actor principal** | Médico / Enfermero Urgencias |
| **Tipo de operación** | Escritura (Prioridad Alta) |
| **Módulos involucrados** | Urgencias |
| **Grupo funcional** | Distribución hospitalaria |
| **Microservicio** | `Farmacia.Dispensacion.Api` |
| **Rama de trabajo** | `feature/CDU-07-carro-de-paro` |
| **Responsable** | @BolstAlex |

## Descripción y efecto

Liberación inmediata sin bloqueo administrativo para reanimación; posterior conciliación de trazabilidad.

## Criterios de aceptación

- [ ] Libera los fármacos sin validaciones administrativas que bloqueen.
- [ ] Registra el ID de urgencia y la apertura de precinto del carro de paro.
- [ ] Genera un pendiente de conciliación de trazabilidad posterior.

## Flujo principal

1. _Por definir por el responsable del CDU._

## Flujos alternos / excepciones

- _Por definir._

## Definición de terminado

- [ ] Código en la rama del CDU con pruebas unitarias.
- [ ] Pull request hacia `develop` aprobado y con CI en verde.
- [ ] Documento del CDU actualizado (flujo principal y alternos).
