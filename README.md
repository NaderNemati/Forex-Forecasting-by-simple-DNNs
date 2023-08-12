# Forex Forecasting with Deep Neural Networks

This repository hosts an exploration into the realm of Forex price forecasting using deep neural networks. Machine learning algorithms have demonstrated their efficacy in predicting future OHLC (Open, High, Low, Close) prices, offering valuable insights for price prediction. Our study centers around a deep neural network model, leveraging Convolutional Neural Networks (CNNs) and incorporating multiple time frames to minimize disparities between actual and predicted prices.

## Motivation and Methodology

In our research, we adopt the use of FLF (Fill Limit Forecasting) and Mean Square Error as loss functions to train our deep neural network model. By harnessing the power of Convolutional Neural Networks, we seek to capture intricate patterns within Forex price data. Our model's architecture is carefully designed to consider multiple time frames, enriching its understanding of the underlying trends.

## Model Architectures Explored

### Long Short-Term Memory (LSTM)

The LSTM, a well-established architecture, processes input through three gates: forget, input, and output. These gates collectively determine the flow of information, allowing the LSTM to capture both short-term and long-term dependencies. The LSTM's recurrent connections facilitate the retention of essential information over sequential time steps.

### Gated Recurrent Unit (GRU)

In contrast to LSTM, the GRU offers a simplified structure by combining forget and input gates into an update gate and a reset gate. This streamlined design reduces parameter complexity while effectively managing long-short term memory. The GRU's ability to retain pertinent information while discarding noise enhances its performance in sequential data analysis.

### Convolutional Neural Network (CNN)

Originally designed for image analysis, CNNs have been adapted for sequential data analysis, including time series forecasting. The architecture's convolutional and pooling layers progressively extract intricate features, culminating in fully-connected layers for classification or regression. One-dimensional convolutions enable effective processing of sequential data, facilitating pattern recognition in Forex price trends.

## Repository Contents

- `data/`: Preprocessed and normalized EURUSD dataset, along with train-validation-test splits.
- `notebooks/`: Jupyter notebooks detailing model implementations, experimentation, and results.
- `models/`: Saved model checkpoints and configurations for reproducibility.
- `results/`: Quantitative and qualitative findings, including performance metrics and visualizations.
- `src/`: Source code for data preprocessing, model architecture, training, and evaluation.

## Usage

To replicate our experiments and delve into the details of our models, refer to the Jupyter notebooks in the `notebooks/` directory. These notebooks provide step-by-step walkthroughs of data preprocessing, model construction, training, and evaluation.

## Citation

If you find this work valuable for your research or projects, kindly consider citing:


## License

This project is licensed under the [MIT License](LICENSE).

---

For inquiries or collaborations, please reach out to [Your Name](mailto:your.email@example.com).

