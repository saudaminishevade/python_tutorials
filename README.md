# python_tutorials
General instructions on set up of python for projects

## Setting up Python 
1. Install python 3.6, if prompted to install pip, say yes. If yes, proceed to step 3.
2. Install `pip` from [here](https://pip.pypa.io/en/stable/installing/)  
**The following steps are to be done through the command line. Go to terminal in Mac or CMD in Windows.**
3. Install virtualenv using the command below  
  ``pip install virtualenv``

## Creating a virtualenv
**We do not ever mess with the system python. So it is necessary to create a 'virtual environment' or `virtualenv` for our specific project.**

1. Create the virtualenv  
  Be in the directory that you want to create your virtualenv in. This need not be the same directory where your project code is. Use the code below.  
``virtualenv -p python3.6 name_of_project``   
('name_of_project' is the name of your virtual environment. You can name this anything you like.)
2. Activate the virtualenv  
Be in the same directory where you created the virtualenv.  
Then do the following (on Windows):  
``name_of_project\Scripts\activate``  
For activating on Mac, use  
  ``$ source name_of_project/bin/activate``

## Installing project requirements in the virtualenv

1. Go to the directory where your project using the `cd` command.
2. Now install the package requirements using the following command:  
``pip install -r requirements.txt``


**Your virtual environemnt is now ready. For additional information, read [this link](http://docs.python-guide.org/en/latest/dev/virtualenvs/)**

