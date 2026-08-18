# pandas

```python
import pandas as pd
```

## Load data
```python
df = pd.read_csv("data.csv")
```

## Inspect
```python
df.head()
df.tail()
df.shape
df.columns
df.dtypes
df.info()
df.describe()
```

## Select
```python
df["sales"]
df[["city", "sales"]]
```

## Filter
```python
high_sales = df[df["sales"] > 100]
```

## Missing values
```python
df.isna().sum()
df.dropna()
df["sales"].fillna(0)
```

## Group and aggregate
```python
df.groupby("city")["sales"].mean()
```

## Sort
```python
df.sort_values("sales", ascending=False)
```

## Create a column
```python
df["revenue"] = df["price"] * df["quantity"]
```

## Export
```python
df.to_csv("output.csv", index=False)
```
