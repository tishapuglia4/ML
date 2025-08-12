# ML
# SEABORN 
```py
import matplotlib.pyplot as plt
import seaborn as sns
titanic = sns.load_dataset("titanic")
sns.jointplot(x='fare',y='age',data=titanic)
```
