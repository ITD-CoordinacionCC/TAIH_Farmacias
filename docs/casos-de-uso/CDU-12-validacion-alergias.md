# CDU-12 · Validación Cruzada de Alergias del Paciente

| Campo | Valor |
|-------|-------|
| **ID** | CDU-12 |
| **Actor principal** | Motor de Seguridad Clínica |
| **Tipo de operación** | Lectura Crítica |
| **Módulos involucrados** | Expediente Clínico |
| **Grupo funcional** | Seguridad farmacoterapéutica |
| **Microservicio** | `Farmacia.ValidacionClinica.Api` |
| **Rama de trabajo** | `feature/CDU-12-validacion-alergias` |
| **Responsable** | @22041153ems |

## Descripción y efecto

Compara el principio activo prescrito contra las alergias documentadas en el expediente clínico.

## Criterios de aceptación

- [ ] Compara el principio activo contra las alergias del expediente.
- [ ] Una coincidencia genera una alerta crítica que detiene el surtido.
- [ ] Registra la decisión del farmacéutico ante la alerta.

## Flujo principal

1. _Por definir por el responsable del CDU._

## Flujos alternos / excepciones

- _Por definir._

## Definición de terminado

- [ ] Código en la rama del CDU con pruebas unitarias.
- [ ] Pull request hacia `develop` aprobado y con CI en verde.
- [ ] Documento del CDU actualizado (flujo principal y alternos).
