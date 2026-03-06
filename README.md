# 📊 TelecomX — Análisis de Evasión de Clientes (Churn)

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0+-150458?logo=pandas)
![Status](https://img.shields.io/badge/Status-Completado-brightgreen)
![Challenge](https://img.shields.io/badge/Alura-Challenge%202-orange)

---

## 📋 Descripción del Proyecto

TelecomX enfrenta una **tasa de evasión (churn) del 26.5%** sobre una base de 7,043 clientes. Este proyecto forma parte del **Challenge 2 de Data Science LATAM de Alura** y tiene como objetivo identificar los factores que llevan a la pérdida de clientes mediante un análisis exploratorio de datos completo.

A partir de los hallazgos, el equipo de Data Science podrá avanzar en la construcción de modelos predictivos y el negocio podrá desarrollar estrategias concretas para mejorar la retención.

### 🎯 Objetivos
- Extraer y procesar datos desde una API en formato JSON
- Aplicar el proceso ETL completo (Extracción, Transformación y Carga)
- Realizar un Análisis Exploratorio de Datos (EDA)
- Identificar patrones y factores de riesgo de churn
- Generar insights y recomendaciones estratégicas

---

## 🛠️ Tecnologías Utilizadas

| Herramienta | Uso |
|---|---|
| `Python 3.10+` | Lenguaje principal |
| `Pandas` | Manipulación y análisis de datos |
| `NumPy` | Operaciones numéricas |
| `Matplotlib` | Visualización de datos |
| `Seaborn` | Visualización estadística |
| `Requests` | Consumo de API |
| `Google Colab` | Entorno de ejecución |

---

## 🚀 Cómo Ejecutar el Proyecto

### Opción 1 — Google Colab (recomendado)

1. Abre [Google Colab](https://colab.research.google.com/)
2. Ve a **Archivo → Subir notebook**
3. Sube el archivo `TelecomX_LATAM.ipynb`
4. Ejecuta todas las celdas en orden con **Runtime → Run all**

> ✅ No requiere instalación adicional. Todas las librerías están disponibles en Colab.

### Opción 2 — Entorno local

```bash
# 1. Clona el repositorio
git clone https://github.com/jealpahu/TelecomX_LATAM.git
cd TelecomX_LATAM

# 2. Instala las dependencias
pip install pandas numpy matplotlib seaborn requests

# 3. Abre el notebook
jupyter notebook TelecomX_LATAM.ipynb
```

---

## 📁 Estructura de Archivos

```
TelecomX_LATAM/
│
├── TelecomX_LATAM.ipynb   # Notebook principal con todo el análisis
├── README.md              # Documentación del proyecto
└── img/                   # Capturas de los gráficos generados
    ├── churn_distribution.png
    ├── churn_by_contract.png
    ├── churn_by_categorical.png
    ├── churn_by_tenure.png
    └── correlation_matrix.png
```

---

## 📊 Capturas de Gráficos

> Los gráficos se generan automáticamente al ejecutar el notebook.

### Distribución de Churn
Visualización de la proporción de clientes que cancelaron vs. los que permanecieron.

### Churn por Tipo de Contrato
Comparación de tasas de evasión entre contratos mes a mes, anuales y bianuales.

### Churn por Variables Categóricas
Análisis de evasión por género, método de pago, servicio de internet, entre otros.

### Churn por Antigüedad
Segmentación de clientes en grupos de tenure para identificar la etapa crítica de riesgo.

### Matriz de Correlación
Relación entre variables numéricas y la probabilidad de churn.

---

## 💡 Principales Hallazgos

- 🔴 **Contrato mes a mes** → tasa de churn del ~42.7%, el factor más crítico
- 🔴 **Primeros 12 meses** → ~47% de evasión, etapa crítica de onboarding
- 🟠 **Cargo mensual elevado** → clientes que se van pagan ~$74/mes vs ~$61/mes los que permanecen
- 🟠 **Fibra óptica** → mayor churn que DSL a pesar de ser el servicio premium
- 🟡 **Cheque electrónico** → método de pago con mayor tasa de evasión
- 🟡 **Adultos mayores** → tasa de churn superior al promedio

---

## 📬 Autor y Contacto

**Jesús Alberto Palet Huerta**

[![GitHub](https://img.shields.io/badge/GitHub-jealpahu-181717?logo=github)](https://github.com/jealpahu)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-jealpahu-0077B5?logo=linkedin)](https://www.linkedin.com/in/jealpahu/)
[![Email](https://img.shields.io/badge/Email-jealpahu@gmail.com-D14836?logo=gmail)](mailto:jealpahu@gmail.com)

---

*Proyecto desarrollado como parte del Challenge 2 — Data Science LATAM | Alura* 🚀
