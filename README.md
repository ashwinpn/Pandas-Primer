# Pandas-Primer
A primer on Pandas

## Working with datasets
- Read a CSV file

  ```python 
  pd.read_csv(file_path) 
  ```
- Read an excel file
  ```python
  pd.read_excel(file_path) 
  ```
- Read a table [.dat]
  ```python
  pd.read_table(file path, delim_whitespace=True)
  ```

## One-Hot Encoding

## Working with dummy variables
Used to quantify non-numeric categorical variables.

```python
df_dummy = pd.get_dummies[df['column_name']]
# check
df_dummy.head()
```

## Difference between concat(), merge() and join().
- ``` concat()``` is used for appending dataframes. We can append across columns ```set axis = 1``` or across rows ```set axis = 0```.
- ``` merge()``` is used for combining dataframes on the basis of data stored in common columns. 
- ``` join()``` is used for merging dataframes on the basis of index.
