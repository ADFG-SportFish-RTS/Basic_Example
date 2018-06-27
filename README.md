# AncBowl_LakeEvals

A template for how to organize a very simple project. For large projects an R package is probably more appropriate.

* Guide to simple layout above: https://nicercode.github.io/blog/2013-04-05-projects/
* Guide to R package organization: http://www.carlboettiger.info/2012/05/06/research-workflow.html



## Files Guide

__data__ stores the raw data and the clean data (and a metadata txt file?). The raw data should never be edited - only read. Analysis starts with the clean data.

__reports__ contains the working and final project reports

__output__ contains saved plots, tables, simulation output, or anything else that is cumbersome to create and is used in the final report 

__scripts__ contains the code organized by purpose. If they need to be run sequentially, number the files, e.g., 01_cleaning, 02_analysis etc. For organizational purposes it may be better to have one functions.R file dedicated to defining all custom functions, and then source that file during cleaning and analysis.
