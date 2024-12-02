# **Análisis Financiero: Ejemplo de Metodología y Visualización**

Este repositorio demuestra un enfoque general para realizar un análisis financiero utilizando **Python** para el procesamiento y análisis de datos, y **Power BI** para la visualización interactiva de los resultados. Los datos utilizados son capados y tienen el único propósito de ilustrar el proceso.

## **Descripción del Proyecto**
El objetivo del análisis es mostrar cómo procesar datos financieros, calcular indicadores clave y presentarlos de forma clara y visual para apoyar la toma de decisiones estratégicas.

### **Metodología**
1. **Procesamiento de datos con Python**:
   - Limpieza y transformación de datos en formatos adecuados.
   - Cálculo de indicadores clave como liquidez, solvencia y rentabilidad.
   - Exploración de tendencias a través de gráficos preliminares.

2. **Visualización con Power BI**:
   - Diseño de dashboards interactivos que presentan métricas clave.
   - Comparaciones entre periodos históricos y proyecciones ficticias.

## **Estructura del Repositorio**
- `procesamiento_financiero.ipynb`: Jupyter Notebook con el código Python que:
  - Procesa datos ficticios para análisis financiero.
  - Calcula ratios como liquidez, solvencia y rentabilidad.
  - Genera tablas y gráficos exportables.
- `visualizacion_financiera.pbix`: Archivo de Power BI con dashboards interactivos que ilustran el análisis.

## **Ratios Calculados**
A continuación, se detallan los principales indicadores calculados en el análisis:

1. **Ratios de Liquidez**:
   - **Ratio de Liquidez Corriente**: Activo Corriente / Pasivo Corriente.
   - **Prueba Ácida**: (Activo Corriente - Inventarios) / Pasivo Corriente.

2. **Ratios de Solvencia**:
   - **Ratio de Solvencia**: Patrimonio Neto / Total Pasivo.
   - **Autonomía Financiera**: Patrimonio Neto / Total Activo.

3. **Ratios de Rentabilidad**:
   - **Margen de EBITDA**: EBITDA / Ventas.
   - **Rentabilidad Financiera (ROE)**: Beneficio Neto / Patrimonio Neto.
   - **Rentabilidad Económica (ROA)**: EBIT / Total Activo.

4. **Ratios de Endeudamiento**:
   - **Ratio de Endeudamiento Total**: Total Pasivo / Total Activo.
   - **Ratio de Deuda a Largo Plazo**: Pasivo No Corriente / Patrimonio Neto.

5. **Ratios de Actividad**:
   - **Rotación de Activos**: Ventas / Total Activo.
   - **Rotación de Inventarios**: Costo de Ventas / Inventarios.
   - **Periodo Medio de Cobro**: (Cuentas por Cobrar / Ventas) × 365.

6. **Indicadores adicionales**:
   - **EBITDA**: Beneficio antes de intereses, impuestos, depreciaciones y amortizaciones.
   - **BAI (Beneficio Antes de Impuestos)**: Ingreso neto antes de impuestos.

## **Herramientas Utilizadas**
- **Python**:
  - Bibliotecas: `pandas`, `numpy`, `matplotlib`, `seaborn`.
  - Uso para preprocesar datos y calcular métricas financieras.
- **Power BI**:
  - Creación de dashboards interactivos para análisis visual.

## **Pasos Realizados**
### **1. Procesamiento de Datos (Python)**
- Transformé datos en formatos adecuados (fechas, decimales, categorías).
- Calculé indicadores financieros básicos como los detallados arriba.
- Exporté los datos procesados en formato compatible con Power BI.

### **2. Visualización (Power BI)**
- Diseñé dashboards que:
  - Representan la evolución de indicadores financieros.
  - Comparan métricas clave entre periodos ficticios.
  - Identifican tendencias y riesgos potenciales.



