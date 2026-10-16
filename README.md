# Héctor Manuel Hernández Narváez

**Líder de Implementación de IA, Análisis de Datos y Automatización de Procesos Operativos**  
*Transformando flujos manuales en herramientas confiables, agentes gobernados, datos organizados e indicadores de productividad y ahorro.*

---

## Perfil profesional

Ingeniero en Tecnologías de la Información (Titulado) enfocado en la intersección entre la **implementación de Inteligencia Artificial Generativa / Agentes de IA**, el **análisis de datos** y la **automatización de procesos operativos**. Identifico áreas de oportunidad en la operación para diseñar, ejecutar y monitorear soluciones prácticas que eliminan cuellos de botella: desde la captura estructurada en campo y la validación en tiempo real, hasta la consolidación analítica, el establecimiento de lineamientos de gobernanza y la capacitación de equipos internos.

Enfoque técnico fundamentado en evidencia verificable, evaluación de impacto (productividad, ahorro de costos y eficiencia), trazabilidad estricta y protección de datos corporativos.

---

## Competencias técnicas

- **Inteligencia Artificial Generativa & Agentes de IA:**  
  Integración de Modelos de Lenguaje (LLMs: OpenAI/GPT, Claude, Gemini), diseño de flujos con Agentes de IA y Model Context Protocol (MCP), ingeniería de prompts avanzada, automatización de desarrollo y análisis documental asistido por IA.
- **Gobernanza de IA, Trazabilidad & Alfabetización Digital:**  
  Establecimiento de lineamientos y buenas prácticas de uso de IA, prevención de fuga de información y anonimización estricta, validación determinista de salidas (Python / Playwright), control de concurrencia e idempotencia transaccional, y programas de capacitación para adopción en equipos internos.
- **Análisis de datos & Business Intelligence (KPIs y ROI):**  
  SQL Server, PostgreSQL, SQLite (consultas analíticas, agregaciones previas al cruce, resolución de grano), Microsoft Excel avanzado / Power Query, Power BI, Looker Studio, modelado relacional y dimensional, integración BigQuery (reportada).
- **Automatización de procesos y Ecosistemas Corporativos:**  
  Python, PowerShell, Microsoft 365 & Power Platform (Power Automate, Power Apps, SharePoint, Teams, Entra ID), Google Apps Script (enrutamiento de eventos, bloqueo concurrente con `LockService`, procesamiento por lotes), Google Forms y Google Sheets avanzado.
- **Desarrollo de herramientas internas:**  
  Python (FastAPI), React, TypeScript, ASP.NET Core, Tailwind CSS, persistencia offline con IndexedDB y arquitecturas PWA.

---

## Proyectos destacados

Los tres proyectos principales demuestran el ciclo completo: desde la captura en campo y la consolidación de fuentes hasta el análisis de costos unitarios.

### 1. [Data Warehouse Agrícola y Analítica Operativa](https://github.com/Hmhn2525/data-warehouse-agricola)
*Consolidación de registros operativos en Google Sheets y presentación analítica de rendimiento.*
- **Enfoque:** Arquitectura de datos para unificar registros de labores de campo, fletes y catálogos distribuidos.
- **Aportación clave:** Módulos de validación, autocompletado y depuración de duplicados en Google Apps Script. Ejemplo reproducible en SQL (SQLite) que resuelve el cálculo de costo unitario agregando hechos antes del cruce, evitando duplicación de costos o producción y contemplando producción cero.
- **Tecnologías:** Google Apps Script, Google Sheets, Looker Studio, SQL (SQLite), BigQuery (pendiente de inspección).
- **Evidencia:** 4 módulos GAS inspeccionados (16 definiciones de función) y modelo SQL pedagógico verificado.

### 2. [FuelTrack](https://github.com/Hmhn2525/fueltrack)
*Control y automatización del flujo de combustible: solicitud, aprobación y despacho en campo.*
- **Enfoque:** Eliminación de inconsistencias en el suministro de combustible mediante un flujo coordinado en tres etapas.
- **Aportación clave:** Validación administrativa con bloqueo concurrente en servidor; captura móvil con registro de evidencias; diseño de claves de idempotencia para prevenir dobles despachos en reintentos; y cola local en IndexedDB para resguardar despachos sin cobertura celular.
- **Tecnologías:** Google Apps Script, Google Sheets, Google Drive, JavaScript, IndexedDB, PWA.
- **Evidencia:** 65 pruebas locales simuladas históricas aprobadas (autorización, balance de saldos, fallos y reintentos) y comprobación reproducible de consistencia aritmética en escenario sintético.

### 3. [Inventario Físico](https://github.com/Hmhn2525/inventario-fisico-portafolio)
*Importación de existencias, captura de conteo físico trazable y conciliación por almacén.*
- **Enfoque:** Plataforma web para digitalizar auditorías de existencias en almacenes (*Subir reporte → Contar → Ver resumen*).
- **Aportación clave:** Distinción estricta entre partidas pendientes (`null`) y confirmación física de cero (`0`); control de concurrencia mediante versión esperada por partida; cálculo exacto de diferencias decimales para conciliación en ERP.
- **Tecnologías:** React, TypeScript, ASP.NET Core (.NET 10), PostgreSQL, ClosedXML, Playwright.
- **Evidencia:** Captura de interfaz real revisada con API sintética; 16 casos Playwright históricos documentados; 5 casos didácticos verificados. Código operativo resguardado de forma privada.

---

## Experiencia complementaria

Proyectos adicionales que complementan el dominio en gestión presupuestaria, gobernanza de registros y plataformas de soporte.

- **[Gestión y Control Presupuestario](https://github.com/Hmhn2525/gestion-presupuestaria):**  
  Captura descentralizada de presupuestos anuales por centro de costo con ciclo formal de revisión (*Borrador → Entrega → Revisión → Validación*), resguardo de versiones históricas y 19 pruebas de servidor verificadas.  
  *Stack:* React, TypeScript, Python, FastAPI, SQLite, SQLAlchemy.

- **[Seguridad y Salud en el Trabajo](https://github.com/Hmhn2525/seguridad-salud-trabajo):**  
  Automatización de captura de incidentes mediante Google Forms, normalización de semanas ISO y catálogos, y enrutamiento con `DocumentLock` en Google Sheets sin exponer datos clínicos sensibles.  
  *Stack:* Google Apps Script, Google Sheets, Google Forms, Looker Studio.

- **[Registros TIC](https://github.com/Hmhn2525/registros-tic):**  
  Demostración saneada de aplicación web para registro, vinculación de activos y trazabilidad de tickets de soporte técnico, con persistencia local y soporte de firma/PIN.  
  *Stack:* React, TypeScript, Vite, Tailwind CSS, Supabase, PostgreSQL, PWA.

---

## Propuesta de repositorios fijados (Pinned Repositories)

Para reflejar la especialidad en análisis de datos y automatización operativa, se propone fijar los repositorios en el siguiente orden:

1. `data-warehouse-agricola` (Análisis de datos, consolidación y SQL)
2. `fueltrack` (Automatización de procesos operativos e idempotencia)
3. `inventario-fisico-portafolio` (Auditoría de existencias y trazabilidad)
4. `gestion-presupuestaria` (Control de versiones y lógica financiera)
5. `seguridad-salud-trabajo` (Gobernanza de datos y flujos de formularios)
6. `registros-tic` (Sistemas internos y trazabilidad de soporte)

---

## Ficha de metadatos para repositorios de GitHub

| Repositorio | Descripción breve recomendada | Topics / Etiquetas |
|---|---|---|
| `data-warehouse-agricola` | Consolidación de datos agrícolas en Sheets y analítica operativa con modelo SQL reproducible en SQLite. | `google-apps-script`, `google-sheets`, `sql`, `sqlite`, `looker-studio`, `data-analysis`, `etl` |
| `fueltrack` | Automatización del flujo solicitud-aprobación-despacho de combustible con Google Apps Script, Sheets y captura offline en IndexedDB. | `google-apps-script`, `google-sheets`, `pwa`, `indexeddb`, `process-automation`, `javascript` |
| `inventario-fisico-portafolio` | Caso de estudio de inventario físico: importación de existencias, conteo trazable por almacén y tratamiento de cero vs pendientes. | `react`, `typescript`, `aspnet-core`, `postgresql`, `inventory-management`, `audit-trail` |
| `gestion-presupuestaria` | Control presupuestario por centro de costo, flujo de revisión y versionado inmutable con FastAPI y React. | `python`, `fastapi`, `sqlite`, `react`, `typescript`, `budget-management` |
| `seguridad-salud-trabajo` | Automatización de formularios de SST, gobernanza de catálogos y normalización de fechas en Google Sheets con Apps Script. | `google-apps-script`, `google-sheets`, `google-forms`, `looker-studio`, `data-governance` |
| `registros-tic` | Demostración web para registro y trazabilidad de soporte técnico con React, TypeScript y persistencia local/PostgreSQL. | `react`, `typescript`, `vite`, `supabase`, `postgresql`, `pwa`, `support-tickets` |

---

## Contacto

- **Correo electrónico:** [hhernandeznarvaez.1516@gmail.com](mailto:hhernandeznarvaez.1516@gmail.com)
- **LinkedIn:** [linkedin.com/in/hector-manuel-hernández-narváez-b67933239](https://www.linkedin.com/in/hector-manuel-hernández-narváez-b67933239/)
- **Portafolio web:** [hmhn2525.github.io](https://hmhn2525.github.io/)
