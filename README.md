# Stock-Market-Prediction-437
Project for Machine Learning and Soft Computing CS437. We are going to be predicting 2 US stocks and Indices trying to create better models than we have discovered. We will be using RNNs, random forests, SVM and Naive Bayes.

## Stocks and Indices for this project 
<table>
  <tr>
    <th>Stocks</th>
    <td>Microsoft (MSFT)</td>
    <td>Amazon (AMZN)</td>
  </tr>

  <tr>
    <th>Indices</th>
    <td>S&P 500 (^GSPC)</td>
    <td>Dow Jones (^DJI)</td>
  </tr>
</table>

<p>These stocks and indices are chosen as they allow us to maximize relevance by mirroring the original paper's goals by testing on highly liquid, market leading components of major indices, while encompassing technology and industrial scale operations. The S&P 500 and Dow Jones are considered two of the most fundemental barometers of the US economy and stock market. Microsoft allows us to see into the tech sector while Amazon allows us to have a conglomerate diversification.</p>

<p>We want to compare continuous valued parameters in data to discrete valued parameters. With continuous valued parameters the data is the raw numerical features such as Relative strength index (RSI). Where it might be 42. In discete valued parameters the data is binary or categorical values. For RSI it will be either 1 or 0 to represent if the RSI was greater or less than yesterday. This simplifies the data and in theory should allow for better prediction. </p>

<p>To run the .ipynb files you must pip install everything on the requirements.txt page<p>
