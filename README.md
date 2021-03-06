# The_Math_of_Intelligence
Emulation of the series "The Math of Intelligence" by Siraj Raval


### 1. Intro to the series- Sample Gradient Descent for Linear equation.
* Link: https://www.youtube.com/watch?v=xRJCOz3AfYY&t=1s
* Gradient Descent Visualization: https://raw.githubusercontent.com/mattnedrich/GradientDescentExample/master/gradient_descent_example.gif
* Sum of squared distances formula (to calculate our error) : https://spin.atomicobject.com/wp-content/uploads/linear_regression_error1.png
* Partial derivative with respect to b and m (to perform gradient descent): https://spin.atomicobject.com/wp-content/uploads/linear_regression_gradient1.png



### 2. Support Vector Machines
* Link : https://www.youtube.com/watch?v=g8D5YL6cOSE&t=1s

Support Vector Machines are a very popular type of machine learning model used for classification when you have a small dataset.


### 3. Second order Optimization
* Link: https://www.youtube.com/watch?v=UIFMLK2nj_w&t=1s

Newton's Method uses the 2nd derivative for optimizing, which hints at a graphs curvature, has better step-wise performance, but is usually outperformed by gradient descent because computing the 2nd derivative is computationally expensive.


### 4. Logistic Regression
* Link: https://www.youtube.com/watch?v=D8alok2P468

We're going to use logistic regression to predict if someone has diabetes or not given 3 body metrics! We'll use Newton's method to help us optimize the model. We'll use a bit from all the mathematical disciplines i've mentioned (calculus, linear algebra, probability theory, statistics). 


### 5. Vectors
* Link: https://www.youtube.com/watch?v=s0Q3CojqRfM

Basically, its just 2 pieces of code that I used to show an example. One compares the dot product operation to standard multiplication to show how linear algebra is faster when we have several numbers to calculate simultaneously. The other is just a simple neural network to show that vectors don't just represent data, they represent our model's learnings.


### 6. k-Means Clustering
* Link: https://www.youtube.com/watch?v=9991JlKnFmk

Let's detect the intruder trying to break into our security system using a very popular ML technique called K-Means Clustering! This is an example of learning from data that has no labels (unsupervised) and we'll use some concepts that we've already learned about like computing the Euclidean distance and a loss function to do this. 


### 7. Neural Networks
* Link: https://www.youtube.com/watch?v=ov_RkIJptwE&t=4s

Have you ever wondered what the math behind neural networks looks like? What gives them such incredible power? We're going to cover 4 different neural networks in this video to develop an intuition around their basic principles (2 feedforward networks, 1 recurrent network, and a self-organizing map). Prepare yourself, deep learning is coming.


### 8. Convolutional Nueral Networks
* Link: https://www.youtube.com/watch?v=FTr3n7uBIuE&t=4s

Convolutional Networks allow us to classify images, generate them, and can even be applied to other types of data. We're going to build one in numpy that can classify and type of alphanumeric character.

### 9. Dimensionality Reduction
* Link: https://www.youtube.com/watch?v=jPmV3j1dAv4&t=10s

Most of the datasets you'll find will have more than 3 dimensions. How are you supposed to understand visualize n-dimensional data? Enter dimensionality reduction techniques. We'll go over the the math behind the most popular such technique called Principal Component Analysis.


### 10. Recurrent Neural Networks
* Link: https://www.youtube.com/watch?v=BwmddtPFWtA&t=233s

Recurrent networks let us learn from sequential data (time series, music, audio, video frames, etc ). We're going to build one from scratch in numpy (including backpropagation) to generate a sequence of words in the style of Franz Kafka. 


### 11. Probability Thoery - Naive Bayes
* Link: https://www.youtube.com/watch?v=PrkiRVcrxOs&t=3s

We'll build a Spam Detector using a machine learning model called a Naive Bayes Classifier!


### 12. Random Forests
* Link: https://www.youtube.com/watch?v=QHOazyP-YlM&t=1s

This is one of the most used machine learning models ever. Random Forests can be used for both regression and classification, and our use case will be to assess whether someone is credible or not by analyzing their financial history!


### 13. Hyperparameter Optimization
* Link: https://www.youtube.com/watch?v=ttE0F7fghfk&t=11s

Hyperparameters are the magic numbers of machine learning. We're going to learn how to find them in a more intelligent way than just trial-and-error. We'll go over grid search, random search, and Bayesian Optimization.


### 14. Gaussian Mixture Models
* Link: https://www.youtube.com/watch?v=JNlEIEwe-Cg

This is a lesson on Gaussian Mixture Models, they are probability distributions that consist of multiple Gaussian distributions. This is useful for modeling more complex data, that has multiple peaks. Sometimes one bell curve isn't enough. We can optimize this model for clustering so that we can classify the data into the discovered classes using the Expectation Maximization algorithm.


### 15. Generative Models - Latent Dirichlet Allocation (LDA)
* Link: https://www.youtube.com/watch?v=HyuBTMaKFmU&t=247s

Generative Models are insanely cool! They help create never before seen data. We'll go over the mathematical difference between discriminative and generative models, talk about a few types, then dive into a basic one called Latent Dirichlet Allocation to generate a set of topics for some news articles. 


### 16. Long Short Term Memory (LSTM) Networks
* Link: https://www.youtube.com/watch?v=9zhrxE5PQgY&t=45s

Recurrent Networks can be improved to remember long range dependencies by using whats called a Long-Short Term Memory (LSTM) Cell. 


### 17. Deep Q-Learning for video games
* Link: https://www.youtube.com/watch?v=79pmNdyxEGo&t=36s

We're going to replicate DeepMind's Deep Q Learning algorithm for Super Mario Bros! This bot will be able to play a bunch of different video games by using reinforcement learning.

### 18. Evolutionary Space Invaders
* Link: https://www.youtube.com/watch?v=rGWBo0JGf50

Evolutionary/genetic algorithms are somewhat of a mystery to many in the machine learning discipline. You don't see papers regularly published using them but they are a really fascinating subfield and in this video we're going to use a genetic algorithm to improve invaders in a space invaders game!


### 19. Quantum Computing
* Link: https://www.youtube.com/watch?v=LhtnECml-KI&t=28s

Quantum Computing offers hope for computing progress as we approach the limits of transistor density on silicon hardware. We're going to talk about the theory behind them then build our own quantum algorithm using IBM's Quantum API! 
