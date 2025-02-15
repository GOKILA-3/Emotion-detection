**Emotion Detection Model**
This project is an emotion detection system using deep learning. The model is built using Convolutional Neural Networks (CNNs) to classify emotions from images.

📂 **Dataset Structure**
The dataset consists of images stored in labeled directories:

📂 **images** 

 ├── 📂 train  (Training dataset)  
 ├── 📂 test   (Testing dataset)  
 
📌 **Requirements**
Install the necessary dependencies using:
pip install keras-preprocessing keras tensorflow pandas numpy scikit-learn

🏗 **Model Architecture**
The CNN model consists of:
Convolutional layers with ReLU activation
MaxPooling layers for dimensionality reduction
Dropout layers to prevent overfitting
Fully connected dense layers for final classification

🚀 **Training & Evaluation**
Load and preprocess images (resize to 48x48, normalize pixel values).
Encode labels into categorical values.
Split the dataset into training and validation sets.
Train the CNN model using categorical cross-entropy loss and Adam optimizer.
Evaluate model performance on the test set.

📌**Running the Code**
To train the model, run:
python trainmodel.py

📊 **Model Evaluation**
The model is evaluated based on accuracy and loss metrics.
