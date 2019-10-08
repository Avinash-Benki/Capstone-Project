**Machine Learning Engineer Nanodegree Capstone Proposal – Speech Recognition Using Tensorflow**

Avinash Benki
October 8th, 2019

**Data Source

This project uses the Speech Commands Dataset, a set of 64,721 1-second .wav audio files each consisting of 1-of-30 single spoken English words. These words are from a small set of commands and are spoken by a variety of different speakers. The audio files are organized into folders based on the word they contain, and this data set is designed to help train simple machine learning models. 6 additional audio files for different types of common noise were also included, though not employed in this project. 

The dataset for this project was downloaded at https://www.kaggle.com/c/tensorflow-speech-recognition-challenge/data. Data was released by Google on August 3, 2017.

**Libraries and Software needed

-	SciPy - Python's scientific computing library; used in this project to directly decode PCM-encoded audio files at a rate of 16000 Mbps and to perform Discrete Cosine Transforms during MFCC calculations
-	Numpy - library useful for handling and processing arrays of values and objects; used in this project to manage data and for performing Discrete Fourier Transforms during MFCC calculations
-	Matplotlib and Seaborn – For audio files data visulaizations.
- Keras with TensorFlow backend - Keras provides a high-level programming interface for deep learning and neural network development; Keras runs on top of TensorFlow, a library and engine for dataflow programming; used in this project to develop and train the neural networks and for one-hot encoding all target labels
-	Glob - standard Python file searching library; used in this project to extrapolate filenames and paths for all audio files
- OS - standard Python operating system interface; used in this project to combine strings and values into valid file pathnames
-	Math - standard Python mathematical functions; used in this project to calculate frequency bins in MFCC calculations


