# CDU-16 · Conciliación de Desecho y Envases Vacíos

| Campo | Valor |
|-------|-------|
| **ID** | CDU-16 |
| **Actor principal** | Farmacéutico / Enfermería |
| **Tipo de operación** | Escritura (Doble Testigo) |
| **Módulos involucrados** | Quirófano, Urgencias |
| **Grupo funcional** | Medicamentos controlados |
| **Microservicio** | `Farmacia.MedicamentosControlados.Api` |
| **Rama de trabajo** | `feature/22041153ems` |
| **Responsable** | @22041153ems |

## Descripción y efecto

Verifica la devolución física de ampolletas vacías o el desecho presenciado de remanentes de narcóticos.

## Criterios de aceptación

- [ ] Registra la devolución de ampolletas vacías o el desecho de remanentes.
- [ ] Exige dos testigos con firma.
- [ ] Una discrepancia genera un incidente.

## Flujo principal

1. _Por definir por el responsable del CDU._

## Flujos alternos / excepciones

- _Por definir._

## Definición de terminado

- [ ] Código en la rama del CDU con pruebas unitarias.
- [ ] Pull request hacia `develop` aprobado y con CI en verde.
- [ ] Documento del CDU actualizado (flujo principal y alternos).
