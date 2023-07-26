# Cryptocurrency_Price_Prediction
The Cryptocurrency Price Prediction model uses machine learning and deep learning concept to predict the value of bitcoin and other cryptocurrencies.
## Bitcoin Price forecasting with LSTM and GRU
Bitcoin is the first decentralized digital currency. This means it is not governed by any central bank or some other authority. This cryptocurrency was created in the 2009 year but it becomes extremely popular in the 2017 year. Some experts call bitcoin "the currency of the future" or even lead it as an example of the social revolution. The bitcoin price has increased several times during the 2017 year. At the same time, it is very volatile. Many economic entities are interested in tools for forecasting the bitcoin prices. It is especially important for existing or potential investors and for government structures. The last needs to be ready for significant price movements to prepare consistent economic policy. So, the demand for Bitcoin price prediction mechanism is high.

This notebook demonstrates the prediction of the bitcoin price by the neural network model. We are using 2-layers long short term memory (LSTM) as well as Gated Recurrent Unit (GRU) architecture of the Recurrent neural network (RNN). You can read more about these types of NN here:

https://deeplearning4j.org/lstm.html

http://colah.github.io/posts/2015-08-Understanding-LSTMs/

https://arxiv.org/pdf/1412.3555v1.pdf

http://karpathy.github.io/2015/05/21/rnn-effectiveness/

The dataset we are using is available here: Bitcoin Historical Data -
https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data

After the boom and bust of cryptocurrencies’ prices in recent years, Bitcoin has been increasingly regarded as an investment asset. Because of its highly volatile nature, there is a need for good predictions on which to base investment decisions. Although existing studies have leveraged machine learning for more accurate Bitcoin price prediction, few have focused on the feasibility of applying different modeling techniques to samples with different data structures and dimensional features. To predict Bitcoin price at different
frequencies using machine learning techniques, we first classify Bitcoin price by daily price, high-frequency price, highest price, lowest price, average price, opening price, closing price and rate of fluctuation in price.

Statistical methods including Logistic Regression and Linear Discriminant Analysis for Bitcoin daily price prediction with highdimensional features achieve an accuracy of 66%, outperforming more complicated machine learning algorithms. Compared with benchmark
results for daily price prediction, we achieve a better performance, with the highest accuracies of the statistical methods and machine learning algorithms of 66% and 65.3%, respectively. Machine learning models including Long Short-term Memory(LSTM) and Gated Recurrent Unit (GRU) for Bitcoin price prediction are superior to statistical methods, with accuracy reaching 99%. Our investigation of Bitcoin price prediction can be considered a pilot study of the importance of the sample dimension in machine learning techniques.

# System Requirements
1. Python version >= 3.9.12 + (Jupyter Notebook/Jupyter Lab)
2. Numpy
3. Pandas
4. Keras
5. Tensorflow
6. Matplotlib
7. Sci-Kit Learn
8. Scipy
9. Datetime
10. Plotly
