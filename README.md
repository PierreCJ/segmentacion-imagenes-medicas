# Segmentación de Imágenes Médicas con MONAI

Este proyecto fue una implementación práctica de un modelo de segmentación de hígado usando la librería [MONAI](https://monai.io/), basado en un tutorial de YouTube.

- **Objetivo:** Entrenar un modelo para diferenciar regiones del hígado en imágenes médicas.  
- **Modelo:** Red neuronal U-Net  
- **Frameworks:** MONAI, PyTorch, Nibabel  
- **Resultados:** Se logró visualizar las máscaras reales vs. las predichas, junto a las métricas de evaluación por época.

⚠️ Este proyecto fue una reproducción educativa con fines de aprendizaje. Aunque no fue creado desde cero, me permitió profundizar en el uso de herramientas como MONAI, la manipulación de datos médicos (.nii.gz), y el entrenamiento de modelos segmentadores.

---

###  Ejemplos

- Máscaras vs predicción
<img width="951" height="340" alt="image" src="https://github.com/user-attachments/assets/493b6547-d45a-4e3c-8d09-995f228f08bf" />

- Curvas de DICE loss y metric DICE
<img width="782" height="403" alt="image" src="https://github.com/user-attachments/assets/7a135966-0cd3-4051-9294-ad0a6fb2befe" />

---

### Tecnologías

- Python
- PyTorch
- MONAI
- Matplotlib
- Numpy
- Jupyter Notebook
