# ResidenciaVerano_ULE-Santander

## 1. Descripción
Este repositorio contiene los scripts necesarios para entrenar, evaluar y comparar diversos modelos de visión por computador (familias **YOLO**, **LeYOLO** y **RT-DETR**).

El objetivo principal de este trabajo es analizar el rendimiento y la velocidad de inferencia de estas arquitecturas sobre un dataset de **imágenes de especies vegetales y objetos agrícolas**, accesible a través de [Zenodo](https://doi.org/10.5281/zenodo.22544419).


## 2. Resultados obtenidos


Los resultados obtenidos tras la ejecucion de los diferentes modelos utilizando el conjunto de imágenes https://doi.org/10.5281/zenodo.22544419: 

| Modelo | Precision | Recall | mAP-50 | mAP-50:95 | FPS |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **YOLOv8l** | 0.733 | 0.731 | 0.750 | 0.485 | 32.68 |
| **YOLOv9m** | 0.736 | 0.736 | 0.751 | 0.487 | 41.15 |
| **YOLOv11m** | 0.754 | 0.737 | 0.759 | 0.492 | 44.44 |
| **YOLOv12l** | - | - | - | - | - |
| **YOLOv26m** | 0.757 | 0.724 | 0.749 | 0.488 | 53.19 |
| **LeYOLOm** | - | - | - | - | - |
| **LeYOLOm Custom** | - | - | - | - | - |
| **RT-DETRI** | - | - | - | - | - |