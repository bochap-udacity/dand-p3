# Analyze A/B Test Results

A/B tests are very commonly performed by data analysts and data scientists. It is important that you get some practice working with the difficulties of these.

For this project, you will be working to understand the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. Your goal is to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

The data and the Jupyter Notebook, which are all of the files you need to complete the project, are provided for you in a downloadable zip file in the resources tab (as well as under "Supporting Materials" below). Note that portions of the notebook reference back to quizzes that are linked in this lesson to ensure you are on the right track.

## Directory Structure

This is the folder structure of the project

```bash
.
├── Analyze_ab_test_results_notebook.html   ' Export of Jupyter 
├── Analyze_ab_test_results_notebook.ipynb  ' Code in Jupyter Notebook
├── LICENSE ' License File
├── README.md ' This file describing the project
├── ab_data.csv ' Data file investigated   
├── countries.csv ' Supporting countries data file
└── dand.yml
```

## Setup

### Prerequisites

1. Python setup on the host
2. conda setup on the host
3. conda environment that is similar to dand.yml

### Running locally

1. Clone repository by running `git@github.com:seetdev/dand-p3.git`
2. Go into the cloned folder
3. Create conda environment `conda env create -f dand.yml`
4. Run the notebook using `jupyter notebook`