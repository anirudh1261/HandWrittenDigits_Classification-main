🧠 Handwritten Digit Recognition using CNN






A Machine Learning project that recognizes handwritten digits (0–9) using a Convolutional Neural Network (CNN) trained on the MNIST dataset.

📌 Overview

This project demonstrates how Deep Learning can automatically recognize handwritten digits from images.
CNN models learn patterns such as edges, curves, and shapes to accurately classify numbers.

Applications

🏦 Bank cheque processing

📮 Postal code recognition

📝 Form digitization

📄 Document processing systems

📊 Dataset

The model is trained using the MNIST dataset.

Dataset Details

70,000 handwritten digit images

Image size: 28 × 28 pixels

Classes: 0–9

Additional datasets used:

Train Dataset
https://www.kaggle.com/competitions/digit-recognizer/data?select=train.csv

Test Dataset
https://www.kaggle.com/competitions/digit-recognizer/data?select=test.csv

⚙️ Technologies Used

Python

TensorFlow / Keras

NumPy

Pandas

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook

🧠 Model

The system uses a Convolutional Neural Network (CNN) consisting of:

Convolution layers for feature extraction

Batch normalization

Max pooling layers

Fully connected dense layers

Softmax output layer for digit classification

🚀 How to Run

1️⃣ Install required libraries

pip install numpy pandas matplotlib seaborn tensorflow scikit-learn

2️⃣ Download train.csv and test.csv from Kaggle and place them in the project folder.

3️⃣ Start Jupyter Notebook

jupyter notebook

4️⃣ Open and run:

SourceCode.ipynb
📈 Output

The model achieves high accuracy in recognizing handwritten digits and generates:

Accuracy graphs

Loss graphs

Confusion matrix

Digit prediction results

👨‍💻 Author

Anirudh Ganji
Computer Science – 2nd Year

⭐ A simple demonstration of Deep Learning for image classification.
