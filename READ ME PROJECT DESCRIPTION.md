This is a research project I completed to evaluate the characteristics of machine learning models 
and compare the performance differences between classical machine learning models vs their quantum 
counterparts in performing the task of categorical classification. The machine learning models I looked at 
included a Support Vector Machine and variations of the Neural Network model. More specifics about the 
functionalities of each model can be seen in the "Quantum Machine Learning Report" file. Here are the 
specifics of each file:

BinaryCNN.ipynb - this is a binary convolutional neural network. Convolutional neural networks are
more designed for image classification and this shows in the performance of the model as it performed
rather poorly compared to the other models. 

MulticlassNN.ipynb - this is a multiclass neural network. This was designed in response to the poor 
outcomes of the convolutional neural network models I designed. This is more designed for raw data and 
there were significant performance increases compared to the CNN models. 

Quantum Machine Learning Report.pdf - This is the summary of most of my research. 

SVM.ipynb - this is a classical support vector machine. Support vector machines typically perform well
when given tasks of classification and regeression.

VQC QNN.ipynb - this is a variational quantum classifier quantum neural network. This was easily the hardest
model to design, but this is the quantum version of our classical neural networks.

VQC QNNadhoc.ipynb - this is another variational quantum classifier quantum neural network but operated 
successfully on a separate adhoc dataset. 

qsvm.ipynb - this is a quantum support vector machine. As the name states, this was used to compare to the 
classical support vector machine, its performance increases were not very significant in comparison to 
its classical counterpart. 

wine.csv - this is the dataset that was used to train and test these machine learning models. More specifics
can be found in the "Quantum Machine Learning Report" file, but this dataset consisted of many instances of wine
and the descriptive features of each like alcohol content and other chemicals. All these instances of wine could 
be classified into 3 different classes, and each machine learning model was tested to see if they could classify
them correctly into these 3 classes.
