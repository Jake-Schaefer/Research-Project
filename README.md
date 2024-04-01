# Independent Study 2024 Spring
For the course project, we will validate and refine the preprocessing of our downloaded datasets for the 153 traits, and the gold standard analysis with single-step regression for traits with available condition data. 

**Task division:** Each teammate is randomly assigned 13-14 traits, see the [google sheet](https://docs.google.com/spreadsheets/d/1U5wjH1mfSHAogCuMTPz1BhyCHMNaZ1F9iDoXFwWbaIc/edit#gid=0) \
**Deadline:** March 10th 2024, 11: 59 pm CT (extended from March 3rd)

## Goals:
1. In this stage, we will work together on the refinement of the GEO data preprocessing for the 153 traits in our question set. We will follow the pipeline in the notebook file [example](examples/Breast-Cancer.ipynb) to do the following:
   - Preprocess all the cohorts related to a trait from our downloaded Xena and GEO datasets. When possible, each cohort should be converted to a tabular form and saved to a csv file, with columns being genetic factors, the trait, and age/gender information when available;
     The pipeline can be seen as a decision tree, where the output of one step may affect the next step to take. For steps that involve fixed logic, we will frequenly use functions in a utils file. For steps that require text understanding or domain knowledge, we will prompt ChatGPT to accelerate this process, and manually verify its answer.
