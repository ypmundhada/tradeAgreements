# tradeAgreements
Analyzing the impact of trade agreements using Machine Learning

Evaluate the impact of trade agreements on trade flows with respect to provisions like competition policy,
trade related investment measures, anti dumping laws, etc.
A Feature Selection problem - To select most important provisions and quantifying their impact on trade
flows between the agreement holding nations.
To find out what provisions leads to the most enhancement of trade flows between the countries.
Different ML techniques are tried to build the models like k-fold cross validation, Lasso regression and Iceberg Lasso.
These techniques are already used in the existing World Bank paper. In the World Bank paper, it was concluded that the Iceberg Lasso, was the best technique in the literature so far, but it cannot be said with certainty that the provisions selected by the Iceberg Lasso would really enhance the trade or some of the provisions were just correlated with the provisions that actually enhance trade.

So, in this project I propose a new technique for feature selection using LSTM. The problem of correlating features getting selected will be eliminated using LSTM, as it is not an econometric method, rather it is based on the Recurrent Neural Networks.

Gained exposure to different Machine Learning techniques like Lasso regression, Iceberg Lasso, LSTM,
etc. The models built in Scikit-Learn and trained on the World Bank dataset on the Preferential Trade
Agreements 1964-2016.


I am currently working on this research project.
Will upload the analysis, code, datasets and paper soon.
