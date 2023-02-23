# Stock Market Prediction

## Stock Market Prediction Using Anonymized Datasets 

Stock market prediction is one of the most difficult tasks even for experts. Market volatility and other factors that influences the value of a stock lead to difficulties in prediction.

However, with the introduction of Deep Learning algorithms, the accessibility of huge compute power, and the democratization and anonymization of financial data by platforms like https://numer.ai/, stock market predictions are becoming easier

Link to the Kaggle Notebook: https://www.kaggle.com/ubajakacj/kaggle-note/

## How is the stock market predicted?
### Summary
- Used 'medium' __features__ of the dataset which is optimal for 30 GB RAM
- 'medium' contains 472 features
- Got the per-era correlation of each feature with the largest and used the information to get 50 riskiest eras by checking the largest correlation differences within each era.

### Model Prediction
- The prediction of the model, that is the validation and live predictions were neutralized to the 50 riskiest features and were ranked from 0 to 1 to meet the Numerai upload requirements.

### Model Performance
- Sharpe Ratio of __0.973428__ for neutralized predictions.
- Sharpe Ratio of __0.858913__ for normal predictions.

### Conclusion
- The Sharpe Ratio is __0.973428__. There is still room for improvement.
- Stock market prediction using anonymized datasets, large compute power and a network of Data Scientists is a new and creative way of extracting optimal value from financial data.


# By Ubajaka, Chijioke

## Prerequisites:
- Google Colab | Kaggle Notebook
- LightGBM
- Google Drive (Optional)
