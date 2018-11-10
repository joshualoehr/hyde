---
layout: page
title: About
---

Hi there! My name is Josh Loehr, and I made this website to showcase myself, my work, and my interests. Consider it like the ultra deluxe extended version of my résumé (if you just want the trim and slim version, find it [here](https://joshualoehr.github.io/public/Joshua_Loehr_Resume_2018.pdf)). Here's what you can find on this page:

 - [Background](https://joshualoehr.github.io/about#background)
 - [Research](https://joshualoehr.github.io/about#research)
 - [Work Experience](https://joshualoehr.github.io/about#work-experience)
 - [Projects](https://joshualoehr.github.io/about#projects)
 - [Academic Overview](https://joshualoehr.github.io/about#academic-overview)

If you'd like to get in contact with me, shoot me an email at [joshualoehr@gmail.com](mailto:joshualoehr@gmail.com). 

Thanks for stopping by!

___

## Background

I was born in Austin, Texas, where I spent the first 18 years of my life and where my parents and older brother still live. In 2014, upon graduating Westwood High School, I left home to attend Western Washington University in Bellingham, Washington. Despite never visiting the campus until move in day of freshman year, I instantly fell in love with PNW and the people around me. At WWU I studied mathematics and computer science, completing my double major bachelor's degree in June 2018. During that time I discovered a passion for data science and machine learning, and I intend to continue pursuing these fields for the near and distant future. 

___

## Research

During my senior year at WWU I joined [Dr. Brian Hutchinson's](https://facultyweb.cs.wwu.edu/~hutchib2/) deep learning research group, where I worked on using RNNs for anomalous network activity and intrusion detection. This was done by using an RNN language model to learn the "grammar" of network log lines, leveraging the discrepancy between what the model predicts will be the next log line vs. what the next log line actually is to determine an anomaly score. This work is done in collaboration with researchers at [Pacific Northwest National Laboratory.](https://www.pnnl.gov/)

This is a poster I co-presented in May 2018 at WWU Scholar's Week describing the general research direction:
<object data="/public/language-modeling-anomalous.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="/public/language-modeling-anomalous.pdf">
        This browser does not support PDFs. Please download the PDF to view it: <a href="/public/language-modeling-anomalous.pdf">Download PDF</a>.</p>
    </embed>
</object>

And here's a link to the paper itself (note that I am not an author on this publication): [Recurrent Neural Network Language Models for Open Vocabulary Event-Level Cyber Anomaly Detection](https://arxiv.org/abs/1712.00557)  
Our code is also open source and available [here.](https://github.com/pnnl/safekit)

My specific area of research within this project has been exploring how variations in the granularity over which logged events are aggregated (day, quarter-day, minute, etc.) affect the accuracies of both our proposed language model and the baselines we compare against. A short paper is pending.

In addition to the research being done, involvement in Dr. Hutchinson's lab also entailed participation in a weekly reading group discussion covering recent publications within the field of deep learning. You can find the papers we covered and more on my [reading list.](/reading-list/)

___

## Work Experience

<details>
  <summary><strong> Dropdown Title </strong></summary>
  <div markdown="1">
  
  <center><div markdown="1">

#### Hidden Title
  </div></center>

Content
___

  </div>  
</details>  

___

## Projects

___

## Academic Overview

I graduated from Westwood High School in 2014 with a 4.0 GPA.

In June 2018, I graduated from Western Washington University with two Bachelors of Science degrees in Computer Science and Mathematics, with a combined 3.88 GPA.

Below are some highlighted elective courses I've taken, along with brief descriptions and projects completed therein. You can find more in depth detail about these projects, as well as others, in the [Projects](https://joshualoehr.github.io/about#projects) section above.

<details>
  <summary><strong> Artificial Intelligence </strong></summary>
  <div markdown="1">
  
  <center><div markdown="1">

#### CSCI 402
  </div></center>
   
**Description:** Introduction to knowledge representation and search. Possible application areas include natural language, perception, learning and expert systems.

**Projects** 
* [Virtual Fish - Selection (C#)](https://github.com/joshualoehr/VirtualFishSelection): Modifications to the original [VirtualFish project](https://www.codeproject.com/Articles/1074915/AI-Genetic-Evolution-of-Virtual-Fish) involving refactoring and an assortment of alternative selection strategies for the genetic algorithm.
* [Neural Network from Scratch (C++)](https://github.com/joshualoehr/neural-network-from-scratch): A very basic artificial neural network, built from scratch in C++ with the [Eigen library](http://eigen.tuxfamily.org). Trained to classify mushrooms as either poisonous or edible based on 23 nominal characteristics with >99% test accuracy.
* [Grid QLearn (C#)](https://github.com/joshualoehr/Grid-QLearn): Use Reinforcement Learning (Q-Learning) to teach a robot to navigate the WWU computer science department in a gridded environment.

*Grade recieved:* **A** (4.0)

___

  </div>  
</details>  


<details>
  <summary><strong> Natural Language Processing </strong></summary>
  <div markdown="1">
  
  <center><div markdown="1">

#### CSCI 404
  </div></center>
  
  **Description:** Fundamental concepts and ideas in natural language processing (NLP), and current research in the area; algorithms available for the processing of linguistic information and the underlying computational properties of natural languages. Word level, syntactic, and semantic processing from both a linguistic and an algorithmic perspective are considered. The focus is on modern quantitative techniques in NLP: using large corpora, including the web, statistical models for acquisition, disambiguation, and parsing.

  **Projects** 
  * [N-Gram Language Model (Python)](https://github.com/joshualoehr/ngram-language-model): Python implementation of an N-gram language model with Laplace smoothing and sentence generation.
  * [Various Assignments (Python)](https://github.com/joshualoehr/natural-language-processing): A hodge podge of small assignments from the course, which I should probably clean up and organize into a more viewable form.
  * Automatic Summarization of Academic Papers (Python): Final project. Attempted to automatically summarize academic papers using an RNN.

  *Grade recieved:* **A** (4.0)

  ___
  </div>  
</details>  


<details>
  <summary><strong> Machine Learning Algorithms </strong></summary>
  <div markdown="1">
  
  <center><div markdown="1">

#### CSCI 571
  </div></center>
  
  **Description:** Covers important machine learning research areas such as artificial neural nets, Bayesian learning, data mining, decision tree learning, evolutionary computation, reinforcement learning, version space learning, rough sets, and computational learning theory. Algorithms from these research areas will be analyzed. Each student will select one of the learned algorithms and apply it to the term project.

  **Projects** 
  * [Linear Regression (Java)](https://github.com/joshualoehr/linear-regression): General purpose linear regression optimizer implemented from scratch with Java. Options for both gradient descent and analytical solutions.
  * [Tensorflow DNN (Python)](https://github.com/joshualoehr/tensorflow-dnn/blob/master/prog2.py): A general purpose deep neural network implemented in Tensorflow. Uses purely the base Tensorflow library - no 3rd party additions or the contrib package.
  * Final Project (Python): TBA

  *Grade recieved:* 

  ___
  </div>  
</details>  


<details>
  <summary><strong> Linear & Nonlinear Optimization </strong></summary>
  <div markdown="1">
  
  <center><div markdown="1">

#### M/CS 335/435
  </div></center>
  
  **Description:** (Two courses) -- (M/CS 335) The optimization of linear functions subject to linear constraints. Linear programming, duality theory, sensitivity analysis, applications. (M/CS 435) Nonlinear optimization with emphasis on basic theory (including Lagrange multipliers and the Kuhn-Tucker conditions), algorithms for numerical solution of problems, and applications. Introductory dynamic programming, with emphasis on applications and algorithms.

  *Grade recieved:* **A** (4.0) / **B+** (3.3)

  ___
  </div>  
</details>  


<details>
  <summary><strong> Numerical Computation & Analysis </strong></summary>
  <div markdown="1">
  
  <center><div markdown="1">

#### M/CS 375/475
  </div></center>
  
  **Description:** (Two courses) -- (M/CS 375) Computer arithmetic, solution of nonlinear equations and optimization in a single variable; matrix factorization; matrix iterative techniques. (M/CS 475) Polynomial interpolation including splines, orthogonal systems of functions and least squares approximation; numerical differentiation and integration; solution of systems of nonlinear equations and unconstrained optimization.

  *Grade recieved:* **A** (4.0) / **A** (4.0)

  ___
  </div>  
</details>  
