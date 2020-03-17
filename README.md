

This is a simple Demo of Visual Question answering which uses pretrained models (see models/CNN and models/VQA) to answer a given question about the given image.

## Dependency

1. Keras version 2.0+
 

2. Tensorflow 1.2+
    

3. scikit-learn
   

4. Spacy version 2.0+
    * Used to load Glove vectors (word2vec)
    * To upgrade & install Glove Vectors
       * python -m spacy download en_vectors_web_lg

5. OpenCV 
    * OpenCV is used only to resize the image and change the color channels,
  

6. VGG 16 Pretrained Weights
    * Please download the weights file [vgg16_weights.h5](https://drive.google.com/file/d/0Bz7KyqmuGsilT0J5dmRCM0ROVHc/view)

## Usage

> python demo.py -image_file_name `path_to_file` -question "Question to be asked"

e.g 

> python demo.py -image_file_name test.jpg -question "Is there a man in the picture?"





Expected Output :
095.2 %  train
00.67 %  subway
00.54 %  mcdonald's
00.38 %  bus
00.33 %  train station


## Runtime

  * GPU (Titan X) Theano optimizer=fast_run       : 51.3 seconds
  * GPU (Titan X) Theano optimizer=fast_compile   : 47.5 seconds
  * CPU (i7-5820K CPU @ 3.30GHz                   : 35.9 seconds (Is this strange or not ?)

