# Project Objectives
1. Design, implement, debug, evaluate, and benchmark deep convolutional neural network architectures (and/or its variants) for a dataset created and curated by yourself with at least a 1000 images (NO pre-cleaned datasets, but you can collect images from the internet).
1. Compare performance with a basic basic fully convolutional neural network model with a few filters and one or two layers.
1. Study the effect of data augmentation, regularization, and transfer learning.

# Project Expectations
1. You will work on your projects individually (i.e. group submissions are not allowed).
1. All reports including the final report must be prepared using <a href="https://www.overleaf.com/">Overleaf</a>.
1. Each of you will review at least two reports of the peers in your group.

# Project Phases

## 1. Data preparation
1. Collect the images or take pictures
1. Crop/resize them all to same dimensions (height = width)
1. Visualize sample images and discuss the distribution of output labels
1. Discuss data normalization

**What to submit?**  
a) A link to your Colab notebook (make sure that anyone with the link can view)  
b) A PDF report describing your findings  

## 2. Build an overfitting model
1. Build a model Compare the results of the neural network with a linear regression or logistic regression model
    - Start with a basic model and then grow your model into a multi-layered model
    - Discuss how neural network models will be selected
    - Document your performance comparison
1. Study performance difference when linear activation is used instead of sigmoid (and vice versa)
   - How does your performance change when linear activations are used instead of sigmoid, in the last neuron and all other neurons?
1. Data spliting into training, and validation sets

a) what architecture do you need to overfit the data?
b) what architecture do need to overfit when you have output as input?



1. Plot your learning curves and include them in your report
1. Discuss what architecture (how big) you need to overfit the data
1. Discuss what architecture (how big) you do need to overfit when you have output as additional input feature
1. Evaluate your predictions (using Precision, Recall, MAE, MSE, etc.)
1. Code a function that represents your model
   - After your model is trained, read all the weights, and build your own function/method that serves as the model
   - Verify that predictions you obtain are same as the one you obtained using your trained model

**What to submit?**  
a) A link to your Colab notebook (make sure that anyone with the link can view)  
b) A PDF report describing your findings  

## 3. Feature importance and reduction
1. Study feature importance by iteratively removing input features
1. Identify non-informative input features and remove them
1. Compare your feature-reduced model with the original model with all input features

**What to submit?**  
a) A link to your Colab notebook (make sure that anyone with the link can view)  
b) A PDF report describing your findings  

## 4. Address peer-review comments
* You will receive comments/reviews from at least two peers in the classroom

**What to submit?**  
a) A PDF report describing the comments you received and how you addressed them  

## 5. Poster presentation (final exam)
* Prepare a poster highlighting the problem, diagrams, your results, plots, etc.
* Poster and final report will be evaluated based on all the criteria above.
* Report and poster presentation grades will be average of (a) grades by the course instructor (b) peer grades, and (c) grades by external visitor/s from industry
* See sample-reports folder and sample-posters folder for samples

**What to submit?**  
a) A copy of your final report  
b) A link to your final Notebook

**What to bring?**  
a) A printed copy of your final report  
b) A link to your final Notebook
c) Your poster  
d) A laptop for demonstration (if needed)  



## Project Objective
Design, implement, debug, evaluate, and benchmark a deep learning method on a dataset you create or curate.

## Evaluation Criteria
1. [3 points] Effort to curate/create your dataset (at least a thousand records/images)
   - Preprocessing (e.g. lowering resolution), cleaning, data summary
   - Outliers analysis
   - Data augmentation (if needed)
2. [3 points] Effort to visualize input data
   - Example, draw plots, visualize all images in groups
   - Novel visualizations/plots can get you bonus points. For example, plots involving 3 or 4 columns
3. [3 points] Effort correctly split data into 3 sets
   - Randomization
4. [3 points] Effort to design and test various neural network architectures
   - Why did you choose the architecture you chose?
   - How does the performance change if linear regression or logistic regression is used?  
5. [3 points] Effort to evaluate your results
   - Discussion of predictability of your model on the data you used
6. [3 points] Effort to benchmark your method / results
   - Comparison with state-of-the-art methods
7. [3 points] Documentation efforts (report preparation)
   - Documentation of all steps above
8. [3 points] Effort to document the training time
   - Relationship between training time, epochs, dataset size
9. [3 points] Effort to study learning curves
   - Plots of epoch vs loss on training / validation datasets  
10. [3 points] Effort to prepare a "reproducible" Python Notebook (.ipynb) file
    - a Readme.txt file that outlines the steps for reproducing everything
    - Hosting online is encouraged (such as GitHub)  

## Example 1:
The goal in this project is to develop a convolutional neural network model that can identify my mood looking at a picture of my face. Take 1000 pictures of your face in various settings - 200 smiling, 200 laughing, 200 sad, 200 crying, and 200 neutral. Then, tagged each of those pictures manually. Next, randomly spit the data into - 600 pictures for training, 200 for validation, and 200 for testing. Cropp images to 256 x 256 dimensions. Write a Python matplotlib code to visualize all the 1000 images. Next, build a single layer CNN model with 64 filters. Data augmentation could significantly improve the performance. The 5-class accuracy of a random classifier is 20% (baseline for the project).

<img src="mood-classification-project.png" align="middle" width="700"/>

## Example 2:
The goal in this project is to develop a convolutional neural network model that can print digital time from the picture of a digital clock (or even analog clock). Rest is similar to Example 1.

<img src="read-clock-project.png" align="middle" width="700"/>


Note: This is a living document and will be updated (with more details) throughout the semester. 
