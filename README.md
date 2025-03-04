<h1 align="center">
  🌟 Mango Leaf Disease Classification in Bangladesh using Random Forest and Decision Tree. 
</h1>

<h3 align = "center"> 👀 Please have a look at our beautiful, well-documented <a href="https://github.com/isratjahan829/Machine-Learning/blob/main/mangoleafbd-rf-df.ipynb">Notebook1</a></h3>
<h3 align = "center"> 👀 Please have a look at our beautiful, well-documented <a href="/src/tasks/task-3-model-training/Best-Model/ResNet50/mango-leaf-disease-detection-using-cnn.ipynb">Notebook2</a></h3>
## Problem
Bacterial and fungal diseases are major constraints for mango production, causing around 30% yield loss annually. The absence of real-time, automated systems for early detection and classification of mango leaf diseases hampers efforts to mitigate crop losses. Currently, farmers face delayed diagnoses which reduces productivity and causes financial losses. This project aims to address this problem by developing a cutting-edge Computer Vision-based model that provides instant in-field detection and classification of mango leaf diseases, empowering farmers with timely information to reduce losses and enhance their income.

## Project Goals
Collect a comprehensive dataset of mango leaf images encompassing multiple bacterial and fungal diseases, ensuring representation across various regions.
Train and optimize Convolutional Neural Network (CNN) models to accurately detect and classify mango leaf diseases using the collected dataset.
Develop an intuitive user interface with trained models for real-time mango disease screening by farmers.
Learning Outcomes:
Gain hands-on experience in training CNN models using popular frameworks such as TensorFlow, applying transfer learning, and optimizing model performance.
Acquire knowledge and best practices for collecting high-quality data and annotations for training machine learning models in agricultural contexts.
Develop proficiency in deploying deep learning models for real-world applications, specifically in the field of agriculture.
Experience collaborating with a diverse team to build an end-to-end applied AI solution.

## Data

The model is trained on a dataset of 3600 mango leaf images representing 7 common diseases and healthy leaves. The dataset was downloaded from data.mendeley.com which was collected from orchards in various mango-growing regions of Bangladesh.

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

## Achievements
The model uses a ResNet50 architecture pre-trained on ImageNet weights. The model achieves an accuracy of 99.21% on the test set.

## Deployment
We deployed the model through Flask and streamlit. You have the option to interact with the project's live demo [here](https://mango-leaf-disease-app-omdena.streamlit.app/)


