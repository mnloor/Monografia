# Aprendizaje profundo para el reconocimiento de polinizadores

![Tema](https://img.shields.io/badge/tema-aprendizaje%20profundo-blue)
![Área](https://img.shields.io/badge/área-visión%20por%20computador-green)
![Tipo](https://img.shields.io/badge/tipo-revisión%20sistemática-purple)
![Idioma](https://img.shields.io/badge/idioma-español-red)

Este repositorio contiene la monografía final y el póster académico titulados:

**“Aprendizaje profundo para el reconocimiento de polinizadores: una revisión sistemática de arquitecturas, métricas y factores de desempeño”**

El trabajo presenta una revisión sistemática de literatura sobre el uso de aprendizaje profundo para el reconocimiento de imágenes de polinizadores, con énfasis en arquitecturas de modelos, métricas de evaluación y factores técnicos asociados al rendimiento.

## Descripción del proyecto

Los polinizadores cumplen un papel esencial en la biodiversidad, la estabilidad de los ecosistemas y la seguridad alimentaria. Sin embargo, su monitoreo visual sigue siendo complejo debido a la similitud morfológica entre especies, los fondos naturales variables, los cambios de iluminación, el movimiento, la escala y la disponibilidad limitada de datos etiquetados.

Esta monografía analiza estudios científicos recientes sobre el reconocimiento automatizado de polinizadores mediante visión por computador y aprendizaje profundo. El análisis se organiza en torno a tres tareas principales:

- Clasificación de imágenes
- Detección de objetos
- Segmentación de imágenes

## Objetivo general

Caracterizar el estado del arte en el reconocimiento de imágenes de polinizadores mediante aprendizaje profundo, a partir de una revisión sistemática de estudios científicos publicados desde 2020.

## Preguntas de investigación

La revisión se guía por tres preguntas principales:

1. ¿Qué arquitecturas y tipos de modelos de aprendizaje profundo se utilizan con mayor frecuencia para el reconocimiento de imágenes de polinizadores?
2. ¿Qué métricas de evaluación se reportan con mayor recurrencia en la literatura?
3. ¿Qué factores técnicos se asocian con mejores niveles de desempeño en los modelos?

## Metodología

El estudio sigue una metodología de revisión sistemática basada en el enfoque PRISMA. La búsqueda se realizó en Scopus, aplicando criterios de inclusión y exclusión previamente definidos.

El corpus final estuvo conformado por **53 estudios** publicados desde 2020, centrados en tareas de clasificación, detección y segmentación de imágenes de polinizadores.

## Principales resultados

Los resultados muestran que la detección fue la tarea más frecuente dentro de los estudios analizados, seguida por la clasificación y, en menor medida, la segmentación.

Las arquitecturas más reportadas fueron:

- YOLO
- ResNet
- MobileNet
- EfficientNet
- Faster R-CNN
- Mask R-CNN

Las métricas de evaluación más frecuentes fueron:

- Exactitud
- Precisión
- Sensibilidad
- Medida F1
- mAP
- IoU
- FPS
- Dice

También se identificaron factores técnicos asociados al rendimiento de los modelos, especialmente:

- Aumento de datos
- Aprendizaje por transferencia
- Ajuste fino
- Métodos de optimización

## Estructura del repositorio

```text
.
├── Monografia_MelaniLoor_final.pdf
├── Poster_MelaniLoor_segunda_version.pdf
├── README.md
└── LICENSE
