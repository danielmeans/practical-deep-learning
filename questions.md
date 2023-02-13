- Do you need these for deep learning?

Lots of math - False
Lots of data - False
Lots of expensive computers False
A PhD False
- Name five areas where deep learning is now the best in the world.
1. Natural Language Processing
2. Computer Vision
3. Medicine: Finding anomalies in radiology images
4. Biology: Folding and classifying proteins
5. Image gneration
- What was the name of the first device that was based on the principle of the artificial neuron?
The perceptron, specifically the Mark I perceptron. 

- Based on the book of the same name, what are the requirements for parallel distributed processing (PDP)?
1. processing units
2. state of activation
3. output funcion per unit
4. connectivity between units
5. propagation rule for propagating activity through connections
6. activation rule, combine inputs to a unit to produce output
7. learnign rule, patterns of connections are modified by experience
8. An environment for the system to operate

- What were the two theoretical misunderstandings that held back the field of neural networks?
 Misunderstood that a single extra layer (two layers), would be enough to approximate most mathematical fns
 In practice they were two big/slow to be useful

What is a GPU?
- A graphical processing unit, capable of executing thousands of single tasks at the same time
Open a notebook and execute a cell containing: 1+1. What happens?
- The result is 2, from a python3 kernel notebook. 

Follow through each cell of the stripped version of the notebook for this chapter. Before executing each cell, guess what will happen.

Complete the Jupyter Notebook online appendix.

Why is it hard to use a traditional computer program to recognize images in a photo?
- Extremely hard. You'd have to teach a program how to recognize each characteristic of an image, like edges, colors, gradients, shapes. 

What did Samuel mean by "weight assignment"?
- Weight assignment are the variable values in a model that determine how the model will act on a given input to produce an an output. 
What term do we normally use in deep learning for what Samuel called "weights"?
- Parameters. 

Draw a picture that summarizes Samuel's view of a machine learning model.
- TO DO

Why is it hard to understand why a deep learning model makes a particular prediction?
- It's difficult to determine what part of all the layers, weights, hyper parameters, etc. actually led to that prediction

What is the name of the theorem that shows that a neural network can solve any mathematical problem to any level of accuracy?
- Universal Approximation Theorem

What do you need in order to train a model?
- Labeled data.

How could a feedback loop impact the rollout of a predictive policing model?
- The model could take in past data, including it's biases. This leads to more policing of people of certain demographics, which the model takes as input, and further reinforces that bias. 

Do we always have to use 224×224-pixel images with the cat recognition model?
No, we can choose the size of the image. The bigger the size, the more details the model can notice, at the expense of memory consumption.

What is the difference between classification and regression?
- Classification gives a categorical output whereas regression trys to predict a numeric quantity. 

What is a validation set? What is a test set? Why do we need them?
- A validation set is a set of data set that the model doesn't see during training, use to test model performance during training. 

What will fastai do if you don't provide a validation set?
- It'll create a validation set for you.

Can we always use a random sample for a validation set? Why or why not?
- No, that won't be helpful for time series data, where it's easy to predict randomly missing sampled data from a full set. Rather in that case we'd use the end of the dataset so that we can use the past to predict the future.

What is overfitting? Provide an example.
- Overfitting is when a model is trained to remember/memorize the specifics of the training set in a way that doesn't generalize.
- A good example is taking a set of points that follow y=x^2, and adding a small bit of random noise. To learn the function, a model might overfit to the random noise, instead of seeing the true y=x^2 function. 

What is a metric? How does it differ from "loss"?
- A metric is numerical value used to assess the performance of the model. Loss is a 

How can pretrained models help?
- Training is expensive , especially for large models. Pretrained models have already been trained for a task using a large dataset,
- they can be finetuned to fit your specific task. 

What is the "head" of a model?
- The head are the last few layers of a pre-trained model where the weights are adjusted to fit the specific dataset/task at hand/ 

What kinds of features do the early layers of a CNN find? How about the later layers?
- The early layers find edges, color gradients, the later layers find shapes, or parts of an image.

Are image models only useful for photos?
-No, they been applied in detecting malware, audio recognition and several other tasks. 

What is an "architecture"?
- The functional form of a model 

What is segmentation?
- Training a model to recognize every pixel in an image

What is y_range used for? When do we need it?
- It indicates the range of continuous values that the outcome variable can take. 

What are "hyperparameters"?
- The are parameters for paramters, high-level parameters that govern the meaining of the weight parameters. 

What's the best way to avoid failures when using AI in an organization?
Understanding test and validation sets.