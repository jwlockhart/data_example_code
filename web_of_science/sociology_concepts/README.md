# Popularity of sociology concepts in the Web of Science

## Inspiration
- Hallett, Tim, Orla Stapleton, and Michael Sauder. 2019. "[Public Ideas: Their Varieties and Careers](https://journals.sagepub.com/doi/full/10.1177/0003122419846628)." *American Sociological Review* 84(3):545–76.
- A conversation on Twitter with Beth Popp Berman, Dan Hirshman, and Philip Cohen.

## Data
- Data come from the Web of Science. The University of Michigan Library has an in-house copy of the database, which I am extremely grateful and fortunate to have access to. 
- Intermediate data files are available in this repo if you want to make plots of a different style.

## Tools
- Data selection was done from `.parquet` with `PySpark`, and that code is not likely to port well to other systems or data formats. 
- Plotting was done with vanilla `pandas` and `matplotlib`, though, and that notebook should run on any system using the files inthis repo.