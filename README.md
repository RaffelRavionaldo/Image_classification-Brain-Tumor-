# Image_classification-Brain-Tumor-
Use Functional API with tensorflow and pytorch

Train image classification with this dataset: https://www.kaggle.com/datasets/thomasdubail/brain-tumors-256x256

we train the image classification model with tensorflow and pytorch with the same structure.

we get tensorflow model have training accuracy = 77% and validation accuracy = 72% and pytorch model with training acc = 81% and validation acc = 78% and we train faster with pytorch then tensorflow.

if we want to increase the training accuracy, we can train longer or train the bigger model (in this case, we can add block_e etc)

but if the model overfits, we can do regularization like using a dropout layer, more data and more data augmentation.

You can this model for another dataset, but don't forget to change num_classes variable (the value on it is the number of your dataset label).
