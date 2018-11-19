# ICCAD-18_Adversarial_Training
This repository has the source code to repeat the experiments presented in the ICCAD18 paper title: Enhancing Adversarial Training towards Robust Machine Learners and its Analysis.

The link to the paper is: 
http://delivery.acm.org/10.1145/3270000/3267502/a78-manoj.pdf?ip=129.174.182.28&id=3267502&acc=OPENTOC&key=B33240AC40EC9E30%2EB

DATASET: Mnist Digits and Mnist Fashion are datasets used for experimentation and can be found online. You can also use other datasets like cifar-10

MODELS: The model folder consists of two models, Artificial Neural Network and Re-trained ANN model(Adversarial Training). You can even use your own  models (ANN,DNN,CNN) instead of the one's provided

ATTACK: Attack folder consists of the different attacks and can be easily adapted to be used. For example, you just need to provide the attack models with the ANN model or your model (ANN,DNN,CNN) and execute the attack.

LIBRARY SUPPORT: Keras, Tensorflow, Numpy, Pandas, Matplotlib and adversarial attacks are modelled using Cleverhans
