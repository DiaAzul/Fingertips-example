# Public Health England Fingertips API Example

The workbook provides an example script for accessing the Public Health England API to obtain indicator data.

The workbook requires an output folder to be created in the root of the project call "X_Output" this folder is not replicated to github to preserve confidentiality of data (and prevent sharing of large files). Each indicator is written to a separate file.

Indicators are downloaded by IndicatorId and AreaId. From files listed in A_Assumptions.

The notebooks require an environment containing:

+ Jupyter (to run the notebooks)
+ Pandas
+ fingertips_py (from PyPi)
+ tqdm
