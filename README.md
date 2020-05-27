# CNN-Sign-ASL-fingerspelling-classifier

The "CNN for the american Manual Alphabet.ipynb" is a convolutional neural network, which classifies the letters of the ASL fingerspelling alphabet (- J and Z, which require movement) from the Kaggle Sign Language MNIST dataset. Additionally an openCV feature is added, where one can sign the letters in front of the webcam in the white frame of the video feed. The classifyer will try to predict your sign. It works best on a white even background. 

The "CNN MNIST.ipynb" is just there to try out the CNN on the digit MNIST data. 

This was build as part of an exam in the Data Science course for the Cognitive Science master at Aarhus University. 


### Data for the CNN can be downloaded here: 

Sign language MNIST 
https://www.kaggle.com/datamunge/sign-language-mnist?select=amer_sign3.png (Files are too big to upload here)

Digit MNIST 
https://keras.io/api/datasets/mnist/ (However, this is included in Keras and downloads within the code) 

### Requirements: 
> Tensorflow 2.0  
> Numpy  
> Pandas  
> CV2  
> Matplotlib  
> Pydot  
> Seaborn  
> A computer webcam (build in)   




#### Code is written with assistance from the follwing pages: 

> Digit MNIST with keras 
> https://nextjournal.com/gkoehler/digit-recognition-with-keras
> 
> Save and load neural network models with tensorflow: 
> https://www.tensorflow.org/guide/keras/save_and_serialize
> 
> Print model layout 
> https://www.tensorflow.org/api_docs/python/tf/keras/optimizers/Adam
> 
> Create confusion matrix 
> https://androidkt.com/keras-confusion-matrix-in-tensorboard/
> 
> OpenCV convert webcam to greyscale 
> https://techtutorialsx.com/2019/04/13/python-opencv-converting-webcam-video-to-gray-scale/
> 
> Tensorflow how to code a neural network 
> https://www.tensorflow.org/tutorials/quickstart/beginner
> 
> OpenCV guide 
> https://realpython.com/face-detection-in-python-using-a-webcam/
> 
> Finger counting open CV 
> https://github.com/jaredvasquez/CNN-HowManyFingers
