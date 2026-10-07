# 🚦 Movilidad Urbana & Economía Internacional — TripleTen (Sprint 5)

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter_Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)](https://colab.research.google.com/)

## 🎯 Objetivo del Proyecto
Evaluar la relación multidimensional entre los indicadores de **movilidad urbana** (congestión, retrasos y tiempos de viaje) y la **productividad socioeconómica** (PIB per cápita, desempleo, población y calidad del aire PM2.5) a nivel internacional, con el fin de identificar patrones clave para la inversión en infraestructura de transporte.

---

## 🛠️ Tech Stack & Fuentes de Datos
* **Fuentes de Datos (2024):**
  * **TomTom Traffic Index:** Métricas de congestión, tiempos de viaje y retrasos viales.
  * **OECD Cities:** Indicadores macroeconómicos, demográficos y de calidad ambiental.
* **Herramientas & Librerías:**
  * **Python (Pandas, NumPy):** Limpieza, ingeniería de variables, fusión de datasets y transformación estructurada.
  * **Matplotlib:** Exploración gráfica de distribuciones y dispersión.

---

## 📊 Principales Hallazgos & Resultados

| Dimensión Analizada | Indicadores Clave | Patrón Identificado |
| :--- | :--- | :--- |
| **Tráfico & Movilidad** | Retrasos, Tiempos de viaje, Longitud de congestión | Variabilidad crítica en la eficiencia del transporte entre metrópolis internacionales. |
| **Contexto Urbano** | PIB per cápita, Desempleo, Calidad del aire (PM2.5) | Brecha estructural entre la capacidad económica de una ciudad y sus niveles de congestión. |
| **Integración de Datos** | Dataset consolidado de 2024 | Revela patrones de infraestructura invisibles al estudiar economía y tráfico de forma aislada. |

---

## 💡 Conclusiones del Negocio & Habilidades Demostradas

### 📌 Impacto en Estrategia y Políticas Públicas
* **Criterio de Inversión en Infraestructura:** Demuestra que un alto PIB per cápita no necesariamente garantiza un tráfico eficiente, permitiendo priorizar recursos en ciudades donde el costo del retraso vial afecta la productividad local.
* **Visión Holística del Entorno Urbano:** Combina variables ambientales (PM2.5) con rendimiento económico para soportar decisiones orientadas a la sostenibilidad y reducción del huella de carbono en logística urbana.

### 🧠 Capacidades Técnicas Demostradas
* **Integración y Modelado de Múltiples Fuentes:** Habilidad para homogenizar, cruzar y limpiar estructuras de datos complejas provenientes de dos APIs/organizaciones internacionales distintas (TomTom + OCDE).
* **Análisis Exploratorio Orientado a Diagnósticos:** Capacidad para transformar datos crudos en un dataset consolidado (`iadb_mobility_economy_2024_clean.csv`) listo para ingesta en tableros de BI o modelos predictivos.

---

## 📁 Estructura del Repositorio

```text
├── notebooks/
│   └── S5_ladb_mobility_economy_project_student(1).ipynb  # Cuaderno principal de EDA y ETL
├── ladb_mobility_economy_2024_clean.csv                   # Dataset final consolidado y limpio
└── README.md                                              # Documentación del proyecto
