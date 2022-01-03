# ProjectDA2021

# Problem statement:

For this project you must create a data set by simulating a real-world phenomenon of
your choosing. You may pick any phenomenon you wish – you might pick one that is
of interest to you in your personal or professional life. Then, rather than collect data
related to the phenomenon, you should model and synthesise such data using Python.
We suggest you use the numpy.random package for this purpose.
Specifically, in this project you should:
• Choose a real-world phenomenon that can be measured and for which you could
collect at least one-hundred data points across at least four different variables.
• Investigate the types of variables involved, their likely distributions, and their
relationships with each other.
• Synthesise/simulate a data set as closely matching their properties as possible.
• Detail your research and implement the simulation in a Jupyter notebook – the
data set itself can simply be displayed in an output cell within the notebook.

# Applications Used with this Jupyter Notebook:
- Anaconda with Python version 3.8.8.
- Install the latest version of git on your machine.
- CMDER
- VS Code
# How to run this Jupyter Notebook:

- Go to the repository in Github [ProjectDA2021 ](https://github.com/katel85/ProjectDA2021) 
- Click the green 'code' button and copy the link.
- Open CMDER and type in git clone and paste the copied link from github.
- Once the link has been cloned to your machine correctly you will be able to open the file by typing jupyter lab in the command line.
- To run the entire notebook we must go to the Kernal tab and select "Restart Kernal and Run All "
- [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/katel85/ProjectDA2021/tree/main/)

# Requirements to run the notebook:

 Requirements to run this notebook are in the requirements.txt file.

# Real World Data Notebook

- For this phenomenon I choose to work with a SAR-CoV-2 dataset that spanned a duratin of 106 days in Ireland.
- Several Variables were analysed in this dataset

    - Date
    - ConfirmedCovidCases
    - ConfirmedCovidDeaths
    - DailyHosp
    - DailyICU
    - Age Groups Hospitilized Daily (D0-5H,D5-14H,D15-24H,D25-34H,D35-44H,D45-54H,D55-64H,D65-74H,D75-84H,D85upH)
    
    
- The dataset was imported and processed to get the variables I required and analysis was conducted to describe, visualise and correlate some of these.
- Based on data from the SAR-CoV-2 dataset I simulated data from the variables above using the numpy random package and visualised it using different plots.
- The simulated data and true data correlated well with the methods chosen to stimulate the data in the numpy random package.