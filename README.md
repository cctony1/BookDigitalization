In this short project, I built classifiers for images and sequences of images (videos). The binary classification problem of interest for this book digitalization process includes the two classes, 'page flipping' and 'page not flipping'.

Goals:

    Build a model that exhibits a high f1-score for binary classification of images.
    Adapt the model for binary classification of videos containing the actions of either 'page flipping' or 'page not flipping'.

I achieved a macro average of f1 = 98% for image classification, and 90% for video classification.

The final models were both convolution nets. The video classifier involved a time distributed architecture in order to simultaneously work on sequences of images, which were then fed into a Gated Recurrent Unit (GRU).

One really useful tool that I familiarized myself with during this project is the python generator. I used the Keras ImageDataGenerator and a video-analog of this to read (and augment) images and sequences from directories.


6AxFRoS5jafBIap1
