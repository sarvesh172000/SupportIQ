For training data cleaning :

1) Import library : Pandas and numpy 
2) Load dataset
3) check data :
    df.info()
    df.head()
    df.duplicated()
    df.isnull.sum()
    round((df.isnull.sum()/df.shape[0]*100),2)
4) handling misiing data : Using nullness
5) Standardize column names 
6) Convert Date to standard form