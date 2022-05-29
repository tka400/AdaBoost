## AdaBoost

AdaBoost algorithm based on stumps. Each followed model is being trained on resampled data.

You can follow my video manual on YouTube (на Русском) and create algorithm for classification

[![Alt text](https://img.youtube.com/vi/dmntCYtP4tQ/mq2.jpg)](https://www.youtube.com/watch?v=dmntCYtP4tQ)

or for regression

[![Alt text](https://img.youtube.com/vi/P5wfdDsTjm4/mq3.jpg)](https://www.youtube.com/watch?v=P5wfdDsTjm4)

The idea was taken from the article "AdaBoost.RT: a boosting algorithm for regression problems", Solomatine, Shrestha.
Several algorithms are explaned there, for classification and regressin problem. Also you can find Druker method.

This implementation trains Dicision Tree, then compares results with AdaBoost method.
At the end yot can explore the error, stumps weights and prediction.

![results](results.png)
