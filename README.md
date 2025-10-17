## Horse vs Human Image Classification (CNN)
The project builds CNN to classify images as 1 for Human and 0 for Horse. The goal is to explore image classification using deep learning and accurately classify images as either a horse or a human.

## Dataset

- Source: [TensorFlow Datasets - Horses or Humans](https://www.tensorflow.org/datasets/catalog/horses_or_humans)
- Classes:  
  - `Horse`  
  - `Human`
- Format: JPEG images, various sizes

## Project Objectives

- Build a CNN for binary image classification
- Apply normalization and data augmentation
- Train and evaluate the model
- Visualize training history and predictions

## Model Architecture

- Input: 300x300 RGB images ---> resized to 128x128x3
- Layers:
  - Conv2D + BatchNorm + ReLu + MaxPooling (2 blocks)
  - Flatten
  - Dropout
  - Dense layer
  - Output: Sigmoid activation for binary classification      
## Evaluation

| Metric     | Value     |
|------------|-----------|
| Accuracy   | ~0.91     |
| Loss       | ~0.33     |

> These results may vary depending on training duration, augmentation, and dataset split. 

## Visualizations

- Training accuracy 
- Confusion matrix 
