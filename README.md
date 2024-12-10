![graphical_neural_network](graphical_neural_network.jpg)

# Molecular Drug Discovery Using Graph Neural Networks

## Project Overview
This project aims to leverage Graph Neural Networks (GNNs) for drug discovery, focusing on molecular analysis to identify potential drug candidates efficiently and accurately. By representing molecular structures as graphs, GNNs can capture complex relationships within chemical compounds, leading to data-driven predictions of properties and interactions crucial in drug development.

As a mentee, you’ll learn the fundamentals of Graph Neural Networks, their application in computational drug discovery, and the process of training these models to make predictions based on molecular data.

## Learning Resources
Before diving into the implementation, here’s a list of essential resources to help you build a strong foundation:

### Week 1: Get Familiar with Python Libraries
- **Libraries**: Numpy, Matplotlib, PyTorch

#### References for Python
- [GeeksforGeeks: Python Programming Language Tutorial](https://www.geeksforgeeks.org/python-programming-language-tutorial/)
- [Python Documentation](https://docs.python.org/3.13/)

  Get Familier with basic python syntax, datatypes, functions and basics of object oriented programming

#### References for numpy,Pandas
- [Numpy Documentation](https://numpy.org/doc/2.1/user/basics.html)
  - Just get to know about the working of numpy arrays, dimensions, axes, matrix operations, broadcasting and try to go over more examples from internet for practice
  - Just get to know the basic graphs plottings which will be used heavily when training any ML model to analyse the training process and sometimes potentially for debugging
 
#### Some basic ML algorithms(to get the hang of machine learning)

-  Linear Regression(Reading): https://www.geeksforgeeks.org/ml-linear-regression/?ref=ml_lbp
- (Optional) https://www.coursera.org/learn/machine-learning. You can go through this course to understand regression better


#### Understanding the Basics of Neural Networks
- **Articles and Reading**:
  - [Medium: Introduction to Neural Networks](https://medium.com/deep-learning-demystified/introduction-to-neural-networks-part-1-e13f132c6d7e)
  - [Medium: A Beginner Intro to Neural Networks](https://purnasaigudikandula.medium.com/a-beginner-intro-to-neural-networks-543267bda3c8)
  - Read the introductory chapter from “Introduction to Machine Learning - Gurney et al.” and optionally the theory (highly recommended).

- **Implementation pytorch tutorials(Optional, but highly recommended to learn the basics about tensors and basic feed forward neural networks)**:
  - https://youtu.be/c36lUUr864M?si=ipK9wX2L0EgOtZHV

> **Note**: We know that the articles we provided mostly cover the theory of neural networks; we also recommend you to get the basics concepts and syntax of pytorch and implement the basic neural networks and play with them.

### Assignments
- **Assignment 1**: Implement Linear and Logistic Regression from scratch using numpy.
- Build a Linear regression model to predict Student performance Index using the dataset provided in the link below. You will have to load the data using the library of your choice and drop rows in which some cells are empty.You are expected to use Numpy to create the linear regression model. Student Performance Dataset(link)
- Build a logistic regression model to predict whether the patient has a 10-year risk of future coronary heart disease (CHD) using the dataset available here: https://www.kaggle.com/datasets/dileep070/heart-disease-prediction-using-logistic-regression?resource=download
- You are free to use any library of your choice to load the data and drop the rows which have a NA entry. You are expected to use numpy to build the logistic regression model.
- Evaluating your model: for linear regression you can print the RMSE loss and for logistic regression print the accuracy of your model (percentage of data points classified correctly) along with the percentage false negatives (numbers of false negatives /number of positives) and percentage false positives(number of false positives/number of negatives)

- **Assignment 2**: Implement K-means clustering algorithm to get used to Numpy operations.
  
- **Assignment 3 (Optional)**: Implement Feed Forward Neural Network on cat and dog dataset from Kaggle and improve the model accuracy using various preprocessing techniques and hyperparameter fine-tuning.

- Submission format: Make your github repository, we will also float the official GitHub repo for WiDs in a few days. You can clone or fork our repo and add your work to it. We will float Google forms asking the repo links, please feel free to reach out in case you are new to GitHub.

### Week 2: Understanding Advanced Neural Networks and Graph Neural Networks
- **Resources**: 
  - To get the intuition of ReLU activation, read this article: [Visualizing Piecewise Linear Neural Networks](https://blog.janestreet.com/visualizing-piecewise-linear-neural-networks/).
  - Go over this [Coursera course](https://www.coursera.org/learn/neural-networks-deep-learning) to learn more about neural networks.

#### For Graph Neural Networks
- **Articles for Basic Ideas**:
  - [Neptune.ai: Graph Neural Network and Some of GNN Applications](https://neptune.ai/blog/graph-neural-network-and-some-of-gnn-applications)
  - [Distill.pub: Understanding GNNs](https://distill.pub/2021/understanding-gnns/)
  - [Towards Data Science: Graph Convolutional Networks](https://towardsdatascience.com/graph-convolutional-networks-introduction-to-gnns-24b3f60d6c95)

- **Optional Readings**:
  - Read and understand the research paper: [Neural Message Passing for Quantum Chemistry](https://arxiv.org/pdf/1704.01212).
  - Read this article on how to use Graphical Neural Networks in drug discovery: [Drug Discovery and Graph Neural Networks](https://medium.com/@mulugetas/drug-discovery-and-graph-neural-networks-gnns-a-regression-example-fc738e0f11f3).

#### Tutorials and Videos
- [YouTube: Graph Neural Networks Introduction](https://www.youtube.com/watch?v=8owQBFAHw7E)
- [YouTube Playlist: Graph Neural Networks](https://youtube.com/playlist?list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn&si=GiLMZdfS5szrhH0z)
