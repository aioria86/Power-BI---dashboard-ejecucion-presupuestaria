# Dashboard de Ejecución Presupuestaria - Aragón (2013-2024)

## 📊 Descripción del Proyecto
Este proyecto de Business Intelligence analiza la evolución financiera del Gobierno de Aragón durante la última década. El objetivo es transformar los datasets de ejecución presupuestaria del portal de **Aragón Open Data** en un dashboard estratégico que permita identificar tendencias de gasto, desviaciones presupuestarias y prioridades sectoriales.

## 📂 Estructura del Repositorio
- `data/`: Contiene los archivos CSV originales (raw) y los procesados.
- `reports/`: Archivos .pbip de Power BI y exportaciones en PDF.
- `scripts/`: Notas sobre transformaciones en Power Query o DAX.
- `scratch/`: (Ignorado por Git) Espacio para borradores e ideas rápidas.

## 🛠️ Desafíos Técnicos (ETL)
- **Normalización Numérica:** Limpieza de formatos de moneda europeos (puntos para miles, comas para decimales).
- **Consolidación:** Unión de 12 archivos anuales en una única Tabla de Hechos.
- **Jerarquías:** Mapeo de códigos de 'Centro Gestor' y 'Económico' para análisis funcional.

## 📈 KPIs Principales
- **% de Ejecución:** Comparativa entre Crédito Inicial vs. Obligaciones Reconocidas.
- **Variación Interanual:** Crecimiento del gasto por capítulos económicos.
- **Análisis de Modificaciones:** Impacto de los ajustes presupuestarios durante el ejercicio.

## 📝 Diccionario de Datos Rápido
- **Capítulo 1:** Gastos de Personal.
- **Capítulo 2:** Gasto Corriente (Bienes y servicios).
- **Capítulo 4/7:** Transferencias (Subvenciones).
- **Capítulo 6:** Inversiones Reales (Obra pública).