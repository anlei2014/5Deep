# 5Deep
SUPINFO-PROJECT -2021年03月24日

# File description
  ## 5Deep.ipynb --It is a general image enhancement plus CNN，And used to generate the model。
  ## 5pre --It is the picture predicted by the loaded model, which contains two folders cat and wolf
  ## useModelPre.ipynb --Use the model to predict
  ## 5deep-resnet.ipynb -- It is a model using resnet

# author: anlei


# Project requirements
Data set source  ：  https://dm.kaist.ac.kr/datasets/animal-10n/

This is an image classification problem with 10 classes, c.f. the “readme” file.
You have to build from scratch your own convolutional neural network to solve this problem. Using a pre-trained model and perform transfer learning is only allowed in the bonus part.
Each step of your project must be fully commented.
Obviously, you will try different networks before achieving your objective. Describe not only your final models but also your attempts.
Your rendering will take the form of a zip archive containing a fully commented Jupyter notebook and the saved model.
You will necessarily use the library Keras.
          1. Load the data set. It is already split in train data and test data.
          2. Perform image augmentation.
          3. Build your convolutional neural network. It must contain at least the following
          elements: convolutional layers, pooling layers, dropout layers, fully connected hidden
          layers. You are free to add other relevant elements.
          4. Compile your model and test its accuracy.
          5. Redo steps 3 and 4 with different structures and different values of the
          hyperparameters.
          6. Save your final model.
          7. Use your model with your own photos or some photos find on internet.
          8. Bonus: use a pre-trained model like ResNet to improve your results.
