# SUTDML2021Project
SUTD ML 2021 Project

# Links 
#Colab
https://colab.research.google.com/drive/1ex6X5akmWNpCP4H7FgeyCg1RPnmiK9Qx

#Overleaf
https://www.overleaf.com/9837459215sdvwrhdwgwbh

# Team 
Arun (1005065),
Jay Bhatia(1005062), 
Joel Tan(1002738), 
Tomomasa Yamasaki(1006480),
Wei Zhou Sim()

# ideas / interests

## Jay Bhatia :  


### Option 1 Multivariate Multi-step Time Series Forecasting using Stacked LSTM for 61850 GOOSE Power Grid DataSet
https://www.tensorflow.org/tutorials/structured_data/time_series
https://www.analyticsvidhya.com/blog/2020/10/multivariate-multi-step-time-series-forecasting-using-stacked-lstm-sequence-to-sequence-autoencoder-in-tensorflow-2-0-keras/
### Option 2 HMM State classification for 61850 GOOSE Power Grid DataSet
https://livebook.manning.com/book/machine-learning-with-tensorflow/chapter-6/v-9/54

## Tomomasa Yamasaki :


### Option 1 Gaussian Process or K-NN for Human Activity Recognition using smartphones with embedded inertial sensors
Dataset: https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones#.    
Gaussian Process: https://en.wikipedia.org/wiki/Gaussian_process.    
Python sample program for Gaussian Process: https://www.tensorflow.org/probability/examples/Gaussian_Process_Regression_In_TFP.   
* The advantage of ML that I think: Care facility and hospital staff are busy with a lot of nursing care work. Therefore, it is difficult to understand each patient in detail. By automatically estimating the patient's physical activity from the data acquired from the smartphone, it is possible to know the detailed patient's condition without interfering with work. 
* The disadvantage of ML that I think: With the increasing automation of patient management, the work becomes too rational. Human communication may be reduced. 


### Option 2 Binarized Neural Network for NIH Chest X-ray Dataset of 14 Common Thorax Disease Categories
Dataset: https://nihcc.app.box.com/v/ChestXray-NIHCC/folder/36938765345.   
python sample program of Several types Binarized NN: https://github.com/itayhubara/BinaryNet.pytorch.  
  →This sample program is for MNIST or CIFAR10 dataset, so we should change dataset. 
* The advantage of ML that I think: Binarized NN has compact model size than fully CNN, so BNN can be applied for wearable devices. If BNN detecting Thorax Disease is activated on smaller device as a wearable device, patients feel free to know their thorax disease, right? People can know if they have thorax disease by only taking their chest X-ray even if they live in the place where they don't have enough doctors.
* The disadvantage of ML that I think: Machine learning can detect patient's disease instead of doctors. A few doctor who have no skills would loss their jobs?


## Joel :  


### Predicting memory device time-to-failure from device characteristics
Wear out leads to memory device failure over time. We can try to predict how long a device would last based on features like applied-voltage, applied-temperature, applied-magnetic field, internal magnetic field, resistance, switching probabilities, switching threshold voltages. I already have data from my own lab. Advantage: Breakdown of device is a complicated non-linear probabilistic process and hence hard to model. It is unknown whether it is possible to produce a useful estimator for device lifetime based on device features. Disadvantage: Might not have enough data (I have millions of samples). The resultant model is non-physical and best used for interpolation only. 
