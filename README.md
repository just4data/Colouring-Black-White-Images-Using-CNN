# Black and white image colourisation with OpenCV and Deep Learning

![image](https://user-images.githubusercontent.com/44177495/192515814-c682accc-2dda-4512-9325-0072e399e82f.jpg)

In this project repository, you will learn how to colourise black and white images using OpenCV, Deep Learning, and Python.


Image colourisation is the process of taking a black and white image as an input and returning an automatically coloured image as the output. Previous methods for image colourisation relied on manual human annotation and often produced desaturated results that were not believable as true colourisations.

In this notebook, we're gonna use a CNN (Convolutional Neural Network) model for colouring vintage black and white photos. This approach is a pre-trained model by [Richard Zhang](https://richzhang.github.io/colorization/), where he implemented an Artificial Intelligent (AI) approach as a feed-forward pass in a CNN at test time then trained on over a million colour images. The reason for choosing this model over to train our own model is because the author has trained his model using millions of images. Due to the lack of such a large number of images and lack of computation power to train such a large number of images, we are using his pre-trained model.
