# Facerecogniton-using-transfer-learning-
Deep CNN may take days or even weeks to train on very large dataset
A way to shortcut this process is to re-use the model weight from pretrained model
Transfer Learning involves using model trained on one problem as a starting point on related problem
What is Transfer Learning?

Transfer Learning generally refers to a process where a model trained on one problem is used in some way on a second related problem
In deep learning, transfer learning is a technique whereby a neural network model is first trained on a problem similar to the problem that is being solved . One or more layers from the trained model are then used in a new model trained on the problem of interest.
I am going to use the pre-trained model approach for making Face recognition system. I am using the weights of the VGG16 model which is trained on the Imagenet dataset.
