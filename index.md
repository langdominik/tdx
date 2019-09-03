---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---


Temporal Density Extrapolation
====================

What is this?
---------------------


This site is dedicated to the Temporal Density Extrapolation ('TDX') method published by Georg Krempl, Dominik Lang and Vera Hofer.

### Abstract

>Density estimation is a versatile technique underlying many data mining tasks and techniques, ranging from exploration and presentation of static data, to probabilistic classification, or identifying changes or irregularities in streaming data. With the pervasiveness of embedded systems and digitisation, this latter type of streaming and evolving data becomes more important. Nevertheless, research in density estimation has so far focused on stationary data, leaving the task of of extrapolating and predicting density at time points outside a training window an open problem.

>For this task, Temporal Density Extrapolation (TDX) is proposed. This novel method models and predicts gradual monotonous changes in a distribution. It is based on the expansion of basis functions, whose weights are modelled as functions of compositional data over time by using an isometric log-ratio transformation. Extrapolated density estimates are then obtained by extrapolating the weights to the requested time point, and querying the density from the basis functions with back-transformed weights.

>Our approach aims for broad applicability by neither being restricted to a specific parametric distribution, nor relying on cluster structure in the data. It requires only two additional extrapolation-specific parameters, for which reasonable defaults exist. Experimental evaluation on various data streams, synthetic as well as from the real-world domains of credit scoring and environmental health, shows that the model manages to capture monotonous drift patterns accurately and better than existing methods. Thereby, it requires not more than 1.5 times the run time of a corresponding static density estimation approach.

### Full Article

The full article can be found on [it's page at Springer](https://rdcu.be/bP6t5) .


Is the code available?
---------------------

We created a [public repository on Bitbucket](https://bitbucket.org/grazdriftmining/tdx_demo/) that contains the core code of the tdx method as well as a short demo of the method.

Acknowledgement
---------------------

We thank the Austrian National Bank for supporting our research project number 17028 as part of the OeNB Anniversary Fund. 

