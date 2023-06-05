# Demos for the 2023 Introduction to Fusion Energy and Plasma Physics Course

Notebooks from this folder can be run in two ways:

1. (Preferred) On a local installation of python that includes Jupyter notebook. 
2. Online on Google Colaboratory (this will require a free Google account). 

Note that some functionality, like interactive plots, may not work on Google Collaboratory.

Instructions are included below for both options 


# Installing PlasmaPy and Jupyter Notebook Locally with Anaconda
1. Download the .ipynb file for the notebook(s)

2. Download and install [Anaconda](https://www.anaconda.com/download)

3. Open Anaconda and do the following to create a new enviroment with PlasmaPy and all its dependencies installed.
  a) Select the 'Enviroments' tab.
  b) Left click on the green arrow.
  c) Click'Open Terminal' to open a command prompt.
![anaconda_open_terminal](https://github.com/PlasmaPy/PlasmaPy-Demos/assets/32618747/a3054200-13ff-4d85-937e-0b379976536f)


4.  In the terminal, create a new virtual enviroment by entering the command "conda create -n suli -c conda-forge plasmapy". When prompted, enter 'Y' to proceed with the installation. Installation will take a few minutes.
![anaconda_create_enviroment](https://github.com/PlasmaPy/PlasmaPy-Demos/assets/32618747/866e38f9-f5b4-4f0d-adfd-9ac2377c3ba9)

5. Open the new enviroment and install Jupyter Notebook.
  a) Select the 'Home' tab.
  b) On the dropdown menu, select the newly created enviroment. 
  c) Click the 'Install' button under on the card for Jupyter Notebook. 
![anaconda_open_enviroment](https://github.com/PlasmaPy/PlasmaPy-Demos/assets/32618747/cb23fa79-3f35-4f4b-8df1-7b6cb16d3af2)

6. Click 'Launch' on the Jupyter Notebook card. The program should open in your default web browser. Navigate to the downloaded .ipynb file and click on the title to open the notebook. ![anaconda_open_notebook](https://github.com/PlasmaPy/PlasmaPy-Demos/assets/32618747/67fa8cf0-4d92-4dc9-bee0-175dcd1d7f0f)


# Running Examples on Google Collaboratory

## Opening the Workbook

Notebooks can either be opened directly from GitHub or by downloading the .ipynb file and uploading it to Google Colab. 

## Opening fron GitHub
1. Open Google Colab in your browser: [Google Colab](https://colab.research.google.com/)

2. You should see a window to select a file. If not, select "File>Open a Notebook" from the tool bar. 

![image](https://user-images.githubusercontent.com/32618747/162498499-23900832-fe96-4d92-9258-d6af114cdb77.png)

3. Select "GitHub" and enter the URL of the notebook (right click "Copy link address" on the name of the notebook above) you want to open in the search field. 

4. If the notebook does not open immediately, click on the notebook in the list of names that appears below the search bar. 


## Opening from a Downloaded File

![image](https://user-images.githubusercontent.com/32618747/162499834-fc224d93-cad8-4e2d-916e-775198b69f55.png)

1. Right-click and click "Save link as" to save the notebook you want to open.

2. From Google Colab, go to "File>Open a Notebook", then to the "Upload" tab to upload the file.


## Running the Notebook

Once the enviroment has opened, use the following tips to use it: 

![image](https://user-images.githubusercontent.com/32618747/162499118-ecdbe48d-06ed-49c7-9c76-ed0a8cc32255.png)

- Select "Runtime>Run All" to run the entire notebook. 
- The first time you run a notebook that installs a package (like these), you may get an error. In this case, restart the runtime ("Runtime>Restart runtime") and the error should go away.
- To run a single cell, select the cell with your mouse and then press "Shift+Enter"
- Create new cells using the "Insert" menu or the "+Code" button.
