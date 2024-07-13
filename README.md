# Heat Wave Insights: Analyzing Regression Models for Accurate Forecasting

<br/>

#### Load Libraries
```{r}
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import warnings
warnings.filterwarnings('ignore')
```
<br/>

#reading data
```{r}
heat_wave = pd.read_csv(r'C:\Users\psagar\Downloads\Data Analytics Projects\Python\Python Projects\Heat Wave Prediction\heat_wave.csv')
heat_wave
```
![image](https://github.com/user-attachments/assets/65477020-3749-4231-b00e-6aff9dee0e10)

<br/>
```{r}
heat_wave.shape
![image](https://github.com/user-attachments/assets/3faf99df-c593-4486-8189-024c3e480a0a)
```


