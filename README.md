# CHPC NITheP Summer School 2021: Machine Learning as a Tool for Theoretical and Computational Science

## Why Machine Learning?

Probability theory and statistical methods play a central role in
science. Nowadays we are surrounded by huge amounts of data. For
example, there are about one trillion web pages; more than one hour of
video is uploaded to YouTube every second, amounting to 10 years of
content every day; the genomes of 1000s of people, each of which has a
length of more than a billion base pairs, have been sequenced by
various labs and so on. This deluge of data calls for automated
methods of data analysis, which is exactly what machine learning
provides. The purpose of thislectures is to provide an
introduction to the core concepts and tools of machine learning in a
manner easily understood and intuitive to physicists and nuclear
physicists in particular. We will start with some of the basic methods
from supervised learning and statistical data analysis, such as
various regression methods before we move into deep learning methods
for both supervised and unsupervised learning, with an emphasis on the
analysis of nuclear physics experiments and theoretical nuclear
physics. The students will work on hands-on daily examples as well as
projects than can result in final credits. Exercises and projects will
be provided and the aim is to give the participants an overview on how
machine learning can be used to analyze and study nuclear physics
problems (experiment and theory). The major scope is to give the
participants a deeper understanding on what Machine learning and Data
Analysis are and how they can be used to analyze data from nuclear
physics experiments and perform theoretical calculations of nuclear
many-body systems.



The goals of these lectures on Machine Learning and Data Analysis are
to give the participants a deeper understanding and critical view of
several widely popular Machine Learning algorithms, covering both
supervised and unsupervised learning. The learning outcomes involve an
understanding of the following central methods:

- Basic concepts of machine learning and data analysis and statistical concepts like expectation values, variance, covariance, correlation functions and errors;
- Estimation of errors using cross-validation, blocking, bootstrapping and jackknife methods;
- Optimization of functions
- Linear Regression and Logistic Regression;
- Neural networks and deep learning;
- Decisions trees and random forests



## The lectures have two central parts

1. Statistical analysis and optimization of data
2. Machine learning

These topics will be scattered thorughout the lectures and may not  necessarily be taught separately. Rather, we will often take an approach (during the lectures and project/exercise sessions) where say elements from statistical data analysis are mixed with specific Machine Learning algorithms. 

### Statistical analysis and optimization of data

The following topics will be covered
- Basic concepts, expectation values, variance, covariance, correlation functions and errors;
- Gradient methods for data optimization, 
- Estimation of errors and resampling techniques such as the cross-validation, blocking, bootstrapping and jackknife methods;

### Machine learning

The following topics will be covered:
- Linear Regression and Logistic Regression;
- Neural networks and deep learning, including convolutional and recurrent neural networks
- Decisions trees, Random Forests, Bagging and Boosting

Hands-on demonstrations and exercises aim at deepening your understanding of these topics.



## Prerequisites

Basic knowledge in programming and mathematics, with an emphasis on
linear algebra. Knowledge of Python or/and C++ as programming
languages is strongly recommended and experience with Jupiter notebook
is recommended.



## Lecture material
_The link_ https://compphysics.github.io/MLSummerSchool/doc/web/course.html gives you direct access to the learning material with lectures slides and jupyter notebooks. Videos of the lectures will be uploaded. Also, if you are interested in Git and GitHub the following video could be useful https://mediaspace.msu.edu/media/t/1_8mgx3cyf


##  Teaching schedule,

### Teacher: Morten Hjorth-Jensen (MHJ)

| | |
|-|-|
| First Week  | February 15-19, 2021 | 
| Monday | - _Lecture 9am-1030am_: Introduction to Machine Learning and linear regression (MHJ) |
| Recommended readings |  Before the lectures starts: Bishop Sections 1.1, 1.2 and 1.3 |
| | Lecture material at https://compphysics.github.io/MLSummerSchool/doc/web/course.html  day 1 |
| Wednesday | - _Lecture 1pm-230pm_: Linear Regression and Bias-Variance Tradeoff (MHJ) |
| | Lecture material at https://compphysics.github.io/MLSummerSchool/doc/web/course.html  day 2 |
| Recommended readings |  Bishop Section 3.2 and Hastie et al chapter 3 |
| Friday | - _Lecture 9am-1130am_:  Logistic Regression and Neural Networks (MHJ) |
| | Lecture material at https://compphysics.github.io/MLSummerSchool/doc/web/course.html  day 3 |
| Recommended readings |  Bishop Sections 5.1-5.5 and Hastie et al chapter 11 |

---

| | |
|-|-|
| Second Week | February 22-26, 2021 |
| Tuesday | - _Lecture 1pm-230pm_:  Neural Networks, back propagation and examples of classification and CNNs |
| | Lecture material at https://compphysics.github.io/MLSummerSchool/doc/web/course.html  day 4 |
| Recommended readings |  Bishop Sections 5.1-5.5 and Hastie et al chapter 11 |
| Thursday | - _Lecture 9am-1030am_:  Decision trees, Random Forests and Boosting (MHJ) |
| | Lecture material at https://compphysics.github.io/MLSummerSchool/doc/web/course.html  day 5 |
| Recommended readings |  Hastie et al chapter 10 |

---

## Required Technologies

Lectures participants are expected to have their own laptops/PCs. We use _Git_ as version control software and the usage of providers like _GitHub_, _GitLab_ or similar are strongly recommended.

We will make extensive use of Python as programming language and its
myriad of available libraries.  You will find
Jupyter notebooks invaluable in your work.  You can run _R_
codes in the Jupyter/IPython notebooks, with the immediate benefit of
visualizing your data. You can also use compiled languages like C++,
Rust, Julia, Fortran etc if you prefer. The focus in these lectures will be mainly 
on Python.


If you have Python installed and you feel
pretty familiar with installing different packages, we recommend that
you install the following Python packages via _pip_ as 

* pip install numpy scipy matplotlib ipython scikit-learn mglearn sympy pandas pillow 

For OSX users we recommend, after having installed Xcode, to
install _brew_. Brew allows for a seamless installation of additional
software via for example 

* brew install python3

For Linux users, with its variety of distributions like for example the widely popular Ubuntu distribution,
you can use _pip_ as well and simply install Python as 

* sudo apt-get install python3

### Python installers

If you don't want to perform these operations separately and venture
into the hassle of exploring how to set up dependencies and paths, we
recommend two widely used distrubutions which set up all relevant
dependencies for Python, namely 

* Anaconda:https://docs.anaconda.com/, 

which is an open source
distribution of the Python and R programming languages for large-scale
data processing, predictive analytics, and scientific computing, that
aims to simplify package management and deployment. Package versions
are managed by the package management system _conda_. 

* Enthought canopy:https://www.enthought.com/product/canopy/ 

is a Python
distribution for scientific and analytic computing distribution and
analysis environment, available for free and under a commercial
license.

Furthermore, Google's Colab:https://colab.research.google.com/notebooks/welcome.ipynb is a free Jupyter notebook environment that requires 
no setup and runs entirely in the cloud. Try it out!

### Useful Python libraries
Here we list several useful Python libraries we strongly recommend (if you use anaconda many of these are already there)

* _NumPy_:https://www.numpy.org/ is a highly popular library for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays
* _The pandas_:https://pandas.pydata.org/ library provides high-performance, easy-to-use data structures and data analysis tools 
* _Xarray_:http://xarray.pydata.org/en/stable/ is a Python package that makes working with labelled multi-dimensional arrays simple, efficient, and fun!
* _Scipy_:https://www.scipy.org/ (pronounced “Sigh Pie”) is a Python-based ecosystem of open-source software for mathematics, science, and engineering. 
* _Matplotlib_:https://matplotlib.org/ is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms.
* _Autograd_:https://github.com/HIPS/autograd can automatically differentiate native Python and Numpy code. It can handle a large subset of Python's features, including loops, ifs, recursion and closures, and it can even take derivatives of derivatives of derivatives
* _SymPy_:https://www.sympy.org/en/index.html is a Python library for symbolic mathematics. 
* _scikit-learn_:https://scikit-learn.org/stable/ has simple and efficient tools for machine learning, data mining and data analysis
* _TensorFlow_:https://www.tensorflow.org/ is a Python library for fast numerical computing created and released by Google
* _Keras_:https://keras.io/ is a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano
* And many more such as _pytorch_:https://pytorch.org/,  _Theano_:https://pypi.org/project/Theano/ etc 

## Textbooks

| | |
|-|-|
|_Recommended textbooks_:| |
| | - Christopher M. Bishop, Pattern Recognition and Machine Learning, Springer, https://www.springer.com/gp/book/9780387310732. This is the main textbook and this lectures covers chapters 1-7, 11 and 12. |
| | - Trevor Hastie, Robert Tibshirani, Jerome H. Friedman, The Elements of Statistical Learning, Springer, https://www.springer.com/gp/book/9780387848570. This is a well-known text and serves as additional text.|
| | - Aurelien Geron, Hands‑On Machine Learning with Scikit‑Learn and TensorFlow, O'Reilly, https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/. This text is very useful since it contains many code examples.|

---

The books by Bishop and Hastie et al. can be downloaded for free if you access the university library via an IP number of your home university.


| | |
|-|-|
| _General learning book on statistical analysis_: | |
| | - Christian Robert and George Casella, Monte Carlo Statistical Methods, Springer|

---

| | |
|-|-|
| _General Machine Learning Books_: | |
 | | - Kevin Murphy, Machine Learning: A Probabilistic Perspective, MIT Press |
| | - David J.C. MacKay, Information Theory, Inference, and Learning Algorithms, Cambridge University Press |
| | - David Barber, Bayesian Reasoning and Machine Learning, Cambridge University Press  |

---








