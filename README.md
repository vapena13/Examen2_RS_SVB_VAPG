# GPBoost para datos espaciales

Este repositorio contiene la reproducción y ampliación de un ejercicio de GPBoost aplicado a datos espaciales. La primera parte reproduce un experimento con datos simulados y proceso gaussiano espacial. La segunda parte aplica el enfoque a muestras Landsat de la cuenca del río Sinú exportadas desde Google Earth Engine.

## Contenido

- notebooks/01_reproduccion_gpboost.ipynb: reproducción del ejercicio base.
- notebooks/02_aplicacion_cuenca_sinu.ipynb: aplicación propia con datos Landsat.
- gee/exportar_muestras_landsat_sinu.js: script de Google Earth Engine.
- data/: datos de muestra.
- outputs/: figuras y tablas generadas.
- report/: informe técnico final.

## Ejecución

1. Abrir los notebooks en Google Colab.
2. Instalar dependencias desde la primera celda.
3. Ejecutar las celdas en orden.
4. Revisar métricas, mapas y tablas de comparación.