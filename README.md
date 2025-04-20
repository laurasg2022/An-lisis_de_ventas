# 📊 Análisis Geográfico de Ventas por Tienda

Este proyecto tiene como objetivo explorar y analizar los datos de ventas de cuatro tiendas distintas, considerando tanto variables comerciales como geográficas. Utilizando Python y herramientas de visualización de datos, se identifican patrones de rendimiento, distribución espacial de ventas y se destacan oportunidades de mejora.

## 📌 Objetivos del Análisis

- Evaluar el desempeño individual de cada tienda.
- Analizar la distribución geográfica de las ventas.
- Detectar zonas con alta concentración de ventas mediante mapas de calor.
- Generar visualizaciones que apoyen la toma de decisiones estratégicas.

---

## 🛠️ Tecnologías y Librerías Usadas

- Python 3.x
- pandas
- matplotlib
- seaborn
- folium
- Google Colab (entorno recomendado)

---

## 🧱 Estructura del Proyecto


---

## ⚙️ Instalación y Dependencias

Este proyecto se recomienda correr en [Google Colab](https://colab.research.google.com/), donde no se requiere instalación adicional. Si deseas ejecutarlo localmente:

1. Crea un entorno virtual (opcional pero recomendado):

```bash
python -m venv env
source env/bin/activate  # En Windows: env\Scripts\activate
```
2. Instala las dependencias necesarias:
```bash
   pip install pandas matplotlib seaborn folium
```
## 🚀 ¿Cómo Ejecutar el Proyecto?

1. Abre el archivo `notebook.ipynb` en Google Colab o Jupyter.
2. Ejecuta cada celda en orden.
3. Asegúrate de tener cargados los cuatro DataFrames: `tienda1`, `tienda2`, `tienda3`, `tienda4`.

### 📈 El análisis genera:

- Un gráfico de dispersión de ventas geolocalizadas (`distribucion_geografica.png`).
- Un mapa de calor interactivo con Folium para explorar zonas de alta densidad de ventas.

---

## 📊 Resultados Esperados

- Visualización clara del rendimiento de cada tienda.
- Identificación de zonas calientes de ventas.
- Detección de posibles mejoras logísticas o comerciales a partir de los patrones geográficos.

---

## 🧩 Posibles Problemas y Soluciones

| Problema                                 | Solución                                                                 |
|------------------------------------------|--------------------------------------------------------------------------|
| `FileNotFoundError` al guardar imagen    | Usar solo el nombre del archivo sin ruta (`distribucion_geografica.png`) si estás en Colab. |
| Problemas con visualización de mapas     | Asegurarse de ejecutar en un entorno que soporte Folium (Colab o Jupyter). |
| Columnas faltantes (`lat`, `lon`)        | Verificar que todos los DataFrames contengan datos geográficos.          |

---

## 👩‍💻 Autora

**Laura Gutierrez**  
Licenciada en Logística | Analista de Datos  
📍 Necochea, Buenos Aires, Argentina  
💼 Proyecto académico para análisis de datos georreferenciados


