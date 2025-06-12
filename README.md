📚 Análisis de la cobertura neta, repitencia y deserción en Colombia — Data 360
Este proyecto analiza los indicadores clave del sistema educativo colombiano, con énfasis en cobertura neta, repitencia y deserción escolar. A partir de datos de la última década, se estudian las tendencias, relaciones y proyecciones de estos indicadores, con el objetivo de identificar inequidades educativas dentro de los departamentos y anticipar su comportamiento en 2024.

🎯 Objetivo
Evaluar si existen brechas significativas en cobertura y calidad educativa entre municipios de un mismo departamento, considerando variables como:
-Cobertura neta
-Repitencia escolar
-Deserción escolar
Además, se analiza la evolución temporal, las correlaciones entre indicadores y se realiza una predicción del comportamiento para el año 2024 con fines de planeación y política educativa.

🧪 Dataset
Fuente principal: Datos_Cleaned.csv
Cobertura temporal: 2013–2023
Unidades de análisis: Municipio, Departamento, Año
Variables clave
AÑO
DEPARTAMENTO
MUNICIPIO
COBERTURA (porcentaje)
REPITENCIA (porcentaje)
DESERCIÓN (porcentaje)

🧰 Herramientas utilizadas
Python 3.13.4
Pandas (manejo de datos)
Matplotlib & Seaborn (visualización)
Scikit-learn (modelado predictivo)
GeoPandas / Folium (visualización geográfica)
Jupyter Notebook

📁 Estructura del proyecto
bash
Copiar
Editar
📦 educacion_inequidad
│
├── Datos_Cleaned.csv             # Datos consolidados y limpios
├── limpieza.ipynb                # Proceso de limpieza y transformación de datos
├── Hipotesis.ipynb               # Análisis exploratorio, correlación y predicción
├── colombia_departamentos.geojson  # Mapa geográfico para visualización por regiones
├── README.md                     # Documentación del proyecto
⚙️ Cómo ejecutar el análisis
Clona el repositorio:

Instala las dependencias necesarias:

pip install pandas matplotlib seaborn scikit-learn geopandas folium

Abre el notebook principal:

jupyter notebook Hipotesis.ipynb

📈 Resultados esperados
-Evolución histórica de cobertura, repitencia y deserción escolar por municipio.
-Correlaciones entre los indicadores clave.
-Proyección de los indicadores para 2024 mediante modelos de regresión.
Visualizaciones geoespaciales por municipios y departamentos.

✨ Autoras
Jennifer Mejia
Milena Pardo
Maria Cedeño
Yuly Castro

Equipo Data 360 — Datos con visión e impacto social
