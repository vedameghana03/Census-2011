# Census-2011

## Project Goals

The primary goal of this project is to analyze the census data using pandas. Specific operations include:

1.  Hiding the index of the dataframe.
   
2.  Adding a suffix to the column names.

## Libraries Used

* pandas

## Code Description

1.  **Import pandas:** The pandas library is imported for data manipulation and analysis. [cite: 1]
   
2.  **Load the dataset:** The dataset is loaded into a pandas DataFrame. [cite: 1]
   
3.  **Hide DataFrame Index:** The index of the DataFrame is hidden using the `style.hide()` method. [cite: 133]
   
4.  **Add Suffix to Columns:** A suffix is added to all column names using the `add_suffix()` method.

## Results

* The index of the DataFrame was successfully hidden. [cite: 133]
   
* A suffix was added to all column names. [cite: 135, 136]

## Code Snippets

### Load Dataset

```python
import pandas as pd
data = pd.read_csv("C:/Users/gvrk1/Downloads/Census+2011.csv")
