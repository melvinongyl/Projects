During my masters programme, I worked on an assignment which contains a deep learning model leveraging the MobileNetV2 architecture, fine-tuned
for the CIFAR - 10 image classification task. The model is implemented in Pytorch, taking advantage of 
transfer learning and customer layers, including a dropout layer for regularization. It uses a dynamic 
learning rate with a scheduler and implements early stopping based on test accuracy to prevent overfitting. 
The model aims for a 85% accuracy target, and the this folder contains the code for training, evaluation, and 
checkpointing to capture the best performing model. 