# PlasmaPy Workshop at the SULI Summer School (6/2025)

Notebooks for this workshop can be run in three ways:

1. Online on **Google Colab** (no setup needed, but must have a Google account)
  - [**Getting started with PlasmaPy**](https://colab.research.google.com/github/PlasmaPy/PlasmaPy-Demos/blob/main/2025-SULI/plasmapy-tutorial.ipynb) ✨ (part 1 with Nick)
  - [**Single particle drifts**](https://colab.research.google.com/github/PlasmaPy/PlasmaPy-Demos/blob/main/2025-SULI/single_particle_drifts.ipynb) 💫 (part 2 with Peter)

To hide AI features, go to Tools → Settings → AI Assistance and click on "Hide generative AI features."

2. Online on **Binder** (no setup needed, but less reliable)

   [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/PlasmaPy/PlasmaPy-Demos/main)

3. On a **local installation of Python** that includes Jupyter notebook. (Advanced)

Some functionality, like interactive plots, may not work on Google Colab. Instructions are included below for each option.


# Table of contents

1. [Running Examples on Google Colab](#installation_google_colab)
2. [Running Examples on Binder](#installation_binder)
3. [Running Examples on Jupyter Notebook Locally with Anaconda](#installation_anaconda)
4. [Tips on Using Jupyter Notebook](#jupyter_tips)

# Running Examples on Google Colab <a name="installation_google_colab"></a>

## Opening the Notebooks

To open the notebooks on **Google Colab**, please open the links at the top of this README.

## Running the Notebook

After opening each notebook, please execute the first code cell by pressing "Shift + Enter" in order to install PlasmaPy. When prompted, click **Run anyway**. If prompted again, either click on the "Restart runtime" box in the output, or go to "Runtime" and select "Restart runtime":

![image](https://user-images.githubusercontent.com/32618747/162499118-ecdbe48d-06ed-49c7-9c76-ed0a8cc32255.png)

# Running Examples on Binder <a name="installation_binder"></a>

To launch a **Binder** environment with PlasmaPy installed and example notebooks from this folder loaded, click the link below. The Binder environment takes some time (~5–10 minutes) to initialize, and that Binder may stop working if many people all sign on at once (e.g. during a large workshop).

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/PlasmaPy/PlasmaPy-Demos/main)

Once the Binder environment has initialized, navigate to the folder with the name of this workshop and select the example notebook you want to run.

# Running Examples on Jupyter Notebook Locally with Anaconda <a name="installation_anaconda"></a>
1. Download the .ipynb file for the notebook(s)

   The notebooks can be downloaded from this GitHub repository. Click on the file you want to download to open the GitHub page for that file. Then, click the download icon to download the raw file.

   ![image](https://github.com/user-attachments/assets/6e5176dd-5249-4fb7-90c8-fe4e4bfae3e1)

3. Download and install [Anaconda](https://www.anaconda.com/download)

4. Open Anaconda and do the following to create a new environment with PlasmaPy and all its dependencies installed.

  a) Select the 'Enviroments' tab.

  b) Left click on the green arrow.

  c) Click 'Open Terminal' to open a command prompt.

![anaconda_open_terminal](https://github.com/PlasmaPy/PlasmaPy-Demos/assets/32618747/a3054200-13ff-4d85-937e-0b379976536f)


4.  In the terminal, create a new virtual environment by entering the command "conda create -n suli -c conda-forge plasmapy". When prompted, enter 'Y' to proceed with the installation. Installation will take a few minutes.
![anaconda_create_enviroment](https://github.com/PlasmaPy/PlasmaPy-Demos/assets/32618747/866e38f9-f5b4-4f0d-adfd-9ac2377c3ba9)

5. Open the new environment and install Jupyter Notebook.

  a) Select the 'Home' tab.

  b) On the dropdown menu, select the newly created environment.

  c) Click the 'Install' button under on the card for Jupyter Notebook.

![anaconda_open_enviroment](https://github.com/PlasmaPy/PlasmaPy-Demos/assets/32618747/cb23fa79-3f35-4f4b-8df1-7b6cb16d3af2)

6. Click 'Launch' on the Jupyter Notebook card. The program should open in your default web browser. Navigate to the downloaded `.ipynb` file and click on the title to open the notebook. ![anaconda_open_notebook](https://github.com/PlasmaPy/PlasmaPy-Demos/assets/32618747/67fa8cf0-4d92-4dc9-bee0-175dcd1d7f0f)

# Tips on Using Jupyter Notebook <a name="jupyter_tips"></a>

- Select "Runtime>Run All" to run the entire notebook.
- To run a single cell, select the cell with your mouse and then press "Shift+Enter"
- Create new cells using the "Insert" menu or the "+Code" button.
