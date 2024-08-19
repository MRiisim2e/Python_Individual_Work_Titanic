# Python_Individual_Work_Titanic

## Exploratory Data Analysis (EDA):

* Load the Titanic dataset into a Pandas DataFrame.
* Use Pandas methods to explore and understand the dataset:
1. Display the first few rows to get an overview of the data structure.
2. Check the dimensions of the dataset (number of rows and columns).
3. Identify missing values and decide on strategies for handling them.
4. Compute basic statistics (e.g., mean, median, min, max) for numerical columns.
5. Analyze categorical variables (e.g., value counts).

```python
import pandas as pd

df = pd.read_csv('/content/train.csv')

df.head()

df.shape
