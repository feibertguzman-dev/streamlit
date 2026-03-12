# 🛒 Amazon Sales Analysis Dashboard

![Streamlit](https://img.shields.io/badge/Streamlit-Dashboard-FF4B4B?logo=streamlit&logoColor=white)
![Python](https://img.shields.io/badge/Python-Data%20Analysis-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-150458?logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Charts-3F4F75?logo=plotly&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)

---

## 📊 Descripción

**Amazon Sales Analysis Dashboard** es una aplicación web interactiva desarrollada con **Python** y **Streamlit** para analizar datos de ventas simuladas de Amazon.

El dashboard permite explorar métricas clave, visualizar tendencias de ventas, analizar el rendimiento por categoría, región y productos, además de aplicar filtros interactivos y descargar los datos filtrados.

Este proyecto demuestra cómo construir **aplicaciones analíticas modernas con Python y visualización interactiva**.

---

## 🚀 Características

- 📊 **Métricas clave de negocio**
  - Ingresos totales
  - Ventas totales
  - Precio promedio
  - Categoría con mayor ingreso
  - Número de órdenes

- 📈 **Visualizaciones interactivas**
  - Ingresos por categoría
  - Distribución de cantidades vendidas
  - Tendencia mensual de ventas
  - Relación entre rating y revenue
  - Ingresos por región
  - Mapas geográficos
  - Top productos por ingresos

- 🔎 **Filtros interactivos**
  - Filtrar por categoría
  - Filtrar por región

- 📥 **Exportación de datos**
  - Descarga de dataset filtrado en CSV

---

## 🧰 Tecnologías utilizadas

- 🐍 Python  
- 📊 Pandas  
- 🔢 NumPy  
- 📈 Plotly Express  
- 📉 Plotly Graph Objects  
- 🌐 Streamlit  

---

## 📂 Estructura del proyecto

streamlit/
│
├── app.py
├── README.md
└── requirements.txt


---

## ⚙️ Instalación

### 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/feibertguzman-dev/streamlit.git
```
### 2️⃣ Entrar al proyecto
cd streamlit
### 3️⃣ Crear entorno virtual (opcional pero recomendado)
```bash
python -m venv venv
```
Activar entorno:

Windows
```bash
venv\Scripts\activate
```
Mac / Linux

source venv/bin/activate
### 4️⃣ Instalar dependencias
pip install -r requirements.txt
### ▶️ Ejecutar la aplicación
streamlit run app.py
Luego abre en tu navegador:

http://localhost:8501
### 📊 Funcionalidades del Dashboard
### 💰 Métricas principales
El dashboard calcula automáticamente:

Ingresos totales
Total de ventas
Precio promedio
Categoría líder
Número de órdenes

### 📈 Visualización por categorías
Incluye:

Gráfico de barras de ingresos
Gráfico de distribución de cantidades vendidas

### 📊 Tendencia temporal
Permite analizar:
Ingresos mensuales
Relación entre rating y revenue

### 🌍 Análisis geográfico
Visualizaciones como:
Ingresos por región
Mapa de ingresos global

### ⭐ Top productos
Se muestran:
Tabla con los 10 productos más rentables
Gráfico de barras comparativo

### 🔍 Filtros interactivos
El usuario puede filtrar por:

Categoría
Región
Las métricas y visualizaciones se actualizan dinámicamente.

### 📥 Descarga de datos
El sistema permite descargar el dataset filtrado en formato CSV.

### 📚 Dataset
El proyecto usa un dataset simulado generado con Python que incluye variables como:

date
product_category
product_name
sales
quantity
revenue
price
region
rating
Puedes reemplazarlo fácilmente por un CSV real de ventas de Amazon.

### 🧑‍💻 Autor
Feibert Guzmán

Investigador, docente y consultor en:
Inteligencia Artificial
Big Data
Visual Analytics
Innovación tecnológica

### 🌎 Propósito del proyecto
Este proyecto fue desarrollado como ejemplo educativo para análisis de datos y desarrollo de dashboards interactivos con Python, aplicable a:

Bootcamps de programación
Cursos de ciencia de datos
Talleres de visualización
Proyectos de analítica empresarial

### ⭐ Contribuciones
Las contribuciones son bienvenidas.

Puedes:
mejorar visualizaciones
integrar datasets reales
optimizar rendimiento
agregar modelos de machine learning

### 📜 Licencia
Este proyecto se distribuye con fines educativos y de investigación.

### 💡 “Los datos cuentan historias… el dashboard correcto permite escucharlas.”
