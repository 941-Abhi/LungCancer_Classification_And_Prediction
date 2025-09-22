Lung Cancer Classification and Prediction
Project Overview
This project focuses on the development of a deep learning model to classify different types of lung cancer from medical images. Leveraging a dataset of high-resolution CT scans, the goal is to build an automated system that can accurately predict a diagnosis, including Adenocarcinoma, Large Cell Carcinoma, Squamous Cell Carcinoma, and Normal lung tissue.

The project uses a Convolutional Neural Network (CNN) architecture to analyze the complex features within the CT scan images, providing a tool that can assist medical professionals in the early and accurate detection of lung cancer.

Dataset
The dataset used for this project is a comprehensive collection of high-resolution CT scan images sourced from Mendeley Data. It is a multi-class dataset divided into three sets:

Training Set: 613 images

Testing Set: 315 images

Validation Set: 72 images

Source: https://data.mendeley.com/datasets/bncfhxbzrv/1

Prerequisites
This project requires Anaconda to manage the Python environment and all dependencies.

The following libraries are required:

TensorFlow

Keras

NumPy

Matplotlib

Scikit-learn

OpenCV

Installation and Setup
To set up the project, follow these steps to create a new Anaconda environment and install all dependencies.

Clone the Repository (If applicable): If you are using Git, clone this repository to your local machine.

Bash

git clone [your-repository-url]
cd [your-project-directory]
Create the Anaconda Environment: A environment.yml file is included to ensure all dependencies are installed correctly. Run the following command in your Anaconda Prompt:

Bash

conda env create -f environment.yml
Activate the Environment: Activate the newly created environment.

Bash

conda activate LungCancer_Classification_And_Prediction
Download the Dataset: Download and unzip the dataset from the Mendeley link provided above. Place the unzipped Data folder inside your project directory. The final directory structure should match the one shown below.

File Structure
.
├── Data/
│   ├── train/
│   ├── test/
│   └── valid/
├── DHAI.ipynb
├── main.py
├── environment.yml
└── README.md
Usage
To run the project, open your Jupyter Notebook and execute the cells in sequential order.

Launch VS Code from your active Anaconda environment:

Bash

code .
Open the DHAI.ipynb notebook.

Select the LungCancer_Classification_And_Prediction kernel in the top-right corner of the notebook.

Run the code cells one by one to load the data, build the model, train it, and evaluate its performance.

Results and Analysis
The project includes code to perform a detailed analysis of the model's performance.

Training and Validation Accuracy/Loss: The training output will show how the model's performance improves over epochs.

Test Set Evaluation: The final accuracy and loss on the test set will provide an unbiased measure of the model's performance on unseen data.

Statistical Analysis: The project includes code to generate a Confusion Matrix and a Classification Report (Precision, Recall, F1-Score) to evaluate the model's predictive capabilities for each class.

License
This project is licensed under the MIT License.