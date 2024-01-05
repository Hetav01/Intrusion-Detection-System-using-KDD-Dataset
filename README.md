# Intrusion-Detection-System-using-KDD-Dataset

# About the Project.

Intrusions are considered the bane of the world of cybersecurity.
Hence, developing a strong intrusion detection system which can
be used to detect abnormal network connections before hand is
vital. In this project, a simple intrusion detection system trained
on the KDD-99 dataset was demonstrated. 

This dataset is considered a **classical benchmark** for developing intrusion detection systems in the world of cybersecurity.

I formulated and tackled multiple problem statements in the project(***These are explained in detail in the report attached***).
1. Perform some kind of feature reduction process to make the dataset easier
to understand for the model.
2. Perform a binary classification on the 2 classes: NORMAL, ANOMALY.
   - Using Standard Scaler and Over Sampling
   - Using Robust Scaler and Over Sampling
3. Perform a multi-class classification on the 5 classes: NORMAL, DOS,
PROBE, R2L, U2R using the same pipeline(Standard Scaler).
4. Perform Hyperparameter Tuning

# Steps to run the code.
1. Clone this repository.
2. Use a .ipynb compatible IDE like [Google Colab](https://research.google.com/colaboratory/), [Jupyter Notebook](https://www.anaconda.com/download), [Pycharm](https://www.jetbrains.com/pycharm/download/) or [Visual Studio Code](https://code.visualstudio.com/download).
3. Run the files in order of the Project:
    - Standard Scaler
    - Robust Scaler
    - Multi Class
4. Rejoice the code ran!

