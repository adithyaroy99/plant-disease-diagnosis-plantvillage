# AI-Driven Plant Disease Diagnosis (PlantVillage)

Deep learning image classification project to detect plant leaf diseases using a 10-class subset of the PlantVillage dataset.

## What I did
- Trained a baseline custom CNN
- Applied transfer learning using MobileNetV2 and ResNet50 (ImageNet weights, frozen backbones)
- Evaluated models using accuracy, macro precision/recall/F1, and confusion matrices
- Benchmarked deployment factors: parameter count, saved model size, and inference latency (ms/image)

## Key result (summary)
Transfer learning models achieved ~97.6% test accuracy with macro F1 > 0.96, and MobileNetV2 provided the best accuracy–efficiency balance.

## Tech stack
Python, TensorFlow/Keras, tf.data, NumPy, Matplotlib (Google Colab / Jupyter)
