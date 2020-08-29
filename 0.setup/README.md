# Download and install Anaconda environment for Python 3.7

https://www.anaconda.com/download/

# Create new anaconda environment for this class
```sh
conda create --name chF20
 ```

# Activate environment

```sh
source activate chF20
```

# Check version (should be 3.7.1)

```sh
python --version 
```
https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html

# Install packages

Be sure to install these specific versions to make debugging easier for everyone in class.

```sh
conda install nb_conda=2.2.1
conda install nltk=3.5
conda install spacy=2.3.1
conda install scikit-learn=0.23.2
conda install pandas=1.1.1
conda install matplotlib=3.3.1
```

# Install spaCy English model

```sh
python -m spacy download en
```

# Use Jupyter notebooks

That's it! Whenever you're ready to use a Jupyter notebook in this setup, open up the terminal and navigate to the folder containing the notebook; then activate the anlp environment to access these libraries and start up the notebook:

```sh
source activate chF20
jupyter notebook
```

We'll be using Jupyter notebooks extensively in this class; if you're new to them, check out the tutorial here:

* [Jupyter notebook tutorial](https://www.dataquest.io/blog/jupyter-notebook-tutorial/)

If you haven't used Github before, you'll just need it to pull course materials (notebooks, data) from the comphumF20 repo.

* [Install git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* ` git clone git@github.com:dbamman/comphumF20.git`
* Whenever you want to update your local copy: `git pull`

See here for an intro to Git/Github:


* https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners

