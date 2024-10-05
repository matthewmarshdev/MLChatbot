# Implementation of a simple AI-Powered Chatbot

No license, open use to all, created by Matthew Marsh, 9/23/24

# Packages needed to run code:

numpy
nltk
nltk.download('punkt') --if necessary. Only needed once
torch
random
json
NeuralNet

import instructions found in each file

# to run the Chatbot:

1. Assure all files are loaded locally and are in the correct structure
2. Assure an interpreter is selected that can use all packages (I use Conda)
3. Make any upgrades as needed to the intents json, or redo it with specific intents
  a. mulitple intents files are provided, feel free to try them all
4. Open train.py file and check epoch runs or make hyperparam adjustments
  a. For most purposes, 3000 Epochs ended with 0.000 loss for shorter intents
5. (if desired) Change model layers for additional convolution
6. Assure that a data.pth file is created after training. This holds training information
  a. delete this file before rerunning trainer
7. Run chat.py 
  a. Chat bot runs in the terminal, and uses trained NN to hold a conversation!