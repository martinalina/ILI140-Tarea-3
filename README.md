# ILI140 | Entrega Taller Programación IA

**Grupo:** Syntax Terrors
**Integrantes:**
* Martina Tejo, 202104018 - 8
* Vicente Vizcarra, 202173036-2
* Joaquín Navarro, 202173125-3
* Lorna Mella, 202110037-7
* Matías Guerra Valles, 202173137-7

## 📌 Sobre el Proyecto
Este repositorio contiene la solución al desafío de análisis de datos de incendios forestales mediante técnicas de **Machine Learning no supervisado**.
Utilizamos el algoritmo **K-Means** para procesar datos históricos de la región del Maule (archivo `Incendios.xlsx`), agrupando los siniestros según ubicación geográfica, superficie afectada y condiciones climáticas para identificar patrones de riesgo y comportamiento.

## 📂 Archivos

* **`ClusterIncendios.ipynb`**: Jupyter Notebook principal que contiene todo el flujo de trabajo:
    * Carga y limpieza de datos.
    * Aplicación del algoritmo **K-Means**.
    * Evaluación del modelo mediante **Silhouette Score**.
    * Visualización de los clusters en mapas (usando coordenadas geográficas).
* **`Incendios.xlsx`**: Dataset original que contiene registros históricos de incendios con variables como:
    * Ubicación (Latitud, Longitud, Comuna, Provincia).
    * Tipo de vegetación afectada (Pino, Eucalipto, Matorral, etc.).
    * Condiciones climáticas (Temperatura, Humedad, Viento).
    * Cronología (Inicio, Detección, Extinción).

* **`ClusterIncendios.ipynb`**: Notebook con todo el código: carga de datos, limpieza, escalado, modelado (K-Means) y visualización de clusters.
* **`Incendios.xlsx`**: Dataset base utilizado para el análisis.

## 🚀 Ejecución
Para revisar el análisis, basta con ejecutar el notebook `ClusterIncendios.ipynb`. Asegúrate de tener instaladas las librerías `pandas`, `scikit-learn`, `matplotlib` y `seaborn`.
