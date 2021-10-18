# Classification of _issues_ from _GitHub_ repositories

## Model Integration

### Introduction

<hr>

According to a survey conducted in 2019 by [VentureBeat](https://venturebeat.com/2019/07/19/why-do-87-of-data-science-projects-never-make-it-into-production/), 87% of Machine Learning models developed do not pass the experimentation phase, that is, they never deliver real value to the customer.

While it is possible to make real-time predictions with our model through _Jupyter Notebook_, it is still not particularly useful until other users and applications can consume its results.

There are several strategies to "serve" Machine Learning models, including:

- Embed the model in an application
- Serve the model through an API
- Use the template saved in a standardized way as a library

Choosing and implementing this strategy is part of what we call [MLOps](https://towardsdatascience.com/what-is-mlops-everything-you-must-know-to-get-started-523f2d0b8bd8), which consists of in a set of practices that aim to implement and maintain Machine Learning models in production in a reliable and efficient way.

### Goal

<hr>

The objective of this task is to encapsulate the developed model in an application, so that its results can be consumed by other users.

The program must receive as a parameter the Title and Body of a _issue_ (or both), and it must return a message to the user informing whether that _issue_ is a BUG or not.
