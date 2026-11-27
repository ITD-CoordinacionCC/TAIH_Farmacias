# CDU-21 · Monitoreo y Registro de Cadena de Frío

| Campo | Valor |
|-------|-------|
| **ID** | CDU-21 |
| **Actor principal** | Sensores / Personal Farmacia |
| **Tipo de operación** | Escritura Periódica |
| **Módulos involucrados** | Almacenamiento Físico |
| **Grupo funcional** | Inventario, red fría y abasto |
| **Microservicio** | `Farmacia.CatalogoInventario.Api` |
| **Rama de trabajo** | `feature/angelornelas16` |
| **Responsable** | @AngelOrnelas16 |

## Descripción y efecto

Registra lecturas bihorarias de temperatura (2°C-8°C) y genera alarmas automáticas ante desviaciones.

## Criterios de aceptación

- [ ] Registra las lecturas de temperatura y humedad cada dos horas.
- [ ] Genera una alarma automática cuando la temperatura sale de 2–8 °C.
- [ ] Conserva un historial auditable de lecturas.

## Flujo principal

1. _Por definir por el responsable del CDU._

## Flujos alternos / excepciones

- _Por definir._

## Definición de terminado

- [ ] Código en la rama del CDU con pruebas unitarias.
- [ ] Pull request hacia `develop` aprobado y con CI en verde.
- [ ] Documento del CDU actualizado (flujo principal y alternos).
