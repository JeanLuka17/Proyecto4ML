# Proyecto 4 — Clasificación de Imágenes CIFAR-10

Clasificación de imágenes usando CNN con Transfer Learning (MobileNetV2),
comparado contra MLP baseline y KNN, más análisis no supervisado con
K-Means y GMM sobre el espacio latente.

## Resultados

| Modelo                  | Accuracy |
|-------------------------|----------|
| CNN (Transfer Learning) | 60.7%    |
| KNN sobre features CNN  | 59.1%    |
| MLP Baseline            | 9.8%     |

## Tecnologías

- Python 3.12 / Google Colab
- TensorFlow 2.x / Keras
- scikit-learn
- Manim (animación)

## Cómo ejecutar

1. Abre `Proyecto4.ipynb` en Google Colab
2. Ejecuta todas las celdas en orden
3. Requiere conexión a internet para descargar los pesos de MobileNetV2

## Video explicativo
[Ver presentación](https://github.com/JeanLuka17/Proyecto4ML/blob/main/proyecto4_final.mp4)
