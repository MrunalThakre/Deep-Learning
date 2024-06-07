
## Data Preprocessing
- Load and preprocess images using `ImageDataGenerator` from TensorFlow Keras.
- Apply data augmentation techniques to enhance the training dataset.
- Normalize pixel values to range [0, 1].

## Model Design
- Define a CNN architecture with several convolutional and pooling layers.
- Add dropout layers to prevent overfitting.
- Compile the model using the Adam optimizer and binary cross-entropy loss function.

## Model Training
- Train the model using the training and validation data generators.
- Use early stopping and model checkpoints to save the best model.

## Model Evaluation
- Evaluate the model on the test set.
- Plot training history to visualize loss and accuracy over epochs.

## Requirements
- Python 3.x
- TensorFlow 2.x
- Keras
- numpy
- matplotlib

## How to Run
1. Clone the repository.
2. Download and organize the dataset as described.
3. Install the required packages.
4. Run the script to train and evaluate the model.

```bash
git clone <repository-url>
cd <repository-directory>
pip install -r requirements.txt
python train_model.py
