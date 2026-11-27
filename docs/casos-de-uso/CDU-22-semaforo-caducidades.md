# CDU-22 · Semaforización y Gestión de Caducidades

| Campo | Valor |
|-------|-------|
| **ID** | CDU-22 |
| **Actor principal** | Sistema Automatizado |
| **Tipo de operación** | Lectura Analítica |
| **Módulos involucrados** | Almacén General |
| **Grupo funcional** | Inventario, red fría y abasto |
| **Microservicio** | `Farmacia.CatalogoInventario.Api` |
| **Rama de trabajo** | `feature/angelornelas16` |
| **Responsable** | @AngelOrnelas16 |

## Descripción y efecto

Clasifica stock en Verde (>6m), Amarillo (3-6m) y Rojo (<3m) para forzar rotación o canje.

## Criterios de aceptación

- [ ] Clasifica: Verde > 6 meses, Amarillo 3–6 meses, Rojo < 3 meses.
- [ ] La clasificación se ejecuta de forma automática y periódica.
- [ ] Produce un reporte de lotes en rojo para rotación o canje.

## Flujo principal

1. _Por definir por el responsable del CDU._

## Flujos alternos / excepciones

- _Por definir._

## Definición de terminado

- [ ] Código en la rama del CDU con pruebas unitarias.
- [ ] Pull request hacia `develop` aprobado y con CI en verde.
- [ ] Documento del CDU actualizado (flujo principal y alternos).
