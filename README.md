# Inter-subject Attention Recognition from EEG with CNN-LSTM model
Final Project for University of Pennsylvania course CIS519 
## Team member
Xingqi Pan, Meiyi Yu, Haiqin Zhao

## Abstract
For this project, we tried to detect the human mental states from Electroencephalogram (EEG), a most studied time-sequential signal which has been proven to have the capacity to detect attention, with a Transfer Learning based state-of-the-art deep learning model, to improve study/work efficiency for various people in different scenarios. In this research, we proposed a framework based on the CNN-LSTM model which learns the inter-subject attentive mental state from multi-channel EEG signals. We also delivered an innovative method of EEG signal preprocessing which enhances the correlations among data without adding redundant information. The result shows that the model reaches an average accuracy of 69.36% on 5 participants for leave-one-out inter-subject attention recognition on a public dataset, which is higher than the similar CNN-LSTM model of 65.29% on single-channel EEG signals. It also points out the possibility of applying multiple EEG channels on mental state detection.

## Implementation
see ipynb

## Reference
J. Cui et al., "Subject-Independent Drowsiness Recognition from Single-Channel EEG with an Interpretable CNN-LSTM model," 2021 International Conference on Cyberworlds (CW), Caen, France, 2021, pp. 201-208, doi: 10.1109/CW52790.2021.00041.
