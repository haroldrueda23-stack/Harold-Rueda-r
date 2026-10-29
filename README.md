# Machine Learning No Supervisado: Clustering y reducción de dimensionalidad

Trabajo individual de **Harold Steven Rueda Lara** — Universidad de Cundinamarca, Extensión Facatativá.

Implementación en Python (Scikit-learn, SciPy, NumPy, pandas y Matplotlib) de algoritmos de clustering y métodos de reducción de dimensionalidad sobre dos conjuntos de datos clásicos incluidos en `sklearn.datasets`: **Iris** (150 × 4) y **Wine** (178 × 13). No hace falta descargar ni subir archivos de datos.

## Contenido

| Archivo | Descripción |
|---|---|
| `01_clustering_kmeans_jerarquico.ipynb` | K-means (método del codo y silueta), clustering jerárquico aglomerativo (dendrograma y criterios de enlace), efecto de estandarizar. |
| `02_reduccion_dimensionalidad_pca_svd.ipynb` | PCA (varianza explicada, cargas), SVD (equivalencia con PCA, SVD truncado, reconstrucción) y clustering en el espacio reducido. |
| `figuras/` | Gráficas generadas por los notebooks (PNG). |
| `resultados/` | Métricas de cada ejecución en formato JSON. |
| `requirements.txt` | Dependencias para ejecutar localmente. |

## Cómo ejecutarlos en Google Colab

1. Entra a <https://colab.research.google.com> y elige **Archivo → Abrir cuaderno → GitHub**.
2. Pega la URL de este repositorio y selecciona el notebook.
3. Ejecuta todo con **Entorno de ejecución → Ejecutar todo**. Las librerías necesarias ya vienen instaladas en Colab.

Los notebooks crean las carpetas `figuras/` y `resultados/` y usan la semilla `42`, de modo que los resultados son reproducibles.

## Ejecución local

```bash
pip install -r requirements.txt
jupyter notebook
```
