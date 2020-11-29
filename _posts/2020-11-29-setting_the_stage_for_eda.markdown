---
layout: post
title:      "Setting the Stage for EDA"
date:       2020-11-29 18:47:05 +0000
permalink:  setting_the_stage_for_eda
---


As a Flatiron Data Science Bootcamp student, Exploratory Data Analysis (EDA) has been a foundational piece for every project I’ve submitted. After completing my first few projects, I developed a workflow to help me complete EDA tasks. I found that I can spend hours exploring datasets, just out of sheer curiosity. Curiosity is a great trait for a data scientist. However, when working on a project where EDA is just the first step of many to complete, having a defined and repeatable workflow was essential for me.


Before we dive in, here are a few things to note. This is not a comprehensive list of everything that should be done as part of your EDA. Consider it a starter pack where you add on additional steps that your particular project requires.  Next, let’s talk tech. I use Python and Jupyter Notebooks for my bootcamp projects with all data available locally. Now let’s dive in.


## Step 1 - Get Organized
Organize your code workspace to set yourself up for success. At a minimum, create separate directories to store your data, code, and images. Even the most trivial of projects can benefit from a tidy file system. Pick file and directory naming conventions and stick to them. Create a README file first and keep adding to it as you progress. I created a generic README template that I re-use for every project.

Once you have identified the data you’ll be using, check for data description documentation. This is documentation that gives details on the meaning of the columns. This can give you great insight on multiple fronts… from helping to guide your analytical line of questioning, to deciding how to handle missing or seemingly erroneous values, to insight into how to handle outliers.  

After you’ve done some background research into your data and have a better idea of the context, organize your thoughts around questions you want to explore in your EDA. Depending upon the project, you might be provided with exact questions to answer or, at the other end of the spectrum, you may be given free reign to just report anything “interesting”.  In any case, define and write out each question to guide you as you write your exploratory code. 

## Step 2 -  Data Cleaning
No matter the source of your data set, you should not make any assumptions about the data being clean and ready to analyze.  Organize your code to have a separate data cleaning module. For example, I create a separate Jupyter notebook with all of my  data cleaning code. Load in your data set and pop the hood for the following inspections:
Duplicate Check - check for both duplicate rows and duplicate id
Null Value Detection and Handling
Zero Value Detection and Handling


## Step 3 - Data Preprocessing
The data you have may not be in the exact format that you need in order to answer your questions. For example, you might have to create some new columns based off of data in existing columns. Another facet of the format dilemma is that the data may be in the "wrong" data type. For example, the data set has a value formatted as text  when what you really  need is a numeric or a date value. My list of preprocessing tasks is as follows:
* New Column Creation
* Data Type Conversion
* Column Renaming
* Outlier Detection and Handling

Here are links to the [Data Cleaning ](https://github.com/lspope/dsc-phase-3-project/blob/main/notebooks/data_cleaning.ipynb)[notebooks](https://github.com/lspope/dsc-phase-2-project-online/blob/master/notebooks/data_cleaning.ipynb) for some of my recent projects where you can find Python code examples for the the data preprocessing tasks listed above.

After you have gone through all of this work, pat yourself on the back and save your cleaned and preprocessed data to file. 

## Step 4 -  EDA
Your data is clean and prepped. You have greater awareness of the data set values and what they mean.  Now it’s time to apply this new-found knowledge towards your EDA  questions (in a new Jupyter notebook of course).  Personally, I like to create an “official’ EDA notebook and a separate “playground” notebook where I can try out a few different ways of approaching a problem before I include it in my final EDA.

Another EDA practice that I’ve found useful is to create 2-4 visualizations per question. Not all of these go into my final presentations, but it definitely helps me to think through each question. This practice also helps me sharpen my skills with the Python visualization libraries, Matplotlib and Seaborn.

In addition to visualizations for each EDA question, I find it useful to include a short write up. Your data analysis should provide actionable insights. Even if you are not the person who will take action on your findings, form a recommendation to the best of your ability. 

Finally, you will likely uncover even more questions that you’d like to explore. Document them as ideas for future work. Share them with your stakeholders when presenting your EDA findings. You can also incorporate your future work ideas into your recommendations.

Here are links to the [EDA](https://github.com/lspope/dsc-phase-2-project-online/blob/master/notebooks/general_eda.ipynb) [notebooks](https://github.com/lspope/dsc-phase-3-project/blob/main/notebooks/eda.ipynb) for some of my recent projects.

## Conclusion
And that’s it… a general workflow for conducting an Exploratory Data Analysis. If you’ve found this helpful, take this workflow and customize it to make it your own. Having a repeatable process will help you save time, mental energy, and will help you to create more consistent data analysis projects.




