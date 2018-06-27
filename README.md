
# Project Name

More information on organizing projectS:
* Guide to simple layout above: https://nicercode.github.io/blog/2013-04-05-projects/
* Guide to R package organization: http://www.carlboettiger.info/2012/05/06/research-workflow.html



## Files Guide

__data__ stores the raw data, the clean data and a metadata .txt file. The raw data should never be edited - only read. Analysis starts with the clean data.

__reports__ contains the working and final project reports

__scripts__ contains the code organized by purpose. If they need to be run sequentially, number the files, e.g., 00_cleaning, 01_analysis etc. For organizational purposes it may be better to have one functions.R file dedicated to defining all custom functions, and then source that file during cleaning and analysis.

