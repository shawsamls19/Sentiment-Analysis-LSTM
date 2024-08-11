# Sentiment-Analysis-LSTM

### 1.Project Setup
Objective: Predict the sentiment (positive or negative) of IMDB movie reviews using an LSTM-based deep learning model.
Dataset: IMDB dataset, typically contains 50,000 movie reviews with binary labels (positive or negative).

### 2. Data Preprocessing
Text Cleaning:
Remove special characters, numbers, and stopwords.
Convert text to lowercase.
Tokenization: Convert words into tokens (integers).
Padding: Pad sequences to ensure all reviews have the same length, suitable for LSTM input.
Train-Test Split: Typically, split the dataset into 80% training and 20% testing.

### 3. Model Development
Embedding Layer: Converts words into dense vectors of fixed size, capturing semantic meaning.
LSTM Layer: Core layer of the model, capable of learning long-term dependencies in the text.
Dense Layer: Fully connected layer with a sigmoid activation function for binary classification.

### 4. Model Compilation
Loss Function: Use binary_crossentropy for binary classification.
Optimizer: Use Adam optimizer for efficient training.
Metrics: Track accuracy to evaluate the model's performance.

### 5. Model Training
Train the model using the training set, validating on a validation split.

### 6. Evaluation
Evaluate the model on the test set to check accuracy, precision, recall, and F1-score.

### 7. Conclusion
Summarize the results, discuss the strengths and limitations of the model, and propose potential improvements.
This project gives hands-on experience with LSTM networks, NLP preprocessing techniques, and model deployment, making it a comprehensive deep learning project.
