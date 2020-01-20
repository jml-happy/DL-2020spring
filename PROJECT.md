# Project Objectives
1. Develop a feedforward neural network architectures for a pre-cleaned tabular dataset (NO time-series data, NO image data,  NO text data, only standard tabular data) with at least a 1000 rows and at least 3 input features (columns) using Tensorflow.
1. Compare the performance with a logistic regression model (for classification) or linear regression model (for regression).
1. Study, investigate and discuss "what", "how", and "why" your model makes predictions.

# Project Expectations
1. You will work on your projects individually (i.e. group submissions are not allowed).
1. All reports including the final report must be prepared using <a href="https://www.overleaf.com/">Overleaf</a>.
1. Each of you will review at least two reports of the peers in your group.

# Project Phases

## 1. Data analysis & preparation
1. Description of the dataset, its source, and motivation for the project
1. Visualize/Plot the distribution of each input features and discuss the range of the values (min, max, mean, median, etc.)
   - For example, plot histograms showing distribution of each input features
1. Study the distribution of the output labels
    - In case of classification, check if the data is imbalanced
    - In case of regression, check if the values are uniformly distributed or not
1. Data normalization
1. Data spliting into training, and validation sets

**What to submit?**  
a) A link to your Colab notebook (make sure that anyone with the link can view)  
b) A PDF report describing your findings  

## 2. Model selection & evaluation
1. Compare the results of the neural network with a linear regression or logistic regression model
    - Start with a basic model and then grow your model into a multi-layered model
    - Discuss how neural network models will be selected
    - Document your performance comparison
1. Study performance difference when linear activation is used instead of sigmoid (and vice versa)
   - How does your performance change when linear activations are used instead of sigmoid, in the last neuron and all other neurons?
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

