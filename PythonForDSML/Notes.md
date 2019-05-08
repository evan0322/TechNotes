# ML with Python

Machine learning is a method that  automates analyticle model building



### Three types of Machine Learning algorithm

##### Supervised Learning

You have labeled data and trying to predict  label based off known features.

Commonly used in applications where historical data predicts likely future events

##### Unsupervised Learning

You have unlabeled data and trying to group together similar data points based off features.

self-organizing maps, nearest-neighbour mapping, k-means clustering and singular vs value decomposition. 

##### Reinforcement Learning

 Algorithm learns to perform an action from experience

Consisted with tree parts:

* Agent: the learner
* Environment: everything the agent interact with
* Action: What the agent can do

The object is for the agent to choose actions that maximize the expected reward over a given amount of time.

## Static learning

### Types

* Predict **continuous** data: Salary
* Predict a **categorical**  or **qualitative**  value: In a given day if the market is going up or down

### Form

General relationship between two variable X = (X1, X2….Xp) and y can be presented as:

Y = f(X) + e

Note: f(X) is not neccessary a linear expression

#### Why do we need to estimate f?

* Prediction: Predict Y based on new data X
* Inference: Understand the way that Y is affected as X1,...,Xp change. Which contribute more.

#### How to estimate f?

##### Parametric method

First, we make an assumption about the functional form, or shape, of f. For example:

f(x) = b0 + b1X1 + b2X2 + … + bpXp

After a model has been selected, we need a procedure that uses the training data to fit or train the model 

##### Non-parametric Methods

Non-parametric methods do not make explicit assumptions about the functional form of f . Instead they seek an estimate of f that gets as close to the data points as possible without being too rough or wiggly

**Advantage**

* avoiding the assumption of a particular functional form for f

**Disadvantage**

* a very large number of observations  is required in order to obtain an accurate estimate for f.
* Overfitting

#### Trade-Off Between Prediction Accuracy and Model Interpretability

**Less flexible method** (such as linear regression) have better interpretability, since the f(x) is easy to understand.

When we care more about inference, less flexible method is better for understanding.

**More flexible method** most of the time have better accuracy, but always hard to interpret. 

When we only care about the accuracy, we may want to choose more flexible methods.

Note more flexible methods do not **always** have better accuracy than less flexible method

 