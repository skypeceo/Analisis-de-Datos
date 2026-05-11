# Análisis de variables operativas como predictores en el volumen de traslados hospitalarios de alta complejidad

Este repositorio contiene el desarrollo del Segundo Avance del proyecto semestral para la asignatura de **Análisis de Datos e Inferencia Estadística** en la Facultad de Ingeniería de la Universidad del Desarrollo.

El objetivo principal es determinar qué factores de la gestión hospitalaria (como la ocupación de camas y el flujo de pacientes) explican de manera más robusta la necesidad de realizar traslados de alta complejidad en la red pública de salud chilena.

## Integrantes
* **Amalia Hermosilla**
* **Martin Olivares**

## Fuente de Datos
Los datos provienen de los **Registros Estadísticos Mensuales (REM-20)** gestionados por el Departamento de Estadísticas e Información de Salud (DEIS) del Ministerio de Salud de Chile. El dataset incluye indicadores operativos mensuales de establecimientos de salud de todo el país.

## Estructura del Proyecto
* `codigoEntrega2.ipynb`: Jupyter Notebook principal que contiene la limpieza de datos, el Análisis Exploratorio de Datos (EDA), el test de hipótesis y el modelo de regresión lineal múltiple.
* `indicadores_rem20_20260225.csv`: Dataset original con los indicadores de gestión hospitalaria.
* `README.md`: Instrucciones y documentación del proyecto.

## Requisitos y Reproducción del Análisis

### Clonar el repositorio
```bash
git clone (https://github.com/skypeceo/Analisis-de-Datos.git)
cd Analisis-de-datos

# Crear el entorno virtual con uv
uv venv

# Activar el entorno (Windows)
.venv\Scripts\activate
# Activar el entorno (macOS/Linux)
# source .venv/bin/activate

# Instalar las librerías necesarias
uv pip install pandas numpy matplotlib seaborn scipy statsmodels scikit-learn jupyter
