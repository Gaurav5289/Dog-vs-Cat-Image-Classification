# 🐱🐶 Cat vs Dog Classification Project
🎯 # Objectives
Classify images of cats and dogs using transfer learning.

Use MobileNetV2 from TensorFlow Hub as a feature extractor.

Build a real-time prediction system for single image classification.

# 🛠 Tools & Technologies 
Python: Model training, evaluation, and real-time inference.

TensorFlow, Keras, TensorFlow Hub: Deep learning and transfer learning.

OpenCV: Image resizing and preprocessing.

Kaggle API: Dataset access and automation.

# 🌟 Key Features
🧹 ## Data Preprocessing
Used 2,000 labeled images from Kaggle's Dogs vs Cats dataset.

Resized all images to 224×224 RGB format.

Labeled images and split into training and validation sets.

# 🧠 Model Training (Transfer Learning)

Used MobileNetV2 with frozen base layers as a feature extractor.

Trained a binary classifier on top using binary_crossentropy loss.

Achieved ~88% accuracy after 5 epochs.

# 🧪 Model Evaluation
Evaluated performance using validation accuracy.

Model generalized well on unseen images.

# 🔮 Real-Time Prediction
Built predict.py to classify a single image as a cat or dog.

Returns label with emoji output based on confidence.
