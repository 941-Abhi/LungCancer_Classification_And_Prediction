# Lung Cancer Classification and Prediction

## 📌 Project Overview
This project focuses on the development of a deep learning model to classify different types of lung cancer from medical images. Using a dataset of high-resolution CT scans, the goal is to build an automated system that can accurately predict a diagnosis, including:

- **Adenocarcinoma**
- **Large Cell Carcinoma**
- **Squamous Cell Carcinoma**
- **Normal Lung Tissue**

A **Convolutional Neural Network (CNN)** architecture is used to analyze the complex features within CT scan images, providing a tool that can assist medical professionals in the early and accurate detection of lung cancer.

---

## 📂 Dataset
The dataset used is a comprehensive collection of high-resolution CT scan images from **Mendeley Data**.

- **Training Set:** 613 images  
- **Testing Set:** 315 images  
- **Validation Set:** 72 images  

🔗 Source: [Mendeley Dataset](https://data.mendeley.com/datasets/bncfhxbzrv/1)

---

## ⚙️ Prerequisites
This project requires **Anaconda** to manage the Python environment and dependencies.

Install the following libraries:
- TensorFlow  
- Keras  
- NumPy  
- Matplotlib  
- Scikit-learn  
- OpenCV  

---

## 🚀 Installation and Setup

1. **Clone the Repository** (if applicable):

```bash
git clone [your-repository-url]
cd [your-project-directory]

Create the Anaconda Environment
An environment.yml file is provided to install all dependencies.

conda env create -f environment.yml


Activate the Environment

conda activate LungCancer_Classification_And_Prediction


Download the Dataset
Download and unzip the dataset from the Mendeley link above.
Place the unzipped Data folder inside your project directory.

📁 File Structure
.
├── Data/
│   ├── train/
│   ├── test/
│   └── valid/
├── DHAI.ipynb
├── main.py
├── environment.yml
└── README.md

🖥️ Usage

Launch VS Code from your active Anaconda environment:

code .


Open the DHAI.ipynb notebook.

Select the LungCancer_Classification_And_Prediction kernel.

Run the notebook cells in order to:

Load the data

Build the CNN model

Train the model

Evaluate performance

📊 Results and Analysis

Training and Validation Accuracy/Loss: Performance improvement over epochs is tracked.

Test Set Evaluation: Provides unbiased accuracy and loss on unseen data.

Statistical Analysis: Generates a Confusion Matrix and Classification Report (Precision, Recall, F1-Score) to evaluate predictive capability across all classes.

📜 License

This project is licensed under the MIT License.
