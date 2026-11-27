# CDU-15 · Asiento en Libro Oficial de Narcóticos

| Campo | Valor |
|-------|-------|
| **ID** | CDU-15 |
| **Actor principal** | Farmacéutico Responsable |
| **Tipo de operación** | Escritura (Inmutable) |
| **Módulos involucrados** | Seguridad Informática |
| **Grupo funcional** | Medicamentos controlados |
| **Microservicio** | `Farmacia.MedicamentosControlados.Api` |
| **Rama de trabajo** | `feature/CDU-15-libro-narcoticos` |
| **Responsable** | @22041153ems |

## Descripción y efecto

Registra movimiento con saldo continuo, folio de receta y médico responsable conforme a ley sanitaria.

## Criterios de aceptación

- [ ] Los asientos son de solo inserción (no se editan ni se borran).
- [ ] Cada asiento mantiene el saldo continuo e incluye folio de receta y médico.
- [ ] Envía la pista de auditoría a Seguridad Informática.

## Flujo principal

1. _Por definir por el responsable del CDU._

## Flujos alternos / excepciones

- _Por definir._

## Definición de terminado

- [ ] Código en la rama del CDU con pruebas unitarias.
- [ ] Pull request hacia `develop` aprobado y con CI en verde.
- [ ] Documento del CDU actualizado (flujo principal y alternos).
