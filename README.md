## CNN:

##### The advancements in Computer Vision with Deep Learning has been constructed and perfected with time, 
##### primarily over one particular algorithm — a Convolutional Neural Network. A Convolutional Neural Network 
##### is a Deep Learning algorithm which can take in an input image, assign importance - learnable weights 
##### and biases to various aspects/objects in the image and be able to differentiate one from the other

### Why CNN?

##### Resolves the problem of not identifying a image/patern at any any location of the pic i.e It learns 
##### about the patterns that exist and then predict when we load the image to a model. Using Convolutions
##### is like scanning over the image with a magnifying glass/Filters.
![1](https://user-images.githubusercontent.com/69350191/127884137-ac792b4f-6568-4a1d-833c-a0e0564c0c9e.PNG)

### Code:

##### The code focuses on X-Ray scans of a covid and Non Covid patients. The algorithm had an accuracy of 91%
##### in train stage and 96% for test set, Clearly the data set used isn't enough. As per observation it yet times 
##### reaches 100% accuracy - "Overfiting the data"
![2](https://user-images.githubusercontent.com/69350191/127884510-3fe1509c-6d4f-4dae-8c74-929de5ddce0d.PNG)
##### As we can observe the loss vs iteration isn't ideal case but acceptable for demonstration considering 
##### epochs is 10 - 15 range.

#### Possible Solutions: 
  ###### Increase the epochs to 100, 1000.
  ###### Adding more data set to train set
  ###### Tunning the hyperparameters if requried 
  ###### Can be improved with more computation power

