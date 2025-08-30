Hindi Fake News Detection

Overview
This project focuses on detecting fake news in Hindi using machine learning and deep learning techniques. It uses the Hindi Fake News Detection Dataset (HFDND), containing over 16,000 Hindi news headlines labeled as fake or real, to train models that classify news accuracy and combat misinformation.

Dataset

Dataset name: Hindi Fake News Detection Dataset (HFDND)
Contents: Approximately 16,933 Hindi news headlines labeled as fake or real news
Dataset location: Place the downloaded dataset files inside the folder named HFDND in the project root
Source: Available on Kaggle or other public repositories 
https://www.kaggle.com/datasets/arnavagrawal22/arnsin-dl-cleaned1

Features

Preprocessing, cleaning, and tokenization of Hindi text data
Implemented deep learning models: Convolutional LSTM and Bidirectional LSTM
Fine-tuned pre-trained Hindi BERT model (L3Cube) for improved classification accuracy
Evaluated models using accuracy metrics with best model achieving ~90% accuracy



Technologies Used

Python
TensorFlow / Keras
NLP libraries for Hindi text processing
Pre-trained Hindi BERT model (L3Cube)


Model	Accuracy

Convolutional LSTM	~81%
Bidirectional LSTM	~82%
Hindi BERT fine-tuned	~90%


Installation & Usage

Clone the repository:

bash
git clone https://github.com/Prabhakar9611/Project-HindiFakeNewsDetection.git
cd HindiFakeNews_Model3.ipynb

Download the Hindi Fake News Detection Dataset (HFDND) from https://www.kaggle.com/datasets/arnavagrawal22/arnsin-dl-cleaned1.



Create a folder named HFDND in the project root directory and place the dataset files inside it.

Install dependencies:

bash
pip install -r requirements.txt
Run the Jupyter notebook for data preprocessing, model training, and evaluation:

bash
jupyter notebook HindiFakeNews_Model3.ipynb
Follow the notebook cells to preprocess data, train models, and evaluate performance.


Future Enhancements

Expand dataset size for better generalization
Add explainability features to interpret model decisions
Develop a web app or API for real-time fake news detection
Explore advanced transformer models for higher accuracy


Contact

For questions or collaboration, 
contact:
PRABHAKAR S- prabhakar4541@gmail.com
"# Project-HindiFakeNewsDetection" 
"# Project-HindiFakeNewsDetection" 
