
Programs written while working through http://deeplearning.net/tutorial/deeplearning.pdf 

Original source code for book and data sources are here https://github.com/lisa-lab/DeepLearningTutorials.git

Theano documentation is here: http://deeplearning.net/software/theano/#documentation



This is a place to store the code I write while working through "Deep Learning Tutorial"

My code is in Python 3, book and sample code is Python 2. Not sure which version of Theano he's using, I'm on 0.7/0.8, some minor changes were needed to get his code working running.

I'm also trying to keep each example net self contained instead of broken into separate files like book examples. This is so I can easily drop a network with only the parts I need into a new project. Once that's done it'll be easy to put the various classes back into separate files.


* see the MachineLearning Resources.md file for a list of tutorials, books etc on Deep Learning 

<b>Theano examples</b>

Logistic Regression 

Multilayer Perceptron

Basic Convolutional Network to filter images

LeNet5

Denoising Autoencoders

Stacked Denoising Autoencoders 

Restricted Boltzmann Machine 

Deep Belief Network 

Hybrid Monte-Carlo Sampling 

Elman-Recurrent (Python 2.x-3.x and replaced PERL script with slow but working Python)
                ( clean up code, fix a few bugs )


LSTM for Sentiment Analysis I converted the example code to process a series of ints and predict next int in series instead.

RNN-RBM to model and sequence music ( I changed this to handle chars from reading in plain text )


<b>Not in the book:</b>

Deep Reinforcement Learning (WIP, the Theano code needs streamlining but it works)

Single layer RNN to read in sentences and generate new sentences

<b>TensorFlow Examples</b>

Programs written while working through Manning 'Machine Learning with TensorFlow'
(https://www.manning.com/books/machine-learning-with-tensorflow )

* I'm only posting the examples that I change, you can find all the book code here:
https://github.com/BinRoot/TensorFlow-Book

LogisticRegression_tf ( cluster some generated data with Logistic Regression )

KMeans_tf ( read in dir of .wav files, compute frequency, notes, histograms, cluster with KMeans )

SOM_tf ( Self organizing map that organizes an array of colors )

Reinforcement_tf (Reinforcement ( QLearning) on a single stock )

LSTM_tf (LSTM on airline passenger volume year over year)

<b>Not in the book:</b>

HelloWorldSeq2Seq.py  ( translates Hello to World )

<b>Notes</b>
That's probably it for this project, I have enough skeleton code to jump start several projects 




