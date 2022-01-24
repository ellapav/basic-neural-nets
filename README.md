In neuralnet.ipynb we consider the data of people applying for credit cards, and a banker has placed them in one of the following categories:

Approved (1)

Denied (-1)

Each data point has 16 associated features (found in credit_data.csv) and a corresponding label (found in credit_label.csv).
(# data = m = 653, # features = n = 16)



The goal in this program is to create an artificial neural network (ANN) model with 3 layers. 

Layer 1: 30 neurons and linear transfer function for the activation function.

Layer 2: 30 neurons and tanh function for the activation function. 

Layer 3: (output layer) 2 neurons and softmax for the activation function.


We consider the data for two cases: data is unchanged, and data is normalized by the maximum value of each feature. 


%------------------------------------ Required Packages --------------------------------------%

	tensorflow    (this notebook is compatible with v1, caution if you have v1 or v2 downloaded)
  
  numpy
	
	matplotlib
	
	scipy
	
  sklearn
