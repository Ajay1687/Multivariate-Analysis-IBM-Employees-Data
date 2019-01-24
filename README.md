# Multivariate-Analysis-IBM-Employees-Data
This repository consists of various R markdown files that were created to do different types of Multivariate Analysis on an IBM Employee dataset.
The techniques used are as follows:
## On IBM Data
### PCA (Principal Component Analysis) : 
It is used to analyze the continuous variables in a given dataset, which helps us in interpreting which all variables contribute more 
to the flow of data and in the end cluster the data in various groups.

### MCA (Multiple Corresspondence Analysis) :
MCA is an extension to the CA, wherein we analyze the relationship between several categorical variables in a data table. Indicator Matrix - Matrix comprising of 0’s and 1’s. So, MCA is technically a CA done on indicator matrix of a data table. Even quantitative variables can be analyzed by binning them, once binned these are again converted to binary values using disjunctive coding(one hot encoding).
### PLSC (Partial Least Square Coorelation) :
PLSC is used when we are trying to find information that is shared between two tables. We have two latent variables after the analysis, for each of the tables involved.

### BADA (Barycentric Discriminant Analysis) :
Barycentric discriminant analysis (BADA) is a robust version of discriminant analysis that is used to assign, to pre-defined groups (also called categories), observations described by multiple variables. By contrast with traditional discriminant analysis, BADA can be used even when the number of observations is smaller than the number of variables—This makes BADA particularly suited for the analysis of Big Data.

### DiCA (Discriminant Correspondence Analysis) :
DICA is an extension on CA and DA (grouping to predefined categories). -The main idea behind DCA is to represent each group by the sum of its observations and to perform a simple CA on the groups by variables matrix.

### MFA (Multiple Factor Analysis) :
MFA is used to handle multiple tables, that have different variables measuring the same observations, or same set of variables on different set of observations. - First, each table is normalized by 1st singular value (obtained by doing PCA on the same table) - All these normalized tables are merged together and then again, a PCA is done on this, which gives us factor score and loading on these variables.

## On Bird Brain Data
### CA (Correspondence Analysis) :
CA is a generalized version of PCA for analyzing data table with qualitative variables. In case of PCA we divided the table into factor scores(rows) and loadings(variables), where as in CA, we derive 2 set of factors scores one for the rows and the other for the columns. -Rows have masses representing each rows importance wrt the total table -similarly Columns have weighted each columns importance in describing each of the rows

## On Wine Data
### DiSTATIS :
It is a generalization of classical multidimensional scaling.
