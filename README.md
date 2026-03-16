# 🧠 Detección de Enfermedades Retinianas con Deep Learning
**Autor:** Luis Miguel Alegre Nontol  
**Curso:** Deep Learning — PUCP  

## 📌 Descripción del Proyecto
Clasificación automática de retinopatía diabética en imágenes del fondo de ojo.
Se clasifica la severidad en 5 niveles: desde No DR (0) hasta Proliferative DR (4).

## 📂 Dataset
- **Nombre:** APTOS 2019 Blindness Detection
- **Fuente:** Kaggle
- **Imágenes:** Fotografías del fondo de ojo (retina)

## 🧪 Pipeline Completo
1. ✅ Data Retrieval — Descarga desde Kaggle
2. ✅ Data Processing & Wrangling — EDA, limpieza, split estratificado
3. ✅ Feature Extraction — Transfer Learning con EfficientNetB4
4. ✅ Feature Scaling — Class Weighting para desbalance de clases
5. ✅ Modeling — Entrenamiento en 2 fases (feature extraction + fine-tuning)

## 🏗️ Modelo
- **Arquitectura:** EfficientNetB4 (preentrenado en ImageNet)
- **Estrategia:** Feature extraction → Fine-tuning
- **Preprocesamiento:** Ben Graham preprocessing

## ▶️ Cómo ejecutar
1. Abrir `notebooks/final_project.ipynb` en Google Colab
2. Ejecutar todas las celdas de inicio a fin
3. Se requiere cuenta de Kaggle para descargar el dataset

## 📁 Estructura del Repositorio
```
├── data/           # Datos del proyecto
├── figures/        # Gráficas y visualizaciones
├── notebooks/      # Notebook principal
├── report/         # Reporte final
├── results/        # Resultados del modelo
└── src/            # Código fuente
