# NIDS
Major project on Network Intrusion Detection System

## Repository Structure
Network-Intrusion-Detection-Using-Machine-Learning
  - Datasets
    - **Normal_data.csv** - CSV Dataset file for Normal data
    - **metasploit.csv** - CSV dataset file for attacks
    - **bin_data.csv** - CSV dataset for Binary labels

  - Labels
    - **le1_classes.npy** - Numpy file for ndarray containing Binary Labels

  - Models
    - **lst_binary.json** - Trained Long Short-Term Memory Model JSON File for Binary 
  
  - Weights
    - **lst_binary.h5** - Model weights of Long Short-Term Memory Model for Binary

  - Plots
    - **Pie_chart_binary.png** - Pie chart of Binary Classificatio
    - **lstm_binary.png** - Long Short-Term Memory Model Summary for Binary Classification
    - **lstm_binary_accuracy.png** - Long Short-Term Memory Accuracy Plot for Binary 
    - **lstm_binary_loss.png** - Long Short-Term Memory Loss Plot for Binary Classification
    - **lstm_binary_roc.png** - Multi Layer Perceptron Loss Plot for Multi-class 

## Dataset
The InSDN dataset (https://aseados.ucd.ie/datasets/SDN/)

## Prerequisites
 - Keras 
 - Sklearn 
 - Pandas 
 - Numpy
 - Matplotlib

## Running the Notebook
The notebook can be run on 
 - Google Colaboratory
 - Jupyter Notebook
 
## Instructions
 - To run the code, user must have the required Dataset on their system or programming environment.
 - Upload the notebook and dataset on Jupyter Notebook or Google
   Colaboratory.
 - Click on the file with .ipynb extension to open the notebook. To run
   complete code at once press Ctrl + F9
 - To run any specific segment of code, select that code cell and press
   Shift+Enter or Ctrl+Shift+Enter
