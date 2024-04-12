```
# COVID-19 Diagnosis from Chest X-Ray Images using CNNs

## Project Overview
This project utilizes Convolutional Neural Networks (CNNs) implemented with TensorFlow to diagnose COVID-19 from chest X-ray images. The model achieves a remarkable 98% accuracy by leveraging advanced machine learning techniques and image processing methods.

### Key Features
- **High Accuracy**: Achieved 98% accuracy in identifying COVID-19 from chest X-ray images.
- **Robustness**: Improved robustness of the model by expanding the training dataset's diversity through advanced data augmentation techniques using `ImageDataGenerator`.
- **Generalization**: Enhanced generalization capabilities of the model by incorporating Dropout, Learning Rate Scheduling, and Early Stopping mechanisms, effectively preventing overfitting.

## Installation

### Prerequisites
- Python 3.6 or higher
- pip
- virtualenv (optional but recommended)

### Setting Up a Virtual Environment
To create and activate a virtual environment, follow these steps:

#### For Windows:
```bash
python -m venv env
env\\Scripts\\activate
```

#### For macOS and Linux:
```bash
python3 -m venv env
source env/bin/activate
```

### Installing Dependencies
After setting up and activating the virtual environment, install the required packages using:

```bash
pip install -r requirements.txt
```
```
