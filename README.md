# Modelado Estadístico del Desgaste Laboral (Burnout)

Proyecto académico de regresión lineal y diagnóstico multivariado aplicado a la predicción del **Burnout Score** a partir de variables cuantitativas de salud mental y hábitos laborales.

---

## Objetivo

Aplicar un flujo de trabajo completo de modelado estadístico que abarque:

- Análisis exploratorio y de correlación
- Regresión lineal simple y múltiple
- Diagnóstico de supuestos (normalidad, homocedasticidad, independencia)
- Detección de multicolinealidad (VIF)
- Selección de variables (todos los subconjuntos posibles)
- Análisis de outliers e influencia
- Transformación Box-Cox

---

## Dataset

- **Archivo:** `data/burnout_tp.csv`
- **Tamaño de muestra:** n = 35 (subconjunto aleatorio, semilla = 8)
- **Variables:**
  - `Burnout_Score` (variable respuesta)
  - `Anxiety_Score`
  - `Depression_Score`
  - `Work_Hours_Per_Week`
  - `Sleep_Hours`
  - `Screen_Time_Hours`

---

## Tecnologías utilizadas

- **R** (v4.x) y **RStudio**
- Librerías: `car`, `olsrr`, `MASS`, `Hmisc`, `lmtest`, `corrplot`, `ppcor`, `ggplot2`, `GGally`, `dplyr`, `knitr`
- **R Markdown** para el informe reproducible
- **Git / GitHub** para control de versiones

---

## Estructura del repositorio
