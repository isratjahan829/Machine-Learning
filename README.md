<h1 align="center">
  🌟 Mango Leaf Disease Classification in Bangladesh using Random Forest and Decision Tree. 
</h1>

<h3 align = "center"> 👀 Please have a look at our beautiful, well-documented <a href="https://github.com/isratjahan829/Machine-Learning/blob/main/mangoleafbd-rf-df.ipynb">Notebook1</a></h3>
<h3 align = "center"> 👀 Please have a look at our beautiful, well-documented <a href="/src/tasks/task-3-model-training/Best-Model/ResNet50/mango-leaf-disease-detection-using-cnn.ipynb">Notebook2</a></h3>
## Problem
Bacterial and fungal diseases are major constraints for mango production, causing around 30% yield loss annually. The absence of real-time, automated systems for early detection and classification of mango leaf diseases hampers efforts to mitigate crop losses. Currently, farmers face delayed diagnoses which reduces productivity and causes financial losses. This project aims to address this problem by developing a cutting-edge Computer Vision-based model that provides instant in-field detection and classification of mango leaf diseases, empowering farmers with timely information to reduce losses and enhance their income.

## Features
- **Data Preprocessing:** Cleans and processes the dataset.
- **Feature Engineering:** Encodes categorical variables.
- **Random Forest Model:** A powerful ensemble learning algorithm used for classification.
- **Evaluation Metrics:** Includes accuracy, precision, recall, and F1-score.
- **Visualization:** Provides graphical representations of feature importance and model performance.

## Installation
1. Clone the repository:
   ```sh
   git clone <repository-url>
   cd MushroomSUC-Data-RF-DF
   ```
2. Install required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```sh
   jupyter notebook mushroomsuc-data-rf-df.ipynb
   ```

## Dataset
The dataset consists of labeled samples of mushrooms with various biological and morphological features. It is preprocessed for optimal model performance. The key features include:
- Cap shape, surface, and color
- Gill attachment and spacing
- Stalk shape, root, and surface texture
- Presence of rings and spore print color

## Usage
- Execute the Jupyter Notebook to train the model.
- Tune hyperparameters for improved accuracy.
- Evaluate model performance using test data.
- Use the trained model to classify new mushroom samples.

## Results
The model successfully differentiates between edible and poisonous mushrooms with high accuracy, making it a valuable tool for mycological studies and food safety analysis.

## Folder Structure
```
MushroomSUC-Data-RF-DF/
│-- data/                # Dataset folder
│-- models/              # Saved models
│-- notebooks/           # Jupyter Notebooks
│-- results/             # Model performance results
│-- mushroomsuc-data-rf-df.ipynb  # Main notebook
│-- requirements.txt     # Dependencies
│-- README.md            # Project documentation
```


## Data

The model is trained on a dataset of 3600 mango leaf images representing 7 common diseases and healthy leaves. The dataset was downloaded from data.mendeley.com, collected from orchards in various mango-growing regions of Bangladesh.

The classes:

    Bacterial Canker
    Anthracnose
    Powdery Mildew
    Leaf Spot
    Die Back
    Sooty Mold
    Healthy

The dataset is split into train and validation sets.
However, we created a test set and our team has removed the duplicates and augmented images from the original dataset.


