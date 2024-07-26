# Ethiopian Athletes Image Classifier

In this project, I developed an image classifier for Ethiopian athletes using scikit-learn. I utilized matplotlib for data visualization and used Haar cascade to detect and select images with facial features such as the face, eyes, nose, and mouth. I also used wavelet transformation for feature engineering. This project was built on Google Colab.

## Features

- Classifies images of Ethiopian athletes
- Uses Haar cascade for facial feature detection
- Employs wavelet transformation for feature engineering
- Visualizes data using matplotlib

## Technologies Used

- Python
- Scikit-learn
- Matplotlib
- OpenCV (for Haar cascade)
- PyWavelets (for wavelet transformation)
- Google Colab

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/saleamlakw/Ethiopian_athletes_image_classifier.git
    cd Ethiopian_athletes_image_classifier
    ```

2. Open the project in Google Colab by uploading the notebook file (`ethiopian_athletes_classifier.ipynb`).

## Usage

1. Upload your dataset to Google Colab or use the provided dataset.
2. Run the cells in the Colab notebook to execute the code step-by-step.
3. The notebook includes data visualization, image preprocessing, feature engineering, and model training.
4. After training, the model can classify new images of Ethiopian athletes.

## Data Preprocessing

- **Image Selection**: Used Haar cascade to detect and select images with prominent facial features such as the face, eyes, nose, and mouth.
- **Feature Engineering**: Applied wavelet transformation to extract relevant features from the images.

## Model Training

- **Algorithm**: Utilized various algorithms available in scikit-learn.
- **Evaluation**: Evaluated the model using appropriate metrics and visualized the results using matplotlib.

## Visualization

- **Matplotlib**: Used for plotting graphs and visualizing data distributions and model performance.

## Dependencies

The project requires the following Python packages:

```text
scikit-learn
matplotlib
opencv-python
PyWavelets
```
## To install these packages, run:
```bash
pip install scikit-learn matplotlib opencv-python PyWavelets
```
