# 🐱 Generador de Imágenes HD de Gatos con Redes GAN
Estudiantes:

- Miguel Angel Naranjo Joya - 20201020037
- Handersson Felipe Pacheco Espitia - 20202020053
- Juan David Martínez Monroy - 20201020043
- Laura Andrea Riobueno Rincón - 20201020040

Este proyecto implementa una Red Generativa Antagónica (GAN) entrenada para generar imágenes sintéticas de gatos en alta definición (HD), utilizando PyTorch como framework principal.

## 🎯 Objetivo

Desarrollar una arquitectura GAN capaz de aprender la distribución de imágenes reales de gatos y generar nuevas imágenes realistas en resolución HD. El enfoque es completamente basado en visión por computador y aprendizaje profundo.

## 📁 Estructura del proyecto

- `GeneradorGatos.ipynb`: Notebook principal donde se desarrolla, entrena y evalúa la GAN.
- `datasets/`: Carpeta sugerida donde se deberían almacenar las imágenes reales de gatos usadas para entrenamiento.
- `salidas/`: Carpeta donde se guardan las imágenes generadas por la GAN (no incluida por defecto en este repo).
- `README.md`: Este archivo.
- `requirements.txt`: (opcional) Archivo con las dependencias del proyecto.

## ⚙️ Tecnologías utilizadas

- Python 3.x
- PyTorch
- NumPy
- Matplotlib
- PIL / torchvision
- Google Colab (opcional)

🧠 Arquitectura
La GAN se compone de dos redes:

Generador: Toma un vector latente aleatorio (ruido) y genera una imagen HD (por ejemplo, 128x128 o superior).

Discriminador: Evalúa si una imagen es real o generada.

Ambas redes son entrenadas de forma simultánea y en oposición, siguiendo la estrategia típica de entrenamiento de GANs.

🏁 Instrucciones de uso
1. Clona el repositorio:
- git clone https://github.com/tu-usuario/generador-gatos-GAN.git
- cd generador-gatos-GAN
2. Instala las dependencias:
- pip install -r requirements.txt
3. Asegúrate de tener imágenes de gatos en la carpeta datasets/.
4. Ejecuta el notebook GeneradorGatos.ipynb en Jupyter o Google Colab.

📦 Dataset sugerido
Puedes usar datasets públicos como:
Kaggle Cats Dataset
Oxford Pets Dataset

📌 Consideraciones
El entrenamiento puede tomar varias horas si se realiza sin GPU.
Se recomienda usar Google Colab o entornos con CUDA para acelerar el proceso.
