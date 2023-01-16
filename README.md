# learning_kaggle_sessions
This project only contains notebooks and requirements in order to learn or remember python stuff

You can find the exercice here : https://www.kaggle.com/learn

# Installation : 

All the packages a listed in the *requirements.txt* folder

You will need to install manually the package names "learntools" from kaggle in order to exercices in your local machine.

In order to do this you'll have to follow these steps : 

-----------------

First go to the below link and download the file in Zip format:
https://github.com/Kaggle/learntools

extract the file.

Go to command line, change the directory to extracted folder ‘learntools-master\learntools-master’ , where setup.py file is available

Then type command ‘python setup.py install’ and press Enter.

If you end up with error like –‘ File "C:\ProgramData\Anaconda3\Lib\site-packages\learntools-master\learntools-master\learntools__init__.py", line 2
machine_learning, ml_explainability, ml-insights, ml_intermediate, python, \’
Then follow below steps:

open file –‘ learntools-master\learntools-master\learntools__init.py’ from the extracted folder

Remove ‘ml_insights, ‘ from the __init.py python file
Save and close it.

-----

*Credit : mvsharish from kaggle community*

