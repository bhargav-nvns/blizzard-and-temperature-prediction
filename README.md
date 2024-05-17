# blizzard-and-temperature-prediction
<br>
For the data used in the polar plot repository (https://github.com/bhargav-nvns/Polar-plots), here machine learning algorithm is used to predict thedata for the next few time points in the data. This is done by using different packages in Python, including packages such as ‘TensorFlow,’ ‘matplotlib,’ ’seaborn’ etc..... to  predict the data and plot the future values using the ‘matplotlib’ in Python and have done classification of blizzard dates to predict them.
<br>
The first part includes predicting the temperature for the next three days (seventy-two values for three days) using the previous two weeks' temperatures as inputs. For this, we used ‘TensorFlow,’ ‘keras,’ ‘sklearn,’ ‘numpy’, and ‘pandas’ packages in Python to create algorithms and used packages such as ‘matplotlib’ to plot the predicted temperatures.
<br>
  
  <br>We use four different algorithms to predict the temperature.
<br> ANN (Artificial neural networks)
 <br> CNN (convolutional neural networks)
 <br> RNN (Recurrent neural network)
 <br> LSTM (Long short-term memory algorithm)
 <br>
 ![image](https://github.com/bhargav-nvns/blizzard-and-temperature-prediction/assets/148454572/3cd56a1c-44bf-455f-9f88-1674bc7c4502)
<br>
The next part includes using k-fold cross-validation. (Here we took K as five.)
 <br>
 ![image](https://github.com/bhargav-nvns/blizzard-and-temperature-prediction/assets/148454572/a92e5b7d-cc43-4228-a840-31540d4bd645)
<br>
And at last, the data is classified into blizzards or not
 <br> <br>
For analysis, we used parameters such as accuracy and F1 score. Accuracy measures the proportion of correctly classified instances made by the classification model. However, accuracy is not a good measure here since a sizable proportion of the data consists of non-blizzard cases, and only a few are balanced. Hence, accuracy cannot be a reliable metric in such huge, unbalanced data.
 <br>
 <br>F1 score makes use of a confusion matrix, which is given below.
 <br>F1 score uses both precision and recall:
 <br>F1 Score = 2 * (Precision * Recall) / (Precision + Recall)
 <brPrecision = TP / (TP + FP)
 <br>Recall = TP / (TP + FN)
 <br>
 ![image](https://github.com/bhargav-nvns/blizzard-and-temperature-prediction/assets/148454572/b5d4ba75-876c-4ad3-9bcf-f3dd3bf0d770)

 # the entire project file is in the file named "project".
