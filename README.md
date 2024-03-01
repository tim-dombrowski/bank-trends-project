# Bank Trends Project

### Overview

This project is focused on the [FDIC BankFind API](https://banks.data.fdic.gov/docs/). From the webpage, we can see that there are several bulk data files available. We'll focus on the [Institutions (CSV format)](https://s3-us-gov-west-1.amazonaws.com/cg-2e5c99a6-e282-42bf-9844-35f5430338a5/downloads/institutions.csv) file. As we dive into the data with the code below, I'll share a bit about the process that I used when constructing the code as well. So be sure to follow along the descriptions as you run the code chunks and explore the data yourself.

### Repository Structure

The data work for this project demo is contained in the R Notebook directory of this repository. On GitHub, the webpage within that folder should display the README.md file, which contains the compiled output of the R Notebook. If you wish to explore the source code locally, then you can open the institutions.Rmd file in RStudio and execute the code chunks to replicate the data work. Note the `output: html_notebook` line in the header of that file, which indicates that the R Markdown document is an R Notebook. 

After running the code chunks in RStudio and making any desired changes, you can then create a copy that will generate a copy that will appear on GitHub. To do this, save a copy of the R Notebook and name it README.Rmd. Then, change the header line for the output type to `output: github_document`. This will switch the file from being an R Notebook to an R Markdown file that will compile into a generic [Markdown](https://www.markdownguide.org/) file (.md). This format (along with the README name) will automatically be recognized by GitHub and displayed in-browser. This will also replace the Preview button with an option to Knit the Markdown file. This knitting process will re-run all the code chunks and generate a new README.md file inside of the R Notebook folder, which will display on GitHub.
