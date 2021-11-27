# TIME-SERIES-Recurrent-Neural-Networks-

Exploring different RNN models and training procedures for a problem in time series prediction.

Building a model for predicting the number of sunspots. We work with a data set that has been published on Kaggle, with the description:
Sunspots are temporary phenomena on the Sun's photosphere that appear as spots darker than the surrounding areas. They are regions of reduced surface temperature caused by concentrations of magnetic field flux that
inhibit convection. Sunspots usually appear in pairs of opposite magnetic polarity. Their number varies according to the approximately 11-year solar cycle.
The data consists of the monthly mean total sunspot number, from 1749-01-01 to 2017-08-31.

Contents :
1) Load and prepare the data
2) Baseline methods
    a) "naive" method which simply predicts Y_t = Y_t-1
    b) AR(p) model
3) Simple RNN
4) Training the RNN model
    Option 1. Process all data in each gradient computation ("do nothing")
    Option 2. Random windowing
    Option 3. Sequential windowing with stateful training
5) Reflection
    
