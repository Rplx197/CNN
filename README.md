Transfer Learning with InceptionV3 for Corn Leaf Disease Classification
This project uses Transfer Learning with the InceptionV3 model to classify diseases in corn leaves. The diseases targeted in this project include leaf rust, leaf blight, and leaf spot.

Project Overview
Corn leaf diseases significantly impact crop yield, and detecting these diseases early is crucial for effective management. This project leverages deep learning and the InceptionV3 model for disease classification. The model is pre-trained on the ImageNet dataset and fine-tuned on a custom corn leaf disease dataset to improve classification accuracy.

Key Features:
Transfer Learning with InceptionV3 model.
Disease Classification for corn leaves (leaf rust, leaf blight, and leaf spot).
Evaluation using performance metrics like accuracy, precision, recall, and F1-score.
Dataset
The dataset used in this project contains images of corn leaves, labeled with different disease categories:

Leaf Rust
Leaf Blight
Leaf Spot
It is recommended to split the dataset into training, validation, and testing sets.

Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/Rplx197/Transfer-Learning-InceptionV3-Corn-Leaf-Disease-Classification.git
Navigate to the project directory:

bash
Copy
Edit
cd Transfer-Learning-InceptionV3-Corn-Leaf-Disease-Classification
Install the required dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Usage
Run the Transfer Learning model using the following command:

bash
Copy
Edit
jupyter notebook Transfer_Learning_InceptionV3_Corn_Leaf_Disease_Classification.ipynb
The notebook contains the following key steps:

Data Preprocessing: Loading and preparing the corn leaf images.
Model Architecture: Using the InceptionV3 model with pre-trained weights, fine-tuned for disease classification.
Model Training: Training the model with the dataset.
Model Evaluation: Evaluating the model performance using accuracy, precision, recall, and F1-score.
Results
The model will output performance metrics, including:

Accuracy
Precision
Recall
F1-Score
These metrics are calculated to evaluate the model's effectiveness in classifying the corn leaf diseases.

Contributing
Feel free to fork the repository and submit pull requests. Contributions are welcome to improve the model, dataset, or other parts of the project.

License
This project is licensed under the MIT License - see the LICENSE file for details.
