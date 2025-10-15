# Fashion_Image_Classification
A COMPARATIVE STUDY OF CLASSIFICATION MODELS FOR FASHION ITEM CATEGORIZATION
│
├── README.md                # Project documentation
├── req.txt                  # Required Python dependencies
├── research images.zip      # Dataset used for training and testing
└── rnet.ipynb               # Jupyter notebook with full implementation
Steps Followed
1. Dataset Collection

The dataset used is from Kaggle (Women's Fashion Trend Dataset).

It contains labeled fashion product images across multiple categories such as dresses, tops, trousers, shoes, and accessories.

Images were downloaded and stored in research images.zip.

2. Data Preprocessing

Extracted and organized images into respective category folders.

Applied preprocessing steps such as:

Image resizing (224x224 pixels)

Normalization of pixel values

Data augmentation (rotation, flipping, zoom)

3. Environment Setup

Created a req.txt file listing all dependencies including:

tensorflow
keras
numpy
pandas
matplotlib
scikit-learn
opencv-python


Installed using:

pip install -r req.txt

4. Model Implementation

Implemented the model in rnet.ipynb.

Used ResNet50 as the base CNN architecture with transfer learning.

Added dense layers for classification with softmax activation.

Used categorical cross-entropy loss and Adam optimizer.

5. Model Training

Trained the model on the preprocessed dataset.

Used training and validation splits for performance monitoring.

Implemented early stopping and learning rate reduction callbacks.

6. Model Evaluation

Evaluated model performance using:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

Visualized performance metrics using matplotlib plots.

7. Results

The ResNet50 model achieved the highest accuracy compared to other tested models.

Demonstrated strong feature extraction and generalization for image-based fashion classification.
