# Sphinx Site Notes

## Jose Notes
#### Installation Link (Windows)
https://www.sphinx-doc.org/en/master/usage/installation.html

Step 1: Install Python (if necessary)
open command prompt for windows

- To check if python 3 is installed on your computer, enter the command
```
python --version
```
If Python 3 is installed, you should see something similar to the following:
```
Python 3.7.4
```

- If Python is not installed, go to https://docs.python-guide.org/

Installing Python 3 enables you to install Sphinx with pip

Step 2: Install Sphinx - https://www.sphinx-doc.org/en/master/usage/quickstart.html

Open Command Prompt for Windows
```
 pip install -U sphinx
```
To check for sphinx, type 
```
sphinx-build --version
```
Step 3: To quickly build a local site 
```
sphinx-quickstart 
```
(It will generate a source directory with conf.py and a master document index.rst)

index.rst serves as a welcome page and to contain the root of the table of contents tree

Step 4: open index.rst with your favorite text editor(Sublime 3, Atom, Notepad are some)

This allows you to get the basic template for the sphinx site. 

To create the html site, go to the root directory for your sphinx site. For me it is called
```
C:\Users\jsanc\sphinx-vidlet-hosting\docs
```
then type 
```
make html
``` 

Voila you have a base template for a sphinx site.
