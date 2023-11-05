# Plant-based-disease-detection

Crop diseases is a significant threat to food security, however their fast identification remains tough in several elements of the planet because of the shortage of the required infrastructure. Recent advances in the field of computer vision made possible for disease diagnosis from healthy and diseased plants through deep learning. In this project I am using PlantVillage dataset a publicly available dataset of diseased plant leaves collected under controlled conditions. Using CNN and Machine Learning can be use to identify the classification between diseased and healthy plants by their leaves condition.
# The steps are as follows.

1. Connect the colab to google drive to access the dataset.
2. Load TensorFlow, Keras and Python libraries.
3. Create small dataset for testing.
4. Load the VGG16 network.
5. Splitting the dataset into test, valid and train.
6. Train the model on training data.
7. Evaluate the model on test data.
8. Use the model for test data accuracy.

# why collab?

From my previous experience with the machine learning projects I choose to go with the google colaboratory. In my previous projects the setting up environment in an anaconda and pytorch is tough installing all the required libraries and everything was lot of problem for me. Setting up environment is one thing but running it on a laptop is a different thing due to hardware restriction on laptop most of the time my environment get crashed due to low hardware power.

As an alternative I got to know about the google colaboratory which is a free online cloud-based Jupyter notebook environment that allows us to train our machine
learning and deep learning models on CPUs, GPUs, and TPUs. In google colab hardware requirement of our laptop does not matter all you need a google account. The google drive act as storage for our dataset. we can upload the whole dataset into google drive or directly download the dataset into drive by using
colab commands. 

Only limit on google colab is storage and run time at a time we can use it for 8-12 hours sometimes it get disconnected when it experience a heavy load but the good thing is storage which helps to store the data so we can’t loose the trained data due to run
time error if it gets disconnected.

In google colab I uploaded the PlantVillage Dataset into my google drive then I linked my google drive with the google colab and then I started my project without any hassleand without need of any hardware requirement. For this project I used tensorflow 2.0 and libraries like numpy, matplotlib, sklearn and tensorflow 2.0 library
