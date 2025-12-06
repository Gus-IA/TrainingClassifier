# Clasificador de Imágenes en CIFAR-10 con PyTorch

Este proyecto entrena una **red neuronal convolucional (CNN)** sencilla sobre el dataset **CIFAR-10** usando **PyTorch**, con aceleración en **GPU (CUDA)** cuando está disponible.

El código sigue el flujo completo de un proyecto de Deep Learning:

1. Cargar y transformar un dataset.
2. Crear dataloaders de entrenamiento y prueba.
3. Definir una CNN tipo *LeNet*.
4. Entrenar el modelo en GPU.
5. Guardar y cargar pesos.
6. Hacer inferencia con imágenes reales.
7. Evaluar la precisión total y por clase.

---

🧩 Requisitos

Antes de ejecutar el script, instala las dependencias:

pip install -r requirements.txt

🧑‍💻 Autor

Desarrollado por Gus como parte de su aprendizaje en Python e IA.
