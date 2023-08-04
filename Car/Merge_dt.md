```py
# Merge the two datasets based on the common attribute "carID"
New_merged_data = pd.merge(dt1, dt2, on='carID')

print("Merged Dataset:")
print(New_merged_data)
```
