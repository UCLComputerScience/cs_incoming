# The power of visualising data
This project provides a self-study introduction to visualising data. It has been created for the induction programme for new undergraduate computer science students at UCL. Its purpose is to give you some insight into one of the many ways that the skills you will learn on your undergraduate course can be used in 'real' life.

## Getting started
This project uses a cloud service Jupyter notebook. When you open one of the following links, the cloud service creates a virtual coding environment in the cloud for you to use so you don't need to install anything on your machine. It will take a few minutes for this 'environment' to be created, once it is ready you will see a page that looks a little like this one.

Once you have the notebook open using one of the following methods, you should follow the instructions in the notebook itself.

### 1. Using the notebook in the Binder cloud service (no account required, no ability to save changes)
If you do not want to create an account then you can access the notebook using [Binder](https://mybinder.org) at [https://mybinder.org/v2/gh/nicholsons/cs_incoming_datavis.git/master?filepath=incoming_students_data_visualisation.ipynb](https://mybinder.org/v2/gh/nicholsons/cs_incoming_datavis.git/master?filepath=incoming_students_data_visualisation.ipynb).  

You will be able to make changes to the code during your Binder sessions and see the effect of your changes, however when you exit Binder any changes that you have made will not be saved. If you wish to save changes that you make to access at another time then the menu bar within the Binder session provides an option to download the notebook to your computer.

### 2. Using the notebook in the Microsoft Azure Notebook cloud service (free account required, ability to save changes)
To use the notebook interactively and save your changes, create an account on [https://notebooks.azure.com](https://notebooks.azure.com). 

Access the notebook hosted on the Microsoft Azure cloud service at:
[https://notebooks.azure.com/snicholson/projects/ucl-computer-science-data-scie](https://notebooks.azure.com/snicholson/projects/ucl-computer-science-data-scie)

First you should 'clone' the notebook. To do this, after clicking the above link, click on the link to the notebook ('incoming_students_data_visualisation.ipynb'). You should see a button towards the top of the screen with the word 'clone'. Press this to create a copy. If you are not already logged in to Microsoft Azure Notebooks and you didn't already create an account, then you will be prompted to create an account now. You may need to wait a few minutes during which a copy of the notebook is made and the 'environment' is created for you. This process may be quite quick and it may not be obvious that the clone has completed, when it has finished you should see a message near the top of the screen that says '```Cloned from https://github.com/nicholsons/cs_incoming_datavis'```.

### 3. Using a locally installed Python Jupyter notebook environment
If you already have a locally installed Python development environment and code editor then you may be able to work out how to use Jupyter notebooks on your own machine. For example, if you are using [Visual Studio Code, you can work with Jupyter notebooks in the IDE](https://code.visualstudio.com/docs/python/jupyter-support). 
You will need to investigate options for doing this yourself depending on your own setup. 
You will need to install plotly and pandas in your local environment which you should be able to do with pip, e.g. 
```python
pip install pandas==1.0.3
pip install plotly==4.8.0
```

## Getting help
Ask for help by posting a message on Moodle at [https://extend.ucl.ac.uk/mod/forum/view.php?id=44916](https://extend.ucl.ac.uk/mod/forum/view.php?id=44916).

## Feedback and corrections
This notebook is maintained at [https://github.com/nicholsons/cs_incoming_datavis](https://github.com/nicholsons/cs_incoming_datavis). 

Please report suggestions or errors at [https://github.com/nicholsons/cs_incoming_datavis/issues](https://github.com/nicholsons/cs_incoming_datavis/issues).

This notebook was developed by [Sarah Sanders](mailto:sarah.sanders@ucl.ac.uk).

## Acknowledgements
The introductory video in the notebook is a TED talk given by Hans Rosling called ['The best stats you have ever seen'](https://www.ted.com/talks/hans_rosling_the_best_stats_you_ve_ever_seen?utm_campaign=tedspread&utm_medium=referral&utm_source=tedcomshare).

The code examples in the notebook make use of the [Plotly Express](https://plotly.com/python/plotly-express/) library. This library provides direct access to the Gapminder data set. There are also examples for the use of the Gapminder data in their help and documentation.

The Gapminder data can also be accessed freely at [Gapminder.org](https://www.gapminder.org/data/). The 'math_achievement_8th_grade.csv' file in this repository was downloaded from Gapminder.

## Data protection and privacy
TODO: Add statement as to the extent to which MS Azure Notebooks and Binder comply with UCL data. Warn students not to put any personal data in their notebook.

[Information on privacy for the Binder service can be found here](https://mybinder.readthedocs.io/en/latest/faq.html).

[Information on privacy for the Microsoft Azure Notebooks service can be found here](https://privacy.microsoft.com/en-gb/privacystatement).
