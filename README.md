# Theoretical Modeling of the Iterative Properties of User Discovery in a Collaborative Filtering Recommender System

This repo contains the simulation code for our experiments for the paper: 

## Authors: 
Sami Khenissi, University of Louisville 
Mariem Boujelbene, University of Louisville 
Olfa Nasraoui: University of Louisville

## Abstract: https://arxiv.org/abs/2008.13526

    The closed feedback loop in recommender systems is a common setting that can lead to different types of biases. Several studies have dealt with these biases by designing methods to mitigate their effect on the recommendations.  However, most existing studies do not consider the iterative behavior of the system where the closed feedback loop plays a crucial role in incorporating different biases into several parts of the recommendation steps.  

    We present a theoretical framework to model the asymptotic evolution of the different components of a recommender system operating within a feedback loop setting, and  derive theoretical bounds and convergence properties on quantifiable measures of the user discovery and blind spots. We also validate our theoretical findings empirically using a real-life dataset and empirically test the efficiency of a basic exploration strategy within our theoretical framework.  
    
    Our findings lay the theoretical basis for quantifying the effect of feedback loops and for designing Artificial Intelligence and machine learning algorithms that explicitly incorporate the iterative nature of feedback loops in the machine learning and recommendation process.


## Main results:

*We present a theoretical study of the evolution of a recommender system's feedback loop by looking at the asymptotic behavior of its components.   
*We provide a theoretical bound on the human discovery resulting from interacting with a generic recommender system, under certain assumptions. 
*We verify our theoretical results, empirically \footnote{https://github.com/samikhenissi/TheoretUserModeling}, using a semi-synthetic dataset.
*We empirically study the limit of basic exploration approaches and their effectiveness in  increasing human discovery

## Requirements to run the code:
'''bash
python 3.6
pandas
numpy
matplotlib
'''
