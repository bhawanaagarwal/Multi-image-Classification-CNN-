# Multi-image-Classification--CNN-
</br>
This repository contains an image classification model that allows you to classify images into any number of classes. The only requirement is to organize the images into folders corresponding to the desired classes. In the provided example, we chose 9 classes: honeybee, bumblebee, ants, butterfly, milkweedbug, beetle, grasshopper, snail, and dragonfly. You can easily adapt the code to classify images into a different number of classes without altering a single line of code.

One thing to note is the use of the SparseCategoricalCrossentropy loss function in this code, which is suitable when dealing with more than two classes. If you're working with only two classes, it's necessary to switch to Binary Cross Entropy loss. Alternatively, you can define a variable at the beginning of the code to dynamically assign the appropriate loss based on the number of classes. (I thought of this while explaining and will update the code soon.)
