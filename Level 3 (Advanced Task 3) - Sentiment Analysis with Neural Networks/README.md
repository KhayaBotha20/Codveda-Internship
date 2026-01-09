# Deep Learning Task (Advanced Level)

## Objective
Demonstrate advanced skills in deep learning by building and training neural networks for complex tasks.

## Key Tasks
1. **Sentiment Analysis with Neural Networks**:
   - Dataset: Sentiment dataset.csv
   - Goal: Classify text sentiment using deep models.
   - Steps:
     - Preprocess text (tokenization, embeddings like Word2Vec or use pre-trained).
     - Build LSTM or CNN model for text classification.
     - Train with train/validation split.
     - Evaluate with accuracy, F1-score.
     - Experiment with hyperparameters.

2. **Stock Price Time Series Forecasting**:
   - Dataset: Stock Prices Data Set.csv
   - Goal: Predict future stock prices using RNNs.
   - Steps:
     - Prepare time series data (sliding windows).
     - Build LSTM or GRU model.
     - Train on historical data.
     - Evaluate with RMSE, MAE.
     - Visualize predictions vs. actuals.

3. **Deep Classification on Tabular Data**:
   - Datasets: iris.csv or churn-bigml-20.csv/80.csv
   - Goal: Use MLP for classification.
   - Steps:
     - Preprocess tabular data.
     - Design multi-layer perceptron.
     - Train and tune (dropout, batch normalization).
     - Compare to traditional ML models.
     - Analyze performance.

## Datasets Location
Datasets are in `../Data Set For Tasks/Data Set For Task/`.

## Tools and Libraries
- TensorFlow/Keras for neural networks
- Pandas/NumPy for data handling
- Matplotlib/Seaborn for visualization
- NLTK for text processing
- Jupyter for notebooks

## Deliverables
- Python scripts or notebooks with model code.
- Training logs, evaluation metrics.
- Visualizations and model interpretations.