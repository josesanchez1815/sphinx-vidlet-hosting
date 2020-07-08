# Sphinx Site Notes

## Jose Notes
#### Installation Link (Windows)
https://www.sphinx-doc.org/en/master/usage/installation.html

Step 1: Install Python (if necessary)
open command prompt for windows
- To check for python 3, type [python --version]
- If Python is not installed, go to https://docs.python-guide.org/

Installing Python 3 enables you to install Sphinx with pip

Step 2: Install Sphinx - https://www.sphinx-doc.org/en/master/usage/quickstart.html

Open Command Prompt for Windows
- pip install -U sphinx
- To check for sphinx, type sphinx-build --version

Step 3: type sphinx-quickstart using command prompt
(It will generate a source directory with conf.py and a master document index.rst)

index.rst serves as a welcome page and to contain the root of the table of contents tree

Step 4: open index.rst with your favorite text editor

This allows you to get the base template for the sphinx site. 

*Need Notes on how to embed videos on the site.*

To create the html site, go to the root directory for your sphinx site, for me I called it docs and it was made as a subdirectory to my username.

In the root directory type "make html" and it will take your index.rst file and use it to make the html website. 

Voila you have a base template for a sphinx site.
