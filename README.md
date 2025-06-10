# Divvy-Q1-Analysis
"Análisis comparativo de viajes en bicicleta entre Q1 2019 y Q1 2020 usando R"

# 🚲 Análisis comparativo de viajes en bicicleta - Divvy Q1 2019 vs Q1 2020

Este proyecto analiza el comportamiento de los usuarios del sistema Divvy (Boston), comparando el primer cuatrimestre de 2019 con el de 2020. El objetivo fue identificar diferencias entre **usuarios miembros** y **usuarios ocasionales**, y entender cómo evolucionó el uso del sistema en ese período.

---

## 📂 Estructura del proyecto

- `scripts/` – Código en R para limpieza, transformación y visualización
- `datos/` – Archivos CSV de Q1 2019 y Q1 2020 procesados
- `graficos/` – Visualizaciones en PNG exportadas desde R
- `presentacion/` – Presentación ejecutiva del análisis (PDF)
- `README.md` – Este archivo

---

## 🛠️ Herramientas utilizadas

- **R + RStudio**
- `tidyverse`, `lubridate`, `ggplot2`
- Visualización con `ggplot2` y presentación con **Google Slides**

---

## 📊 Principales hallazgos

- 🚴 La cantidad total de viajes aumentó de 2019 a 2020.
- 👤 Los usuarios miembros siguen siendo los más activos, especialmente de lunes a viernes.
- 📅 En 2020 se observó un **aumento en viajes los domingos**, en especial de usuarios ocasionales.
- ⏱️ La **duración promedio de los viajes** pasó de 1016.34 s (2019) a 1326.90 s (2020).

---

## 🎯 Recomendaciones

- Enfocar campañas en usuarios ocasionales los fines de semana.
- Fortalecer fidelización de miembros para mantener su uso diario.
- Ajustar disponibilidad de bicicletas en función de la demanda semanal.

---

## 📥 Cómo usar este proyecto

1. Descargar los scripts de la carpeta `scripts/`
2. Correr `analisis_divvy.R` (asegurarse de tener tidyverse instalado)
3. Visualizar los gráficos exportados
4. Ver el archivo PDF de la presentación final

---
