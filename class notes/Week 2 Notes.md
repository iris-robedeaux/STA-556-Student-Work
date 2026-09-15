**Objects**

Attributes

* object.attributeName 

  * ex: df.shape
  * no parenthesis

Methods

* object.method

  * ex: df.transpose()



**Pandas**

* import: import pandas as pd
* pandas the most common DS python package
* initialize dataframe from dictionary

  * df = pd.DataFrame(dictionaryObj)
* read csv in: pd.read\_csv("name.csv")
* how many rows and cols: df.shape
* show rows: df.shape\[0]
* show columns df.columns
* missing values: df.isnull()\[.sum()]

  * optional sum for how many are null
* get general summary of data: print(df.info())
* summary statistics: df.describe()
* get first \[x] rows or last \[x] rows: df.head(x) or df.tail(x)
* get a specific column: df.index(x, \[inplace = True])

  * inplace = True means that it doesn't create a whole new data frame (memory is short)
* get a slice of rows or columns: df.iloc\[r,c]

  * want a range? Like normal (1:5)
* find anything: df.loc

  * customizable for almost all uses (conditions on values, rows, etc)
* Operators

  * and - \&
  * or - |
  * not - \~

