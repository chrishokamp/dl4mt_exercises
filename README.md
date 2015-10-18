**An Introduction to Deep Learning with Theano**

Fundamentals for DL4MT  I

Quick review of MLP & Backprop
Deep Belief Nets, Stacked Auto-Encoders
Tricks: drop-out, distributed training, Hessian-free optimization, ReLu, etc. 

Goal: Prep and setup.
Compare logistic regression, MLP, and stacked auto-encoders on same data
Challenges: Implement tricks


**Day 1**
***Please work through the notebooks in the following order:***

If you are new to theano, please start with the excellent tutorials from the [Montreal Deep Learning Summer School 2015](https://github.com/mila-udem/summerschool2015), and complete the following notebooks first:       

- intro_theano/intro_theano.ipynb 
- intro_theano/logistic_regression.ipynb 

If you are already familiar with theano, please work through the notebooks in this repository in the following order:      
- theano_logistic_regression.ipynb
- mlp.ipynb
- theano_autoencoder.ipynb
- stacked_autoencoder.ipynb      

**Day 2**

TODO: add instructions

**Completing the labs**

As you work through the notebooks, you will notice that some of the cells use the %%writefile magic at the top of the cell to write the content to a file. This is done for classes and functions which will be used in later notebooks. In order for the save paths to work correctly, you need to be running `ipython notebook` inside the directory for that day. 

Every time the cell is run, the file will be overwritten, so if you want to modify the behavior of a class or function, just edit the cell where it is created, and the corresponding file will automatically update. 

***Installation and Setup***

The notebooks need to be run inside the day\*/ directory, so, for example:

```
git clone https://github.com/chrishokamp/dl4mt_exercises.git
cd dl4mt_exercises/notebooks/day1
ipython notebook
```


Please also make sure that you are using the bleeding edge version of theano from github. Installation instructions are [here](http://deeplearning.net/software/theano/install_ubuntu.html#bleeding-edge-installs). 

These labs use [Fuel](http://fuel.readthedocs.org/en/latest/setup.html) to build, load, and iterate over datasets, please install that first. 

***Memory and Disk Space Management***
If you are using the Virtual Machine provided for the exercises, you may find the available memory getting low. Once you have worked through a notebook, you can close it to free up the RAM used by that kernel. 

***Dataset Description
TODO


***Resources and Inspirations Used to Create these Tutorials***

Most of the Theano code in these tutorials was taken from the [excellent tutorials on deeplearning.net](https://github.com/lisa-lab/DeepLearningTutorials), and modified to be used with an example Part-of-Speech tagging task using the Brown Corpus with the Universal Tagset.  


