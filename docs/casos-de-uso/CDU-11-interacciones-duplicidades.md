# CDU-11 · Detección de Interacciones y Duplicidades

| Campo | Valor |
|-------|-------|
| **ID** | CDU-11 |
| **Actor principal** | Motor Farmacoterapéutico |
| **Tipo de operación** | Lectura Analítica |
| **Módulos involucrados** | Expediente Clínico |
| **Grupo funcional** | Seguridad farmacoterapéutica |
| **Microservicio** | `Farmacia.ValidacionClinica.Api` |
| **Rama de trabajo** | `feature/CDU-11-interacciones-duplicidades` |
| **Responsable** | @22041153ems |

## Descripción y efecto

Cruza medicamentos prescritos simultáneamente y emite alertas de riesgo leve, moderado o severo.

## Criterios de aceptación

- [ ] Cruza todos los medicamentos activos del paciente.
- [ ] Clasifica cada alerta como leve, moderada o severa.
- [ ] Detecta duplicidad terapéutica.

## Flujo principal

1. _Por definir por el responsable del CDU._

## Flujos alternos / excepciones

- _Por definir._

## Definición de terminado

- [ ] Código en la rama del CDU con pruebas unitarias.
- [ ] Pull request hacia `develop` aprobado y con CI en verde.
- [ ] Documento del CDU actualizado (flujo principal y alternos).
