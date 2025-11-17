# 📊 Identificación de Drivers de Ventas en Estrategias de Marketing
**EDA + Regresión Lineal | Proyecto de Análisis Predictivo**

![Status](https://img.shields.io/badge/EDA-Complete-brightgreen)
![Model](https://img.shields.io/badge/Model-LinearRegression-blue)
![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Last Update](https://img.shields.io/badge/Last_Update-2025-lightgrey)

---

## 🧠 Sobre el Proyecto

Este proyecto analiza cómo diferentes inversiones en marketing se relacionan con las ventas, con el objetivo de **identificar el canal con mayor impacto comercial**.  
El análisis está diseñado para un entorno profesional, siguiendo un enfoque orientado a decisiones.

El trabajo incluye:

- Exploración visual del dataset  
- Identificación de patrones iniciales entre medios y ventas  
- Construcción de un modelo de regresión lineal  
- Validación de supuestos estadísticos  
- Documentación ejecutiva en formato PACE y One-Pager  

El modelo final identifica un medio con **impacto fuerte, directo y estadísticamente significativo**, explicando más del **75%** de la variación en ventas.

---

## 🔑 Insight Clave

> **Un canal publicitario destaca como el principal predictor de ventas, mostrando una relación lineal sólida y consistente.**

Esto respalda decisiones estratégicas para redistribuir el presupuesto hacia medios más rentables.

---

## 📊 Principales Resultados

- **R² = 0.757** → Alta capacidad explicativa del modelo.  
- El canal más influyente presenta una **relación lineal positiva clara** con las ventas.  
- Se validan todos los supuestos: linealidad, normalidad, independencia y homocedasticidad.  
- Otros medios presentan correlaciones menores o más dispersas.

---

## 🗂️ Estructura del Repositorio

```
Marketing-Sales-Analysis/
│
├── data/
│   └── marketing_sales_data.csv
│
├── notebooks/
│   └── marketing_sales_analysis.ipynb
│
├── reports/
│   ├── marketing_sales_analysis.pdf
│   ├── PACE-Marketing_Sales.pdf
│   └── Resumen_Ejecutivo.pdf
│
├── images/
│   ├── dispersion_por_pares.png
│   ├── grafico_q-q.png
│   ├── histograma_de_residuos.png
│   ├── linea_de_regresion.png
│   └── valores_ajustados_vs_residuos.png
│
├── requirements.txt
│
└── README.md
```

---

## 📄 Documentos del Proyecto

| Tipo | Archivo |
|------|---------|
| 📘 Notebook interactivo | notebooks/marketing_sales_analysis.ipynb |
| 📄 PACE (Metodología) | reports/PACE-Marketing_Sales.pdf |
| 📊 Resumen Ejecutivo | reports/Resumen_Ejecutivo.pdf |
| 🗂 Dataset | data/marketing_sales_data.csv |

---

## 🔧 Cómo Ejecutar el Proyecto

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/fcamasca/Marketing-Sales-Analysis.git
   ```
2. **Crear un entorno virtual (opcional)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
   ```
3. **Instalar dependencias**
   ```bash
   pip install -r requirements.txt
   ```
4. **Abrir el notebook**
   ```bash
   jupyter notebook notebooks/marketing_sales_analysis.ipynb
   ```

---

## 🧪 Tecnologías y Librerías

- Python 3  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Statsmodels  
- Jupyter Notebook  

Requisitos completos en  
📦 **requirements.txt**

---

## 📈 Visualizaciones

### 🔹 Pairplot — Relaciones iniciales entre variables de marketing  
<img src="images/dispersion_por_pares.png" width="450px">

**Explora patrones de correlación entre medios y ventas.**

---

### 🔹 Regresión Lineal — Canal con mayor impacto  
<img src="images/linea_de_regresion.png" width="450px">

**Relación lineal fuerte, estable y estadísticamente significativa.**

---

## 🚀 Próximos Pasos

- Ampliar el análisis hacia un modelo multivariable.  
- Evaluar interacciones entre canales publicitarios.  
- Analizar sensibilidad ante incrementos presupuestales.  
- Probar modelos no lineales como Random Forest o GAM.  
- Construir un dashboard interactivo para simulación de inversiones.  

---

## 📬 Autor

**Frankz Camasca**  
Analista de Datos | Data Analytics & Predictive Modeling  

[![GitHub](https://img.shields.io/badge/GitHub-%40fcamasca-black?logo=github)](https://github.com/fcamasca)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Frankz%20Camasca-blue?logo=linkedin)](https://www.linkedin.com/in/frankz-william-camasca-castillo-b63a0094)

---

## 📄 Licencia
Este proyecto es de uso libre para fines educativos y demostración profesional.
