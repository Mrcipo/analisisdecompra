# Análisis de Precios de Sillas en MercadoLibre

Este proyecto realiza un análisis exploratorio de datos sobre precios de sillas ofrecidas en MercadoLibre Argentina. El objetivo es entender la distribución de precios, el impacto de la condición del producto (nuevo o usado), el tipo de vendedor y el efecto del envío gratis en el precio final.

## Estructura del proyecto

- `analisis_mercadolibre.ipynb`: Notebook principal con todo el análisis, limpieza de datos, visualizaciones y conclusiones.
- `sillas_mercado_sintetico.xlsx - Sheet1.csv`: Archivo de datos utilizado para el análisis.
- `.gitignore`: Configuración para ignorar archivos temporales, datos y configuraciones locales.
- `requirements.txt`: Lista de dependencias necesarias para reproducir el análisis.

## Requisitos

- Python 3.8 o superior
- Las librerías listadas en `requirements.txt`:
  - pandas
  - matplotlib
  - seaborn
  - jupyter

Puedes instalar las dependencias con:

```sh
pip install -r requirements.txt
```

## Ejecución

1. Abre el archivo `analisis_mercadolibre.ipynb` en Jupyter Notebook o Visual Studio Code.
2. Ejecuta las celdas en orden para cargar los datos, limpiarlos y visualizar los resultados.

## Principales análisis realizados

- **Distribución de precios**: Histograma y estadísticas descriptivas.
- **Precio promedio por condición**: Comparación entre productos nuevos y usados.
- **Impacto del envío gratis**: Análisis de si el envío gratis encarece el producto.
- **Recomendaciones**: Conclusiones basadas en los datos analizados.

## Resultados destacados

- Los productos nuevos tienen un precio promedio significativamente mayor que los usados.
- El envío gratis suele estar incorporado en el precio final del producto.
- Para obtener el mejor precio, conviene buscar productos usados sin envío gratis, siempre que el costo de envío no supere la diferencia promedio encontrada.

## Licencia

Este proyecto es solo para fines educativos y de análisis de datos.

---

Si tienes dudas o sugerencias, no dudes en abrir un
