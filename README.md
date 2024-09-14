This study evaluates the performance of various deep learning models—Artificial
Neural Networks (ANN), Convolutional Neural Networks (CNN), Long Short-Term Memory
networks (LSTM), and Recurrent Neural Networks (RNN)—in classifying speaker age and
gender across several categories. The classifications include age determination without
gender information, with perfect gender information, and with male or female identification, 
in addition to speaker gender classification across three age groups. Features were
extracted using Mel-frequency Cepstral Coefficients (MFCC), and the models were trained
on Mozilla Voice Data 7.0.
The results indicate that the ANN model excelled in detecting senior adults, achieving
a precision of 92%, recall of 85%, and an F1-score of 89%, with an overall accuracy of
87%. The CNN model followed closely with an accuracy of 83%, performing well for
adults and seniors but struggling with teenagers. The LSTM and RNN models exhibited
lower accuracies of 71% and 72%, respectively, highlighting challenges in distinguishing
younger age groups. Both the CNN and ANN models achieved impressive 96% accuracy in
gender classification, surpassing the RNN’s 93% and LSTM’s 92%. Overall, these findings
underscore the effectiveness of ANN and CNN models in age and gender classification
tasks, suggesting that future work should focus on optimizing recurrent models and
refining feature extraction techniques to enhance performance across all demographics.
