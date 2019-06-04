# CMPS-184-ImgAug-Presentation

Before attempting the steps below, please keep in mind that any python libraries you install using pip (or potentially other methods) 
must be installed such that the environment you are using can access them. For example, if running Jupyter notebook by using Anaconda, 
make sure you install while in the anaconda virtual environment on the command line. Python version may be one of the exceptions to 
this rule, since I believe Anaconda may prompt you to choose which Python to use (the one locally stored on your computer, or the one 
that comes with anaconda). You’ll also want to make sure pip is fully updated (pip install –upgrade pip or 
python -m pip install –upgrade pip).

1. Install [Anaconda w/ Jupyter Notebook](https://jupyter.readthedocs.io/en/latest/install.html) 
2. Install/clone imgaug library
3. Install Tensorflow
NOTE: I have had issues following the instructions to install this before on Windows. If you run into issues, try opening the command line,
activating an Anaconda virtual environment, and installing Tensorflow using pip. This link may be more helpful -> Another Tensorflow Link
4. Install Keras
5. pip install all other essential libraries needed. This may include:
- os
- glob
- sklearn
- pandas
- numpy
- pickle
- matplotlib
6. Clone my repository on GitHub

You should now be able to run my project using Jupyter notebook by navigating to the cloned repo locally and opening the ‘Copy for Testing’
ipynb file. Please keep in mind that if running this on a laptop without a GPU, you may not be able to run the Convolutional Neural Network
I used to train the model (ResNet) due to memory constraints. I occasionally run into memory issues on my computer as well, but I can 
easily fix them by restarting my Jupyter notebook instance. If you are able to run the model, then it may also take several minutes or 
hours to finish depending on laptop specs. Deep Learning works much better when training using a GPU versus a CPU.

If you aren’t able to run the project locally. You may also be able to run it via importing to Google Colab. 
