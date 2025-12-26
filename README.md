# Análisis Climático: Sequía en el Altiplano Peruano (2022-2023)

Este repositorio contiene el flujo de trabajo desarrollado para analizar las causas y la evolución del evento de sequía extrema que afectó al Altiplano Peruano. El estudio integra el análisis de variables oceánicas y atmosféricas para explicar el déficit de precipitación.

## 📖 Descripción del Proyecto
El objetivo fue demostrar cómo la fase de **La Niña** actuó como el forzante principal, alterando la Circulación de Walker y generando una barrera de alta presión que suprimió las lluvias en la región andina durante el periodo 2022-2023.

## 📊 Estructura del Análisis (Notebooks)

El proyecto se divide en tres módulos de procesamiento de datos en Python:

* **`Proyecto - TSM.ipynb` (Temperatura de la Superficie del Mar):** Procesamiento de la base de datos **ERSSTv5** para identificar anomalías negativas en el Pacífico Central y cuantificar la magnitud de La Niña mediante el Índice Niño 3.4.

* **`Presion a nivel del mar(slp) - PROYECTO.ipynb`:** Análisis de datos de reanálisis **NCEP** para identificar anomalías positivas de presión (SLP). Se modela el mecanismo de subsidencia atmosférica que impide la formación de nubes convectivas.

* **`Proyecto - Precipitacion.ipynb`:** Uso de datos satelitales **GPCP** para cuantificar el déficit hídrico. Se analiza la serie temporal que muestra la falla crítica del ciclo de lluvias en febrero de 2023.

## 🧪 Metodología y Herramientas
* **Lenguaje:** Python (Pandas, Xarray, Matplotlib/Cartopy para mapas).
* **Variables:** TSM (Oceánica), SLP (Atmosférica) y Precipitación (Impacto final).
* **Referencia:** Comparación de datos actuales contra la climatología base 1981-2010.

## 📄 Documentación Completa
Para una explicación detallada de la física del evento, las gráficas resultantes y las conclusiones académicas, puedes revisar el informe técnico incluido en este repositorio:
👉 **`Climatologia_Sequia2022_Altiplano.pdf`**

---
