# Dashboard de Ejecución Presupuestaria - Aragón (2013-2024)

## 📊 Descripción del Proyecto

Proyecto de **Business Intelligence con Power BI** enfocado en el análisis de la ejecución presupuestaria del Gobierno de Aragón utilizando datos abiertos oficiales (2013-2024).

El objetivo es construir un dashboard estratégico que permita analizar:

* Ejecución de **gastos públicos**.
* Evolución de **ingresos**.
* Clasificación presupuestaria completa (económica, funcional, orgánica y financiación).
* Tendencias financieras y prioridades de política pública.

Los datos provienen del portal **Aragón Open Data** y se trabajan bajo un enfoque de modelo estrella para análisis avanzado.

---

## 📂 Estructura del Repositorio

* `data/raw/` → Archivos CSV originales descargados del portal open data.

  * Estado de ejecución de gastos.
  * Estado de ejecución de ingresos.
  * Estructura económica.
  * Estructura funcional.
  * Estructura orgánica.
  * Estructura de financiación.
* `docs/` → Documentación y planificación del proyecto.
* `img/iconos/` → Recursos visuales utilizados en el dashboard.
* `reports/` → Archivos Power BI (.pbip / .pbix) y exportaciones.
* `scratch/` → Borradores e ideas rápidas (uso local).

---

## 🛠️ Desafíos Técnicos (ETL)

* Normalización de formatos numéricos europeos.
* Consolidación de múltiples ejercicios en tablas de hechos únicas.
* Integración de estructuras presupuestarias oficiales como dimensiones.
* Modelado tipo **Star Schema** para análisis financiero público.

---

## 📈 KPIs Principales

* % Ejecución Presupuestaria (Obligaciones vs Crédito Definitivo).
* % Pago sobre obligaciones reconocidas.
* Cumplimiento de previsión de ingresos.
* Resultado presupuestario (Ingresos vs Gastos).
* Análisis por capítulo económico y función pública.

---

## 🧩 Clasificación Presupuestaria

El modelo incorpora estructuras oficiales:

* **Económica:** Capítulos, artículos, conceptos y subconceptos.
* **Funcional:** Políticas públicas y programas de gasto.
* **Orgánica:** Centros gestores e instituciones.
* **Financiación:** Origen de los recursos económicos.

---

## 📝 Diccionario de Datos Rápido

* **Capítulo 1:** Gastos de Personal.
* **Capítulo 2:** Bienes y Servicios.
* **Capítulo 4/7:** Transferencias.
* **Capítulo 6:** Inversiones Reales.

---

## 🚀 Objetivo del Proyecto

Desarrollar un dashboard profesional orientado a analítica financiera del sector público, demostrando capacidades en:

* Modelado de datos en Power BI.
* Transformaciones ETL.
* Diseño de KPIs estratégicos.
* Visualización avanzada aplicada a finanzas públicas.
