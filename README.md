**this project is made for the "Python Programming Foundation" course from [Electro PI](https://electropi.ai/ "Go To Electro PI page")**

# Overview
DataPrepKit is a Python package designed to provide a comprehensive toolkit for preprocessing datasets. It offers functionalities for data reading from various file formats, data summarization, handling missing values, and categorical data encoding. The package uses NumPy and Pandas.

## Key Features:
- Read files of type CSV, Excel, and JSON, using "DataReading" class.
- Use "DataSummaries" class to create summaries for data frames, or get each individual summary value for mean, median, mode, standard deviation, number of values, minimum value, maximum value, and frequent values.
- Clean up data bases with "HandleMissingValues"  class using one of these cleaning strategies: 'drop', 'mean', 'median', 'mode', 'ffill', 'bfill', or replace the missing values with a value of your choice using the "replace_missing_values" method.
- Encode categorical data  using 'one-hot' strategy, or using 'label' from class "DataEncoding".
