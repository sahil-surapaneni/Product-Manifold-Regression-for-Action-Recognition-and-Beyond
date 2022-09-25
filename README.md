# Product-Manifold-Regression-for-Action-Recognition-and-Beyond
EECS 545 (Machine Learning) Final Project. 

## Abstract
Action videos are multi-dimensional data that can be represented via data tensors. The goal of this
project is to characterize data tensors as points on a product manifold and perform regression for
action recognition. To fulfill this goal, we first decompose the tensor data using Higher Order Singular
Value Decomposition (HOSVD), and impose the unfolded matrices on a Grassmann manifold. We
then formulate a regression function to model the processed data for learning and classification
without explicitly modeling the shape and motion. Databases used in related papers are employed,
namely the Weizmann Actions as Space-time Dataset and UC San Diego Traffic Video database, to
determine the efficacy of this approach and to challenge the implementation as originally described
in the literature. Our experimental results show the efficiency and accuracy of the method we
implemented; a second method is implemented based on earlier literature to demonstrate the strength
of manifold regression as compared to simpler manifold methodologies.

## Motivation
Human gestures and actions are a vital part of daily human lives; while humans instinctively recognize
such movements, quick and automated gesture and action recognition can be very difficult, in no
small part due to the multidimensional nature of video data. Effective methods to identify human
gestures can drastically expand the way people interact with computers in their day-to-day lives,
and the video-reliant nature of this task is widely-studied. As discussed in Lui [1], one common
problem of several gesture recognition methods, as we will discuss in detail in later sections, is the
need for large amounts of training data or time to have a result with good accuracy. The method
we found proposes a solution to optimize the process of characterization and classification over this
multidimensional data via regression; in contrast to complex models such as deep learning methods,
regression potentially allows for faster training and classification, marking these less-complex models
as worthy of further study. In addition, to study how this method can be more generally applied to
the problem of action and video recognition and classification, we implemented and compare both
methods upon the UC San Diego Traffic Video database ([2]).

## Full Information
Please Refer to **Final_Project_Writeup.pdf** in the repository for the full project writeup!
