# Natural Language Processing (NLP) - Disaster Tweets Classification

## Project Overview
This project applies **Natural Language Processing (NLP)** techniques to classify disaster-related tweets. Using **BiGRU with Attention**, **pre-trained GloVe embeddings**, and **hyperparameter tuning**, the model aims to differentiate between tweets about real disasters and unrelated content.

### Dataset
The dataset is sourced from Kaggle's **"Real or Not? NLP with Disaster Tweets"** competition:
[🔗 Kaggle Competition](https://www.kaggle.com/competitions/nlp-getting-started/data)

## Project Features
✔ **Preprocessing & Tokenization**: Cleans and tokenizes text data.
✔ **GloVe Embeddings**: Uses pre-trained word embeddings for better semantic understanding.
✔ **BiGRU with Attention**: Improves text classification by focusing on key features.
✔ **Hyperparameter Tuning**: Optimizes model performance using Keras Tuner.
✔ **Evaluation & Optimization**: Finds the best F1-score threshold for optimal classification.

## Setup Instructions
### **🔹 1. Install Anaconda**
If Anaconda is not installed, download and install it from:
[🔗 Anaconda Download](https://www.anaconda.com/products/distribution)

### **2. Create the Conda Environment**
Run the following command to set up the environment from the `environment.yml` file:
```bash
conda env create -f environment.yml
```

### **3. Activate the Environment**
```bash
conda activate my_env  # Replace 'my_env' with the environment name
```

### **4. Download the Dataset**
1. Visit the Kaggle competition page: [🔗 Kaggle Competition](https://www.kaggle.com/competitions/nlp-getting-started/data)
2. Download `train.csv` and `test.csv`
3. Place them in the project's `data/` directory.

### **5. Run the Jupyter Notebook**
Start Jupyter Notebook and open the project file:
```bash
jupyter notebook
```

##  Contact Information
For any questions or collaborations, feel free to reach out:
📧 **Email:** christopher.overton@colorado.edu