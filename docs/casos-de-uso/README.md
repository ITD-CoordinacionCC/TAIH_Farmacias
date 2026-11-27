# Casos de Uso - Servicio de Farmacias (Hospitalin TAI)

Cada CDU tiene su documento, su issue en GitHub y su rama `feature/CDU-XX-...` creada desde `develop`.

| ID | Caso de uso | Grupo | Microservicio | Rama |
|----|-------------|-------|---------------|------|
| [CDU-01](CDU-01-validar-vigencia-derechos.md) | Validar Vigencia de Derechos (IMSS) | Derechohabiencia y receta | `Farmacia.Dispensacion.Api` | `feature/bolstalex` |
| [CDU-02](CDU-02-validar-receta.md) | Validar Autenticidad y Estado de Receta | Derechohabiencia y receta | `Farmacia.Dispensacion.Api` | `feature/bolstalex` |
| [CDU-03](CDU-03-receta-resurtible.md) | Procesar Receta Resurtible (Crónicos) | Derechohabiencia y receta | `Farmacia.Dispensacion.Api` | `feature/bolstalex` |
| [CDU-04](CDU-04-dispensacion-completa.md) | Dispensación y Surtimiento Completo | Dispensación ambulatoria y vales | `Farmacia.Dispensacion.Api` | `feature/bolstalex` |
| [CDU-05](CDU-05-vale-desabasto.md) | Emisión de Vale de Medicamento por Desabasto | Dispensación ambulatoria y vales | `Farmacia.Dispensacion.Api` | `feature/bolstalex` |
| [CDU-06](CDU-06-canje-vale.md) | Canje y Surtimiento de Vale Pendiente | Dispensación ambulatoria y vales | `Farmacia.Dispensacion.Api` | `feature/bolstalex` |
| [CDU-07](CDU-07-carro-de-paro.md) | Suministro Urgente a Carro de Paro / Shock | Distribución hospitalaria | `Farmacia.Dispensacion.Api` | `feature/bolstalex` |
| [CDU-08](CDU-08-dosis-unitaria.md) | Preparación de Dosis Unitaria (SDU) | Distribución hospitalaria | `Farmacia.Dispensacion.Api` | `feature/bolstalex` |
| [CDU-09](CDU-09-kits-quirurgicos.md) | Despacho de Kits Quirúrgicos y Anestesia | Distribución hospitalaria | `Farmacia.Dispensacion.Api` | `feature/bolstalex` |
| [CDU-10](CDU-10-devolucion-medicacion.md) | Conciliación y Devolución de Medicación | Distribución hospitalaria | `Farmacia.Dispensacion.Api` | `feature/22041153ems` |
| [CDU-11](CDU-11-interacciones-duplicidades.md) | Detección de Interacciones y Duplicidades | Seguridad farmacoterapéutica | `Farmacia.ValidacionClinica.Api` | `feature/22041153ems` |
| [CDU-12](CDU-12-validacion-alergias.md) | Validación Cruzada de Alergias del Paciente | Seguridad farmacoterapéutica | `Farmacia.ValidacionClinica.Api` | `feature/22041153ems` |
| [CDU-13](CDU-13-ajuste-posologico.md) | Ajuste Posológico por Falla Renal/Hepática | Seguridad farmacoterapéutica | `Farmacia.ValidacionClinica.Api` | `feature/22041153ems` |
| [CDU-14](CDU-14-receta-especial-controlados.md) | Validación de Receta Especial de Controlados | Medicamentos controlados | `Farmacia.MedicamentosControlados.Api` | `feature/22041153ems` |
| [CDU-15](CDU-15-libro-narcoticos.md) | Asiento en Libro Oficial de Narcóticos | Medicamentos controlados | `Farmacia.MedicamentosControlados.Api` | `feature/22041153ems` |
| [CDU-16](CDU-16-desecho-envases.md) | Conciliación de Desecho y Envases Vacíos | Medicamentos controlados | `Farmacia.MedicamentosControlados.Api` | `feature/22041153ems` |
| [CDU-17](CDU-17-registro-sram.md) | Registro de Sospecha de Reacción Adversa (SRAM) | Farmacovigilancia y alertas | `Farmacia.ValidacionClinica.Api` | `feature/22041153ems` |
| [CDU-18](CDU-18-reporte-farmacovigilancia.md) | Generación de Reporte Oficial de Farmacovigilancia | Farmacovigilancia y alertas | `Farmacia.ValidacionClinica.Api` | `feature/angelornelas16` |
| [CDU-19](CDU-19-bloqueo-lote.md) | Bloqueo y Retiro de Lote por Alerta Sanitaria | Farmacovigilancia y alertas | `Farmacia.CatalogoInventario.Api` | `feature/angelornelas16` |
| [CDU-20](CDU-20-consulta-existencias.md) | Consulta Masiva de Existencias y Catálogo | Inventario, red fría y abasto | `Farmacia.CatalogoInventario.Api` | `feature/angelornelas16` |
| [CDU-21](CDU-21-cadena-frio.md) | Monitoreo y Registro de Cadena de Frío | Inventario, red fría y abasto | `Farmacia.CatalogoInventario.Api` | `feature/angelornelas16` |
| [CDU-22](CDU-22-semaforo-caducidades.md) | Semaforización y Gestión de Caducidades | Inventario, red fría y abasto | `Farmacia.CatalogoInventario.Api` | `feature/angelornelas16` |
| [CDU-23](CDU-23-baja-tecnica.md) | Baja Técnica por Caducidad o Pérdida de Frío | Inventario, red fría y abasto | `Farmacia.CatalogoInventario.Api` | `feature/angelornelas16` |
| [CDU-24](CDU-24-requisicion-reorden.md) | Generación de Requisición por Punto de Reorden | Inventario, red fría y abasto | `Farmacia.CatalogoInventario.Api` | `feature/angelornelas16` |
| [CDU-25](CDU-25-recepcion-lotes.md) | Recepción Técnica de Lotes desde Almacén | Inventario, red fría y abasto | `Farmacia.CatalogoInventario.Api` | `feature/angelornelas16` |
