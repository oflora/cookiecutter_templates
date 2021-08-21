# Cookiecutter R and Python template 

Personal project structure template for general projects. As it includes more folder than needed for most projects you can run the next commands to clean the folder.

``` bash
find . -type d -empty -exec rmdir {} \;
```
If any directory is left empty after running the previous command, use the -delete option, which will repeatedly delete all empty directories till the top-level directory.

``` bash
find . find . -type d -empty -exec -delete
```

## Directory structure

```
├── data
│   ├── external          <- Data from third party sources.
│   ├── interim           <- Intermediate data.
│   ├── processed         <- The final datasets for modeling and analysis.
│   └── raw               <- Original field/lab data dump.
├── docs
│   ├── documentation     <- Project documentation. Includes data dictionary, workflow description, etc.
│   ├── figs              <- General purpose images. Includes downloaded images.
│   ├── notes             <- Notes written during project development. Includes theory.
│   └── references        <- References employed in the project.
├── notebooks
│   ├── explore           <- Exploration notebooks.
│   └── reports           <- Notebooks for generating reports.
├── reports
│   ├── figures           <- Generated graphics and figures to be used in reporting.
│   ├── html              <- Generated analysis as html.
│   └── pdfs              <- Generated analysis as pdf.
├── src
│   ├── python                  <- Python function definitions.
│   ├── R                       <- R function definitions.
│   ├── scripts                 <- Executed scripts.
│   │   ├── analysis                <- Analyisis and model fitting scripts.
│   │   ├── data                    <- Scripts for downloading/extracting data.
│   │   ├── processing              <- Scripts to turn raw data to clean and useful data.
│   │   └── visualization           <- Scripts to create graphics and figures.
│   ├── sql                     <- SQL scripts for managing databases.
│   └── test_units              <- Test units for functions/scripts.
├── Makefile
├── py_requirements.txt
├── README.md
└── R_requirements.txt
```
 
