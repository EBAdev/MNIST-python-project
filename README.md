### Overvejselser
* Overvej at skrive linalg om til kun at være matricer, også benytte boolean til at vuderer om noget er en vektor eller ej.
    * formålet ville være at vi ikke hele tiden skulle konverterer den ene til den anden
    * Det ville være mere uoverskuerligt

### Final IPSA project
In this project we are going to create a very simple neural network (linear classifier) to identify the handwritten digits from the MNIST database - often considered the “Hello World” problem in neural networks. In this problem we are given grayscale images of size 28 × 28 showing handwritten digits and are going to classify them into the 10 classes 0 - 9, depending on the digit depicted in the image. The MNIST database consists of 60.000 images to train your network on and 10.000 images to test the quality (accuracy) of the resulting network. For all images the correct label 0 - 9 is part of the database. There exist many of-the-shelf modules for this problem in Python, e.g. Keras, TensorFlow, scikit, and PyTorch, but in this project we are going to build a solution using pure Python from scratch.

A good introduction to the topic are the following four videos from the YouTube channel by 3BLUE1BROWN: Neural Network (19:13), Gradient Descend (21:00), Backpropagation (13:53), and Backpropagation Calculus (10:17). The few mathematical equations required in this project for performing simple backpropagation are stated explicitly below.

In this project we are going to create a very simple neural network (linear classifier) to identify the handwritten digits from the MNIST database - often considered the “Hello World” problem in neural networks. In this problem we are given grayscale images of size 28 × 28 showing handwritten digits and are going to classify them into the 10 classes 0 - 9, depending on the digit depicted in the image. The MNIST database consists of 60.000 images to train your network on and 10.000 images to test the quality (accuracy) of the resulting network. For all images the correct label 0 - 9 is part of the database. There exist many of-the-shelf modules for this problem in Python, e.g. Keras, TensorFlow, scikit, and PyTorch, but in this project we are going to build a solution using pure Python from scratch.

A good introduction to the topic are the following four videos from the YouTube channel by 3BLUE1BROWN: Neural Network (19:13), Gradient Descend (21:00), Backpropagation (13:53), and Backpropagation Calculus (10:17). The few mathematical equations required in this project for performing simple backpropagation are stated explicitly below.

