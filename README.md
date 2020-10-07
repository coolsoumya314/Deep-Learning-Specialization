# Deep-Learning-Specialization-
solutions of deep learning specialization on coursera

Step 1- Install Anaconda
Install Anaconda - https://www.anaconda.com/products/individual Installation Instructions - https://docs.anaconda.com/anaconda/install/windows/
After Installation on Windows a bunch of applications are installed along with Anaconda:
(1) Anaconda Navigator, a GUI for managing your environments and packages
(2) Anaconda Prompt, a terminal where you can use the command line interface to manage your environments and packages
(3) Spyder, an IDE geared toward scientific development
Open Anaconda terminal and type command

conda list

- you can chech your own install by this.
To avoid errors later, it's best to update all the packages in the default environment. Open the Anaconda Prompt application. In the prompt, run the following commands:

conda upgrade conda
conda upgrade --all

Troubleshooting
If you are seeing the following "conda command not found" and are using ZShell, you have to do the following:
Add export PATH="/Users/username/anaconda/bin:$PATH" to your .zsh_config file.
------
Now, for installing any package you simply have to type conda install package_name in your terminal. For example, to install numpy,type

conda install numpy

You can install multiple packages at the same time. Something like

conda install numpy scipy pandas

will install all those packages simultaneously. It's also possible to specify which version of a package you want by adding the version number such as

conda install numpy=1.10

You can install multiple packages at the same time. Something like conda install numpy scipy pandas will install all those packages simultaneously. It's also possible to specify which version of a package you want by adding the version number such as conda install numpy=1.10


Step 2- Running a python script on you cmd
This is the original window that you will see when you open cmd

Now is the time when you can create another folder for coursework and set the directory before executing the command to run python script.
For instance, I have created the folder named Udacity/Python and changed the directory as shown

Furthur, give the command

python first_script.py


if you get the same output as mine, you have done it correct.
Step 3 - Installing Atom Environment
Link (For windows) - https://atom.io/
Step 4- Installing and Launching Jupyter Notebook
We will install Jupyter Notebook by giving this command in Anaconda Prompt.

conda install jupyter notebook
or
pip install jupyter notebook

and then Jupyter notebook can be launched by this command in cmd or Anaconda prompt (remember to check the directory, as we have installed it through Anaconda, it will be installed in Anaconda directory folder. While launching through cmd, use that directory)
jupyter notebook


(P.S- I have shifter my Anaconda folder to coursework directory)
You should consider installing Notebook Conda to help manage your environments. Run the following terminal command:

conda install nb_conda

Then if you run the notebook server from a conda environment, you'll also have access to the "Conda" tab shown below. Here you can manage your environments from within Jupyter. You can create new environments, install packages, update packages, export environments and more. You can shutdown the entire server by pressing control + C twice in the terminal. Again, this will immediately shutdown all the running notebooks, so make sure your work is saved!

When you create a new notebook, you should see something like this:
