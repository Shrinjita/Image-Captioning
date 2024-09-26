## Dataset
The model is trained on the **Flickr8k dataset**, which contains 8,000 images, each annotated with five different captions. This diverse set of images provides a rich resource for training the captioning model.

## Features
- **Deep Learning Architecture**: Utilizes CNNs and RNNs to process images and generate captions.
- **Comprehensive Walkthrough**: The Jupyter notebook includes a step-by-step explanation of the model architecture, data preprocessing, training, and evaluation.
- **Performance Metrics**: Detailed analysis of model performance using various evaluation metrics to ensure effective caption generation.

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib (for visualizations)

## Getting Started
To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Shrinjita/Image-Captioning.git
   cd Image-Captioning
   ```

2. **Download the Flickr8k dataset**:
   You can download the dataset from [here](http://web.engr.illinois.edu/~bplumme2/Flickr8k_Dataset.htm). Ensure that the dataset is placed in the correct directory as referenced in the notebook.

3. **Install the required packages**:
   If you don’t have the required libraries installed, you can do so with:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Jupyter Notebook**:
   Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

5. **Open the Notebook**:
   Open `ImageCaptioning.ipynb` to explore the project and generate captions for your images.

## Usage
Load your images from the Flickr8k dataset and generate captions by executing the cells in the notebook. The model can be further fine-tuned with additional training data for improved performance.
