# multilayer-perceptron
In this project, I implemented a multilayer perceptron entirely from scratch with the only non-standard dependency being a matrix library I also created. I started by creating a simple one-layer perceptron that could differentiate between the digits '0' and '1'. After achieving that, I decided to try and classify all digits from '0' to '9', which required a neural network capable of non-linear classification and the multilayer perceptron was the natural choice. The implementation involved one input layer, one output layer, and an arbitrary number of hidden layers in-between.

To train my MLP to classify handwritten digits, I used the MNIST dataset, which contains 60,000 training images and 10,000 testing images of handwritten digits. Each image was a 28x28 grayscale image with each pixel represented by a value between 0 and 255. To preprocess the data, I normalized the pixel values to be between 0 and 1 and flattened the images into 1D arrays.

Throughout the project, I gained a deeper understanding of neural network and machine learning fundamentals, such as forward and back propagation, loss/cost functions, and gradient descent. I also gained a better understanding of the calculus underlying gradient descent, especially the chain rule. Overall, the project allowed me to consolidate my knowledge of these concepts and apply them to a real-world problem.

This repo is just the stand-alone multilayer perceptron, to see the full-stack web-app that utilizes my trained multilayer perceptron, and was built (mostly) from scratch, check out my github page.