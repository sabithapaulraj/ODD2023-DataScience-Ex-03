# ODD2023-DataScience-Ex-03
# Ex03-Univariate-Analysis
## Aim:
To read the given data and perform the univariate analysis with different types of plots.
## Eplanation:
Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.
## Algorithm:
- Step 1: Read the given data.
- Step 2: Get the information about the data.
- Step 3: Remove the null values from the data.
- Step 4: Mention the datatypes from the data.
- Step 5: Count the values from the data.
## Program:
```
Developed By : Sabitha P
Register number: 212222040137
```
### Superstore.csv
```
import pandas as pd
import numpy as np
import seaborn as sns
df=pd.read_csv('SuperStore.csv')
print(df)
df.head()
df.info()
df.dtypes
df['Postal Code'].value_counts()
sns.boxplot(x='Postal Code', data=df)
sns.countplot(x='Postal Code',data=df)
sns.distplot(df["Postal Code"])
df.describe()
```
### Diabetes.csv
```
import pandas as pd
import numpy as np
import seaborn as sns
df = pd.read_csv("/diabetes.csv")
df
df.info()
df.isnull().sum()
df.dtypes
df.describe()
df['Glucose'].value_counts()
sns.boxplot(x="Glucose",data=df)
sns.countplot(x="Glucose",data=df)
sns.distplot(df['Glucose'])
sns.histplot(x="Glucose",data=df)
df.skew()
df.kurtosis()
```
## Output:
### Superstore.csv
![image](https://github.com/sabithapaulraj/ODD2023-DataScience-Ex-03/assets/118343379/c60a7a52-7471-4268-858b-1415bbb0f46a)
![image](https://github.com/sabithapaulraj/ODD2023-DataScience-Ex-03/assets/118343379/bdcb6b85-484f-4005-9b20-445ad099e3d4)
![image](https://github.com/sabithapaulraj/ODD2023-DataScience-Ex-03/assets/118343379/9035cc15-c3f6-4352-b3b9-57285f553aad)
![image](https://github.com/sabithapaulraj/ODD2023-DataScience-Ex-03/assets/118343379/fe714f68-e92f-484d-b03e-fd2b28aa4543)
![image](https://github.com/sabithapaulraj/ODD2023-DataScience-Ex-03/assets/118343379/d543e026-8edd-416b-8009-504f352a9a2a)
![image](https://github.com/sabithapaulraj/ODD2023-DataScience-Ex-03/assets/118343379/e9681923-7b3a-4888-9988-f7a06991aab9)
![image](https://github.com/sabithapaulraj/ODD2023-DataScience-Ex-03/assets/118343379/fad76c98-c6d8-46b4-9c73-0fecdffebb66)
![image](https://github.com/sabithapaulraj/ODD2023-DataScience-Ex-03/assets/118343379/6a4e99cb-cde5-4d1f-950a-34a60a87e229)
![image](https://github.com/sabithapaulraj/ODD2023-DataScience-Ex-03/assets/118343379/5bb9cea3-5e34-4188-a46a-3899f5d632c6)
![image](https://github.com/sabithapaulraj/ODD2023-DataScience-Ex-03/assets/118343379/7c272e67-24ec-4585-92d6-cc4866dbb83b)
![image](https://github.com/sabithapaulraj/ODD2023-DataScience-Ex-03/assets/118343379/031212a1-4a9c-436c-8f40-a5458c2ca169)
![image](https://github.com/sabithapaulraj/ODD2023-DataScience-Ex-03/assets/118343379/20748a99-e923-4dc4-a4d7-74801e8fe555)
![image](https://github.com/sabithapaulraj/ODD2023-DataScience-Ex-03/assets/118343379/48475314-e343-46df-943c-140628cd69e4)
![image](https://github.com/sabithapaulraj/ODD2023-DataScience-Ex-03/assets/118343379/a11dce04-82d6-416a-a6cb-ed6277d0e21c)
![image](https://github.com/sabithapaulraj/ODD2023-DataScience-Ex-03/assets/118343379/d3fb314b-dd41-4110-97dc-8b8c771bbc09)

### Diabetes.csv

![image](https://github.com/sabithapaulraj/ODD2023-DataScience-Ex-03/assets/118343379/d1aac8c3-2e80-444b-88ca-49fee892ad90)
![image](https://github.com/sabithapaulraj/ODD2023-DataScience-Ex-03/assets/118343379/5967e6c8-e96f-4358-aff9-297eeb0f732e)
![image](https://github.com/sabithapaulraj/ODD2023-DataScience-Ex-03/assets/118343379/54066bb9-421d-4585-9b90-5ada1b8ca95c)
![image](https://github.com/sabithapaulraj/ODD2023-DataScience-Ex-03/assets/118343379/9ebc6045-af61-4125-be5d-da671e12ea5f)
![image](https://github.com/sabithapaulraj/ODD2023-DataScience-Ex-03/assets/118343379/f10c5902-edbd-4019-9d52-e502bd65cc07)
![image](https://github.com/sabithapaulraj/ODD2023-DataScience-Ex-03/assets/118343379/ceadce74-aa9d-4094-832d-8c276bbbb165)
![image](https://github.com/sabithapaulraj/ODD2023-DataScience-Ex-03/assets/118343379/8fbc140e-d36c-468d-8e39-b0ca43e1818a)
![image](https://github.com/sabithapaulraj/ODD2023-DataScience-Ex-03/assets/118343379/e3ca64a3-f793-4053-8ebd-5ed0975c2810)
![image](https://github.com/sabithapaulraj/ODD2023-DataScience-Ex-03/assets/118343379/12984e47-e993-4321-95fe-c833eda0630f)

## RESULT:
Hence the univariate analysis is performed on the given dataset.

