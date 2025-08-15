## Oxford-IIIT Classification: PyTorch Transfer Learning

Python project on utilizing transfer learning for classification.

### Overview
- Goal: Train an accurate classification model with a time/compute-efficient method.
- Stack: Python (PyTorch/torchvision), Jupyter notebook.

### Dataset
- Source: https://docs.pytorch.org/vision/main/generated/torchvision.datasets.OxfordIIITPet.html

### Methods
- Preprocessing: resize, normalize, and bilinear interpolation transformations.
- Training: freeze pretrained ResNet-34 weights, retrain classification layer.

### Results (highlights)
- Minimal training time/compute.
- Model accuracy 89%.
- Custom image 100% predictive success.

### How to Run
1) Run `pytorch_oxford_iiit_pet_dataset_computer_vision.ipynb`.

### Structure
- `custom_images/`: custom images for prediction
- `models/`: model state dictionaries

### Next
- Introduce new models; validate with TensorBoard/MLFlow/etc..
