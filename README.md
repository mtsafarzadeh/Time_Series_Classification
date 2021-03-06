# Time_Series_Classification
Classification of time series of subscribers for 100 different companies from their LinkedIn followers count. 
In this approach I adopt KMeans classification of time series by implementing dtw metric which stands for dynamic time warping. 
This is different that Eucledian case as time series are compared with more elasticity. 
By randomly selecting about 100 companies with long-enough records dating back to Sep 2015 (covering for almost 3 years) I ask the classifier to 
find three main "growth eigenmodes" or clusters. The result is that companies are either  showing  i) a bubmp in subscriber number, remaining constant and then starting a linear increase or ii) a bumbp in subscriber number followed by a linear growth, 
then another bump and followed by anothe linear growth or iii) a constant linear growth from the beginning. 


By analyzing the time series data, in this Python notebook I explore whether 1) there is a correlation between the subscribers' growth rate on LinkedIn for a company and the employees count of those companies. 2) Do specific industries, for example banking, exprience a different statistics in terms of their emplyee's count.

Later on I will use the time series forecaster "prophet" ( made by Facebook ) to predict the growth of companies. 
