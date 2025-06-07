# X Posts Sentiment Analysis

A deep learning project using LSTM networks to classify tweet sentiments (positive/negative) based on the Sentiment140 dataset. This project was developed as part of the AI Capstone course at Samsung Innovation Campus.

### Project Structure
Sentiment140_Project.ipynb: Jupyter notebook containing the full implementation.

README.md: Project overview and instructions.

SIC_AI_Capstone Project_Final Report.pdf: Detailed final report (not publicly distributed).

### Objective
The main goal of this project is to build and evaluate LSTM-based models to classify sentiment in tweets. The project explores various model architectures and compares performance between LSTM, BiLSTM, and GRU.


### Model Overview
Best Model: Bidirectional LSTM with 2 layers + 2 dropout layers

Accuracy: ~77.6%

### Frameworks: TensorFlow / Keras

### Features:

Tokenization and padding

Model checkpointing and early stopping

Evaluation with metrics: accuracy, precision, recall, F1-score

### Project Steps
#### Data Preprocessing :

- Removed URLs, mentions, stopwords, special characters
- Tokenization and padding (max length = 50)

#### EDA (Exploratory Data Analysis):

- Class balance check
- Word clouds for each sentiment class

#### Model Training:

- Compared LSTM, GRU, and Bidirectional LSTM architectures
- Hyperparameter tuning (dropout rate, learning rate, etc.)
- Early stopping and best-model saving

#### Evaluation:

- Confusion matrix
- Performance comparison between 9 model versions

### Results
Model	Accuracy	Training Time
BiLSTM (2 layers, 2 dropouts)	77.6%	174 sec
GRU (2 layers, 2 dropouts)	50%	126 sec
LSTM (simpler)	49–75%	93–98 sec


### Future Work
- Apply transfer learning using BERT/GPT
- Expand dataset with multilingual or industry-specific tweets
- Improve generalization via text augmentation
- Develop a UI for real-time sentiment prediction

### Team Members
Aws Alharthi - Layan AlShahrani - Ismail Alsalhi - Ali Alfares - Naif Alaklubi - Lama Aljuaid


### License
This project was created under the Samsung Innovation Campus program and is protected by copyright. Do not distribute without permission.
