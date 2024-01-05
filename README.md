# ENCRYPTON HACKATHON - Green Finance Predictive Models

## Team Solomon
- Taneti Sanjay
- Narne Dheeraj Balaram

## Problem Statement
Develop innovative AI and machine learning models to predict trends and risks in green finance, assisting financial institutions in making informed and sustainable decisions.

## Abstract
This study introduces a novel approach to address the increasing significance of sustainability in financial decision-making. By integrating artificial intelligence (AI) and machine learning (ML) models, our solution aims to predict trends and assess risks in green finance. Leveraging advanced analytics techniques, our methodology offers financial institutions a comprehensive perspective on sustainable investments, aligning portfolios with long-term environmental and financial goals.

## Methodology: Synergizing Financial and Environmental Data

### Model Building: Simple RNN
1. **Sequence Creation:** Transformed normalized time series data into sequences with 10 consecutive closing prices, setting the target for each sequence as the next closing price.
2. **Model Architecture:** Utilized three recurrent layers - SimpleRNN, LSTM, and GRU - with 50 units each, employing ReLU activation and Reshape layers for sequence dependencies. The final Dense layer represented the predicted price.
3. **Model Compilation:** Used the Adam optimizer, Mean Squared Error loss function, and accuracy as a metric.

### Prediction of Financial Data
- Considered NIFTY 50 index companies for predicting trends.
- Data preprocessing involved Minmax Scaling and omitted PCA due to the small dataset.
- Trained the model using sequences and target values, validating on a subset of the data.

### Prediction of Risk Factor
- Utilized an ESG dataset for India, applying a mean mathematical function to derive an ESG rating or risk factor.
- Lower risk factors indicated non-sustainable investments, guiding investors judiciously.

### Cons of Our Approach
1. Limited Representativity: Small datasets may lack diversity.
2. Overfitting Risk: Higher chance due to insufficient data.
3. Model Complexity Concerns: Complex models may memorize the small dataset.
4. Uncertain Predictions: Limited data may lead to less confident predictions.

### Overcoming Problems
1. Augmentation of datasets.
2. Implement techniques such as dropout or L1/L2 regularization.
3. Choose a simpler model rather than a complex one.

### Model Outcomes Ranking
1. Random Forest
2. Linear Regression
3. Simple RNN
4. ARIMA

## Conclusion
The combination of predictive models enables financial investors to make sustainable investments. The ongoing improvement process and potential enhancements in the project's scope make it a promising solution for green finance.

## Future Scope
The current implementation is a prototype with potential for enhancement. Establishing a robust data pipeline allows models to undergo continuous training, refining and expanding their predictive and forecasting capabilities over time.

## References
1. Short-term stock market price trend prediction using a comprehensive deep learning system – Jingyi Shen.
