# Tamil Optical Character Recognition using Deep learning
## Project Overview
This project develops a deep learning model for Optical Character Recognition (OCR) to identify Tamil characters from printed texts. It leverages a custom-built convolutional neural network (CNN) to process images and recognize characters, addressing the unique challenges posed by the Tamil script's complexity.

## Key Features
- **Custom CNN Architecture**: Tailored network to handle the intricacies of Tamil characters.
- **Reduced Character Classes**: Simplifies the recognition process by reducing the classes to 108.
- **Preprocessing and Training**: Detailed steps for image preprocessing, model training, and evaluation.
- **Real-Time OCR Capability**: Designed to handle real-time image processing and character recognition.
- **Image Preprocessing**: Automates the conversion of images to grayscale, resizes them, and extracts labels for training.
- **Robust CNN Architecture**: Employs Conv2D, MaxPooling2D, Flatten, and Dense layers to effectively recognize Tamil characters.
- **Training and Evaluation**: Includes scripts for training the model on a curated dataset and evaluating its accuracy on a separate test set.


## Installation
Ensure the following are installed:
- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib
- OpenCV

## Usage
1. Clone the repository.
2. Install dependencies.
3. Run the script `tamil_ocr.py` to train the model and perform OCR on new images.

## Contributing
Contributions are welcome! Please feel free to submit pull requests, report issues, or suggest improvements.

