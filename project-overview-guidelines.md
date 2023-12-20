# Project Overview Guidelines

This is intended to provide a high-level guideline that can be applied to all projects, with the goal of creating portfolio-ready repos that you will be proud to share with recruiters and future employers.

There should be a clear flow from one notebook to the next. The entire project tells the story. Viewers of your project shouldn’t have to search through notebook after notebook looking for specific parts. It should be very clear from markdown, code comments, executive summary. 

We like to see how you think and work, but that is why we have labs! Projects repositories should be well polished and have a logical flow. This means that projects should be:
- Well organized
- Easy to follow (commenting and markdown really helps here!)
- Replicable (relative file paths and error-free)


## File structure

- README.md. This should include:
  - Problem Statement (1-2 sentences)
  - Executive Summary (2-3 paragraphs)
    - This section should include a brief overview of your process, models used, important findings and/or metrics, model performance, etc.      and a brief summary of conclusions and recommendations.
  - File Directory/table of contents
    - Files should be clearly labeled with descriptive names
  - Data  and Data Dictionary
    - Write a sentence or two about the source of your data. If you are not including your data in the repo share a link to your data source.
    - Include all features in your final cleaned csv/file
    - Include engineered features
  - Conclusions and Recommendations
  - Areas for Further Research/Study
  - Sources
  - Any important visualizations - these can be included in the Executive Summary or Conclusions/Recommendations, or as its own section. Use good judgement! Include a few here that really highlight your findings.
- Data folder
  - Original data
  - Cleaned data
- Code folder
  - 01_Data_Collection 
  - 02_Data_Cleaning
  - 03_EDA
  - 04_Modeling
    - This can be multiple notebooks - for example…
    - 04a_Logistic_Regression_Models
    - 04b_Naive_Bayes_Models
- Presentation folder
  - Presentation pdf
  - Can include images folder if needed
- Scratch folder
  - This can include any of your work that you want to save, but do not want to be evaluated on.


## Notebook cleanup! Before you submit….
- Remove any erroneous libraries from imports - only import the libraries you need for this specific notebook
- Remove any erroneous cells. Did you create a function that you don’t use? Remove it! Did you create a bunch of visualizations and realize that there is viz in there that doesn’t add to your data storytelling? Remove it! 
- It is good practice to restart your kernel and run all cells before submitting. This is also a great way to double check for errors and remove those.
- Data Science is recursive. There's a good chance that you will get through your EDA, start modeling, and then go back to realize there are more features that you want to explore. That's great! But try to keep your notebooks siloed. You can always revisit a notebook to add in more work, but all EDA should be in the EDA notebook, all modeling should be in the modeling notebook, etc. The idea is to capture the workflow, rather than your flow of thought.

Remember, these are guidelines! Your structure will change from project to project, but this is a great baseline format to follow. Now let's get to work on some portfolio-worthy projects!



