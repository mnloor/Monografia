# Aprendizaje profundo para el reconocimiento de polinizadores

Este repositorio contiene la monografía final, el póster académico y los archivos fuente en LaTeX del trabajo titulado:

**“Aprendizaje profundo para el reconocimiento de polinizadores: una revisión sistemática de arquitecturas, métricas y factores de desempeño”**

El trabajo presenta una revisión sistemática de literatura sobre el uso de aprendizaje profundo para el reconocimiento de imágenes de polinizadores, con énfasis en arquitecturas de modelos, métricas de evaluación y factores técnicos asociados al rendimiento.

## Descripción del proyecto

Los polinizadores cumplen un papel esencial en la biodiversidad, la estabilidad de los ecosistemas y la seguridad alimentaria. Sin embargo, su monitoreo visual sigue siendo complejo debido a la similitud morfológica entre especies, los fondos naturales variables, los cambios de iluminación, el movimiento, la escala y la disponibilidad limitada de datos etiquetados.

Esta monografía analiza estudios científicos recientes sobre el reconocimiento automatizado de polinizadores mediante visión por computador y aprendizaje profundo. El análisis se organiza en torno a tres tareas principales:

* Clasificación de imágenes
* Detección de objetos
* Segmentación de imágenes

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

* YOLO
* ResNet
* MobileNet
* EfficientNet
* Faster R-CNN
* Mask R-CNN

Las métricas de evaluación más frecuentes fueron:

* Exactitud
* Precisión
* Sensibilidad
* Medida F1
* mAP
* IoU
* FPS
* Dice

También se identificaron factores técnicos asociados al rendimiento de los modelos, especialmente:

* Aumento de datos
* Aprendizaje por transferencia
* Ajuste fino
* Métodos de optimización

## Estructura del repositorio

```text
.
├── Monografia.pdf
├── Poster.pdf
├── README.md
├── LICENSE
└── overleaf-source-monografia
└── overleaf-source-poster
```

## Documentos incluidos

### Monografía

La monografía contiene el desarrollo completo del trabajo, incluyendo fundamento teórico, metodología, resultados, discusión, conclusiones y referencias.

### Póster académico

El póster resume los elementos principales de la investigación: objetivo, metodología, preguntas de investigación, resultados y conclusiones.

### Código fuente en LaTeX

La monografía fue desarrollada en Overleaf. Los archivos fuente de LaTeX se encuentran en la carpeta `overleaf-source/`, incluyendo el archivo principal `.tex`, la bibliografía y los recursos gráficos necesarios para compilar el documento.

## Cómo citar este trabajo

Si utilizas o referencias este trabajo, puedes citarlo de la siguiente manera:

```text
Loor, M. (2026). Aprendizaje profundo para el reconocimiento de polinizadores: una revisión sistemática de arquitecturas, métricas y factores de desempeño. Pontificia Universidad Católica del Ecuador.
```

## Autora

**Melani Nayely Loor Pérez**\\
Pontificia Universidad Católica del Ecuador\\
Facultad de Ciencias Exactas, Naturales y Ambientales\\
Carrera de Ciencia de Datos

## Tutor

**Andrés Esteban Merino Toapanta**

## Palabras clave

`aprendizaje profundo` · `polinizadores` · `visión por computador` · `reconocimiento de imágenes` · `revisión sistemática` · `YOLO` · `CNN` · `detección de objetos`

## Licencia

Este trabajo se comparte con fines académicos y no comerciales. Para más detalles, revisar el archivo `LICENSE`.
