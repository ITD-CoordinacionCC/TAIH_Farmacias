# CDU-14 · Validación de Receta Especial de Controlados

| Campo | Valor |
|-------|-------|
| **ID** | CDU-14 |
| **Actor principal** | Farmacéutico Responsable |
| **Tipo de operación** | Lectura / Retención |
| **Módulos involucrados** | Seguridad Informática |
| **Grupo funcional** | Medicamentos controlados |
| **Microservicio** | `Farmacia.MedicamentosControlados.Api` |
| **Rama de trabajo** | `feature/CDU-14-receta-especial-controlados` |
| **Responsable** | @22041153ems |

## Descripción y efecto

Exige validación de código de barras de recetario COFEPRIS para estupefacientes (Grupos I y II).

## Criterios de aceptación

- [ ] Valida el código de barras del recetario COFEPRIS.
- [ ] Retiene la receta especial en el sistema.
- [ ] Exige la firma electrónica avanzada del farmacéutico responsable.

## Flujo principal

1. _Por definir por el responsable del CDU._

## Flujos alternos / excepciones

- _Por definir._

## Definición de terminado

- [ ] Código en la rama del CDU con pruebas unitarias.
- [ ] Pull request hacia `develop` aprobado y con CI en verde.
- [ ] Documento del CDU actualizado (flujo principal y alternos).
