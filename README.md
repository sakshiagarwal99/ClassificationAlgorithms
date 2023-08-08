# ClassificationAlgorithms

## **What is a classification algorithm?**
> Takes in data which may be raw or cleaned into features; mostly incomplete information and predicts its category.
> The task of a classification algorithm is to classify data in a discrete way - this or that? example pear or apple?
> An example could be an algorithm that takes in data as features like color, size and weight and gives the output as pear, apple and blueberry.

## **Difference between regression and classification**
> Regression predicts a value aka it is predictive of a continuous value. On the other hand classification is like a boolean value.
> Lets say you are given a bunch of data, like the altitude of an airplane, weather conditions and some other bunch of data and then you are asked to
guess its speed. In classification you may put the speed into categories like slow, kinda fast and crazy fast but in this case a number like 300km/h would be more helpful
when predicted by the algorithm.

## **Types of Classification Algorithms**

1. Logistic Regression
2. Naive Bayes
3. K-Nearest Neighbors(KNN)
4. Markov Decision Process(MDP)
5. Decision Trees/ Random Forest
6. K-Means Clustering
7. Support Vector Machines


## **How do we construct an algorithm specific to our needs?**

### 1. *_Type of Learning Involved_*:
   A. Supervised Learning - Supervision :
   > The Model learns from training examples, provided by humans.
   > In the fruit classification algorithm, the model is trained by giving images of the fruits and we have a human look at the picture and tell the algorithm that this a
     pear/apple/blueberry.
   > Mostly used for discrimination(recognition) tasks.
   > The training data, utilized to fine-tune the model, and the test data, employed to gauge its performance, are usually divided in an 80%/20% ratio.
     This division conceptually resembles our educational experience, wherein mathematics textbooks encompass both solved and unsolved problems, aiding our comprehension
     and application of mathematical concepts.

   B. Unsupervised Learning :
   > Model is learning from data that is unlabeled without any human input other than how the algorithm is designed and the type of data the algorithm is exposed to.
   > Mostly used for generative (imagination) tasks.
   > No split between training and testing data.

   C. Reinforcement Learning :
   > Here, The model learns the best strategy using a scenario given by humans.
   > We are giving the model a lot of information even beyond the actual data we are even going to tell it some of the possible outcomes and some of the rules of the road.
   > We are not labeling the data as the right or wrong choices but there will be some human input.
   > Scenario here is : What action can you, the algorithm take as an actor in this scenario and how is the environment going to respond to this action.
   > Mostly used for decision making tasks. (eg: robotics)
   > Reinforcement learning is a type of Semi-supervised learning where you are giving the model some human guidance but also allowing it to learn from its own.

 ![Type of Learning: Select Learning Mode based on Application](https://en.wikipedia.org/wiki/Supervised_learning#/media/File:Task-guidance.png)

### 2. *_Number of Features_* :

> How many variables do you have?(age, height,…)

> 1. More Features: the model is more optimized - consider a Support Vector Machine.
> 2. Less Features: the model is less optimized -  consider a Decision Tree.
> 3. Point to note: Can you reduce the number of features to simplify your model?(Feature Selection)
> 4. Some features have more predictive value than others - example if you want to predict tomorrow’s weather - an important feature to take in would be today’s weather and not something like what you ate for cereal today :)

### 3. *_Linearity_* :
    
> Is your data linear?
    
> 1. Linear: Consider a Support Vector Machine.
> 2. Non Linear: Consider a Decision Tree.

### 4. *_Training Time_* :

> How much data do you have, and how fast is your computer?

> 1. Faster Training: Consider a logistic regression.
> 2. Slower Training: Consider a random forest.
> 3. More training = more accuracy

### 5. *_#Of Parameters_* (parameters = model specs. #iterations, error, etc) :
    
> How much flexibility do you want in your training?
    
> 1. Less Parameters: Consider Logistic Regression(4)
> 2. More Parameters: Consider K-means Clustering(8)
> 3. Split data into train/validation/ test to examine the parameter space.

   
