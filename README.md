# Preprocesamiento de imágenes con Python y OpenCV

## 1. Descripción del proyecto

Este proyecto desarrolla diferentes técnicas de preprocesamiento digital de imágenes mediante Python y las librerías OpenCV, NumPy y Matplotlib.

Se utiliza la imagen Lena.png como referencia para implementar y analizar transformaciones de intensidad, operaciones geométricas y técnicas de reducción de ruido.

## 2. Objetivos

- Analizar la distribución de intensidades mediante histogramas.
- Aplicar transformaciones de intensidad a una imagen.
- Implementar la transformación negativa y la umbralización.
- Mejorar el contraste mediante ecualización del histograma.
- Reducir el ruido utilizando filtros espaciales.
- Aplicar transformaciones geométricas mediante rotación.

## 3. Estructura del proyecto

```text
preprocesamiento-imagenes/
├── data/
│   └── Lena.png
├── resultados/
│   ├── 02_rotada.png
│   ├── 03_negativo.png
│   ├── 04_umbralizada.png
│   ├── 05_ecualizada.png
│   ├── 06_filtro_gaussiano.png
│   └── 07_filtro_mediano.png
├── preprocesamiento.ipynb
├── requirements.txt
└── README.md
```

## 4. Requisitos

- Python 3.13 o compatible.
- Jupyter Notebook.
- OpenCV.
- NumPy.
- Matplotlib.

## 5. Instalación de dependencias

Desde la terminal, ejecutar:

```bash
pip install -r requirements.txt
```

## 6. Ejecución

1. Descargar o clonar el repositorio.
2. Abrir la carpeta del proyecto en Visual Studio Code.
3. Abrir `preprocesamiento.ipynb`.
4. Seleccionar un entorno de Python que tenga instaladas las dependencias.
5. Ejecutar las celdas del Notebook en orden.

La imagen original debe estar ubicada en la carpeta `data/`.

## 7. Técnicas implementadas

- Carga y caracterización de imágenes.
- Conversión a escala de grises.
- Cálculo y análisis del histograma.
- Determinación del rango dinámico.
- Transformación negativa.
- Umbralización binaria.
- Ecualización del histograma.
- Generación de ruido gaussiano.
- Filtrado gaussiano y mediano.
- Rotación de 45 grados.

## 8. Resultados

Los resultados de las transformaciones se almacenan en la carpeta `resultados/` y se documentan en el Notebook.

## 9. Conclusión

El proyecto permite comprender y aplicar técnicas fundamentales de preprocesamiento de imágenes, identificando cómo las transformaciones de intensidad, los filtros espaciales y las operaciones geométricas modifican la información visual. Estas técnicas constituyen una etapa importante en los sistemas de percepción y visión artificial aplicados a la robótica.