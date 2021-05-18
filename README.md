# Spotify-Track-Popularity-Prediction.

## Team Members 
1. Arnav Bagchi (Roll No : 04, Class : D12C)
2. Jay Dulera (Roll No : 15, Class : D12C)
3. Rohan Ghosalkar (Roll No : 20, Class : D12C)

## Introduction
Here we are deciding wether or not a certain song will be a popular song (hit) or not. Our dataset consists of numerous songs which have been labeled according to different properties and types (loudness, duration, etc) and finally wether or not it was a hit song.

## Dataset
The datase consists of various spotify songs which are labelled with various properties of the song. For example,

- **Name** : Lucky Man
- **Artist** : Montgomery Gentry
- **Energy Level** : 0.471
- **Loudness** : 7.270	
.

.

.

.

- **Popular** : 1 (Yes)

## Software/Tools Used
* Jupyter Notebook
   
## Libraries Used
* Numpy
* Pandas
* Scikit-learn
* matplotlib
* seaborn

## Models 
We have used three models. 

### SUPPORT VECTOR MACHINE
SVM is a supervised machine learning algorithm that is commonly used for classification and regression challenges. In the SVM algorithm, each point is represented as a data item within the n-dimensional space where the value of each feature is the value of a specific coordinate. After plotting, classification has been performed by finding hyper-plane, which differentiates two classes. Refer to the below image to understand this concept.

### RANDOM FOREST ALGORITHM
The random forest algorithm is based on supervised learning. It can be used for both regression and classification problems. Random forests creates decision trees on randomly selected data samples, gets prediction from each tree and selects the best solution by means of voting. It also provides a pretty good indicator of the feature importance.

### MULTILAYER PERCEPTRON
Multi-Layer perceptron defines the most complicated architecture of artificial neural networks. A multilayer perceptron is a feed forward 
artificial neural network that generates a set of outputs from a set of inputs. An MLP is characterized by several layers of input nodes connected as a directed graph between the input nodes connected as a directed graph between the input and output layers.

## Result and Accuracy
Algorithm | Accuracy
---------- | -----------
SVM | 91.99
Random Forest | 93.00
MLP | 91.9

## Conclusion
We have acheived accuracy above 90% in each of the algorithms however we could implement more algorithms and get better efficacy too.
