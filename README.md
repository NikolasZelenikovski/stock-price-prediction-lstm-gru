# Stock Price Prediction using LSTM and GRU

This project explores the use of Recurrent Neural Networks (LSTM and GRU) to predict Apple Inc. (AAPL) stock prices based on historical data. We also enhance the GRU model by including volume data as an additional feature.

## Models Used
- LSTM (using only 'Close' prices)
- GRU (using only 'Close' prices)
- GRU with Volume (using both 'Close' and 'Volume')

## Technologies
- Python
- Keras (TensorFlow backend)
- yfinance
- scikit-learn
- matplotlib
- Google Colab

## Results
| Model               | RMSE (Lower is Better) |
|---------------------|------------------------|
| LSTM                | 3.2204                 |
| GRU (Close only)    | 2.0293                 |
| GRU (Close + Volume)| 2.1223                 |

## Project Files
- `stock_prediction.ipynb`: Main Jupyter notebook with model training, evaluation, and plots
- `report.pdf` or `report.md`: Summary of methodology, results, and conclusion
- `presentation.pdf`: Slides for the final presentation

## Author
Nikolas Zelenikovski — Final Project Exam for CS XXXX, Spring 2025
