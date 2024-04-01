# About this project
This is a jupyterlab notebook that uses the API by Cohere to ask its Large Language Model (LLM) questions about a collection of pdf files.

### How it works
You give the programme the path of a folder that contains a set of pdf files you want to feed the AI. 
You also give the path of a `.txt` file that contains questions you want to ask about all the files.

It then feeds each file into the LLM, asks the questions, and stores the answers in a `.csv` file.


### Getting started
#### Installing JupyterLab
You should install JupyterLab (or any other appp that can open Jupyternotebooks). 

See: https://github.com/jupyterlab/jupyterlab-desktop

You should open the programme and install Python.

#### Getting API acces from Cohere
You can get acces to the API (for free!) using this link: https://dashboard.cohere.com/

The free API is rate limited to 10 requests per minute, which is taken into account in the code of the programme.

#### Downloading and using the JupyterNotebook
Now you are ready to open and use the notebook!
