# Instructions for using my N Gram Model

Please make sure you have srcml installed locally on your system in order to run my code.

Also, please install all dependencies listed under conda_requirements.txt AND pip_requirements.txt (I apologize for not having a single requirements.txt file - I am relatively new to this and could not figure out how to make a single file work)



# Dataset Collection and Preprocessing

The dataset collection process can be seen in "Dataset Collection.ipynb"

NOTE: GitHub will not let me upload my dataset because it is too large, so please access the student dataset at the following google drive link:

https://drive.google.com/file/d/1mOKOMooAJioBPIZsYB-jwzoOMCO4vTgE/view?usp=sharing

In order for this notebook to run correctly, please have an empty directory named "GitHub Repos" and an empty directory named "Method Data" in the current working directory

If you're using the data that I provided, running through this notebook should not be required, but it shows all of the code used for preparing the student data set.

Running through this notebook will take the user through cloning the source repositories, extracting the methods, preprocessing them, and saving them to a csv file that will be able to be used during model training.

# Model Training and Evaluation

The model training and evaluation steps can be seen in "N-Gram_Training.ipynb"

Please make sure you have the student_dataset.csv and training.txt files in your working directory in order to use this file.

Archives of the best performing instructor and student models can be found in the corresponding pickle files.

These models can be recovered using the code found in the notebook.