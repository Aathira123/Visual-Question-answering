

This is a simple Demo of Visual Question answering which uses pretrained models (see models/CNN and models/VQA) to answer a given question about the given image.

## Dependency
python3 version - 3.5
1. Keras version 2.0+
2. Tensorflow 1.2+
3. scikit-learn -0.18
4. Spacy version 2.0+
    * Used to load Glove vectors (word2vec)
    *To install Glove Vectors
       * python -m spacy download en_vectors_web_lg
5. OpenCV 
    * cv2 version -4.2.0
6. VGG 19 Pretrained Weights
    * Weights can be downloaded online
### How to run

1.python demo.py </br>
2.Then click on ImageCroppingPro executable file .</br>
3.Browse for image and type down question in textbox and click submit</br>
4.The answer will be displayed on answer textbox.</br>
5.Click reset to try for another image</br>









