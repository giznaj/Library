# Library
This lab uses the 'Library Open Data' dataset

## Assignment #3 
# 
Clustering using PCA (Principal Component Analysis) to demonstrate library similarity.
Linear Regression using 'lm' (Linear Model) to make predictions.
# 
1. Produces an output that demonstrates which libraries are most similar to which other libraries
2. Produces an output that can predict the ratio of the number of active library cardholders relative to the resident population served

## High Level
1. Import data files (.csv) into 1 R objects
2. PCA / Model
3. Linear Regression classification
3. Visualize the results

### Low Level
* declare libraries
* set working directory
* read in files from work directory (redirect into objects)
* merge the data (dataframes - omit 'NA')
* sum the data
* manual feature/column mapping (old/new data format)
* tidy column names
* prepare data for model (int/feature flag)
* merge other data in (stack vertically)
* pca/prcomp()
* scatterplot
* build the prediction (using lm)
* display the prediction
* compare the data (testdata, prediction)


#
## Notes
### Library/packages used

* library(dplyr)
* library(readr)
