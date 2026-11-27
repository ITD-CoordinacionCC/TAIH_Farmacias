# CDU-06 · Canje y Surtimiento de Vale Pendiente

| Campo | Valor |
|-------|-------|
| **ID** | CDU-06 |
| **Actor principal** | Paciente / Farmacéutico |
| **Tipo de operación** | Escritura (Transaccional) |
| **Módulos involucrados** | Almacén General |
| **Grupo funcional** | Dispensación ambulatoria y vales |
| **Microservicio** | `Farmacia.Dispensacion.Api` |
| **Rama de trabajo** | `feature/bolstalex` |
| **Responsable** | @BolstAlex |

## Descripción y efecto

Valida vigencia del vale y realiza la entrega física cuando el lote arriba al hospital.

## Criterios de aceptación

- [ ] Valida la vigencia y el estado del vale.
- [ ] Surte con asignación PEPS cuando el lote ya está disponible.
- [ ] Marca el vale como canjeado y bloquea un segundo canje.

## Flujo principal

1. _Por definir por el responsable del CDU._

## Flujos alternos / excepciones

- _Por definir._

## Definición de terminado

- [ ] Código en la rama del CDU con pruebas unitarias.
- [ ] Pull request hacia `develop` aprobado y con CI en verde.
- [ ] Documento del CDU actualizado (flujo principal y alternos).
