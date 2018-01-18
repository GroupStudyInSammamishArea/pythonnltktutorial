# pythonnltktutorial

This repository will hold the source code for the Python and NLTK Youtube tutorial: 
https://www.youtube.com/watch?v=FLZvOKSCkxY&amp;list=PLQVvvaa0QuDf2JswnfiGkliBInZnIC4HL

All the Python source code for this tutorial can be found at github:

https://github.com/PythonProgramming/NLTK-3----Natural-Language-Processing-with-Python-series

Each member will submit his code to his own directory, thus there are five directories:

* aish for Aishvarya Sharma
* bj for BJ Lee
* gavin for Gavin He
* lei for Lei Ma
* wei for Wei Ren

## 1. Sentdex home page

https://www.youtube.com/user/sentdex

## 2. Preparation

### 2.1 Install Anaconda

https://www.continuum.io/downloads

### 2.2 Install matplotlib/scipy/scikit-learn 

(1) Create the environment.

```sh
$ conda create --name <any name like "nltk" or "twitter">
```

To specify the Python version, use the argument "python=".

```sh
$ conda create --name <any name like "nltk" or "twitter"> python=2.7
```

(2) Activate the environment, assuming that the environment name is "nltk".

```
$ conda activate nltk
```

If you want to deactivate the environment later,

```sh
$ conda deactivate
```

(2) Install the packages.

```sh
$ conda install matplotlib scipy scikit-learn
```

You may also use Anaconda Navigator to install those.

## 3. Get code

```sh
$ git clone https://github.com/GroupStudyInSammamishArea/pythonnltktutorial.git
```

## 4. Jupyter

A very good jupyter notebook tutorial: 

https://www.youtube.com/watch?v=HW29067qVWk
