# Image Captioning

## Overview

The project employs the **VGG16** architecture for feature extraction from images and uses an **LSTM** network for generating captions based on the extracted features. The goal is to create meaningful descriptions of images through an end-to-end learning approach.

## Requirements

To run this project, you will need the following Python packages:

- `numpy`
- `tensorflow`
- `tqdm`
- `pickle`

You can install the necessary packages using pip:

```bash
pip install numpy tensorflow tqdm
```

## Project Structure

- `ImageCaptioning.ipynb`: The main Jupyter notebook that contains the implementation of the image captioning model, including:
  - Importing libraries and necessary modules
  - Data preprocessing and feature extraction using VGG16
  - Building the LSTM model for caption generation
  - Training and evaluation of the model

## Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Shrinjita/Image-Captioning.git
   cd Image-Captioning
   ```

2. **Open the Jupyter Notebook**:
   Launch Jupyter Notebook and open `ImageCaptioning.ipynb`.

3. **Run the Notebook**:
   Follow the steps in the notebook to preprocess images, train the model, and generate captions.

## Model Architecture

The model architecture consists of:
- **CNN (VGG16)**: Used for feature extraction from images.
- **RNN (LSTM)**: Used for sequence prediction to generate captions.
- **Tokenizer**: To convert text captions into sequences for model input.

## Results

Once trained, the model can generate captions for new images, demonstrating the capability of deep learning in understanding and describing visual content.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [TensorFlow](https://www.tensorflow.org/) for providing the deep learning framework.
- [Keras](https://keras.io/) for high-level neural network APIs.
