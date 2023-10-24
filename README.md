This project was done in Google colab


# Traffic Sign Recognition using Convolutional Neural Networks (CNN)

This project is a Python implementation of a Convolutional Neural Network (CNN) for traffic sign recognition. It includes the following components:

1. Data Preparation: Unzipping the dataset, loading images, and preprocessing.

2. Data Augmentation: Applying data augmentation techniques to increase the diversity of training data.

3. Convolutional Neural Network (CNN) Model: Building and training a CNN model for traffic sign recognition.

4. Model Evaluation: Testing the trained model on a test dataset and reporting accuracy.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook (optional)

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/traffic-sign-recognition.git
   cd traffic-sign-recognition
   ```

2. Install the required Python packages:(Not required if you are using google colab)
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Unzip the dataset:
Copy the zip file in main directory in your google drive. Connect your google drive with google colab.
   ```bash
   unzip /content/drive/MyDrive/test.zip
   ```

2. Run the Python script:

   ```bash
   python traffic_sign_recognition.py
   ```

3. The script will perform data preparation, model training, and evaluation.

4. Trained model weights will be saved as `my_model.h10`.

## Dataset

The dataset used in this project is located in the `test/traffic_Data/DATA` directory. It includes traffic sign images organized by class.

## Model Architecture

The CNN model used for traffic sign recognition has the following architecture:

- Input layer: (72, 72, 1) grayscale images
- Convolutional layers
- Max-pooling layers
- Fully connected layers
- Output layer with 58 classes (traffic sign types)

## Results

The model achieved an accuracy of 82.54% on the test dataset.

## License

-
## Acknowledgments

- Dataset source: https://www.kaggle.com/datasets/ahemateja19bec1025/traffic-sign-dataset-classification/data

## Author

- Muhammad Rufaid Peerzada

## Contact

For any inquiries or feedback, please contact rufaid2k21@gmail.com
```

