# Our workshop in WICCON

This repository belongs to the workshop "Hardware Hacking with Artificial Intelligence" for WICCON 2025. 

Made by Azade Rezaeezade and Lizzy Grootjen.

## Copyright
We have not opted for a specific license. However, designing such materials is takes a lot of time. Therefore, please do not distribute the materials without our permission.

## How to use?
You need the following programs installed:
- Visual studio code, which you can download from: https://code.visualstudio.com/download
- Python 3.12, which you can download from: https://www.python.org/downloads/
- Git, which you can download via brew (MacOS) or apt-get (Linux) or via this website: https://git-scm.com 
- Git LFS, which you can download via brew (MacOS) or apt-get (Linux): https://stackoverflow.com/questions/48734119/git-lfs-is-not-a-git-command-unclear

Then you need to clone the repository as follow:
~~~
git clone https://github.com/BruteforceMisa/wiccon-workshop
cd wiccon-workshop
git lfs install
git lfs pull
~~~

Then, open the downloaded repository in VSCode and perform the following steps:
- Open the Jupyter Notebook "01-intro-sca.ipynb", which is loacted in codebase/exercises
- In the right top corner, click "Select kernel"
- In VSCode, a bar will occur. If extensions are not installed, click "install python and extensions"
- If VSCode asks you to install IPykernel, select "install"
- Then, create a kernel. Select "Create new virtual environment" and select "Python 3.12" as interpreter
- To install dependencies, select the checkbox "requirements.txt" 
- Make sure that your new virtual environment (.venv) is selected as kernel within your Jupyter Notebook

You should be ready to go!


### Troubleshooting
In some cases, creating the environment might give some errors. If you experience issues, try the following:
- If you manage to create a virtualenvironment, try restart/reselect it in the Notebook
- In the top bar, you can select "Terminal -> New terminal" 
- In your terminal, you can activate the virtual environment by ``` source .venv/bin/activate```
- If the packages were not installed correctly, you can install them by running ```pip install numpy chipwhisperer scipy tqdm matplotlib tensorflow```


