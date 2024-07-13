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


heat_wave.shape
<br/>
![image](https://github.com/user-attachments/assets/3423d878-e14d-4bf7-9469-6fd2d58cceb8)
<br/>
heat_wave.columns
![image](https://github.com/user-attachments/assets/d982e380-e697-497a-83e6-dbeb30637714)
<br/>
#identifying duplicates
heat_wave.duplicated().sum()
0
<br/>
#identifying null values
heat_wave.isnull().sum()
<br/>
Present_Tmax        61
<br/>
Present_Tmin        61
<br/>
LDAPS_RHmin         65
<br/>
LDAPS_RHmax         65
<br/>
LDAPS_Tmax_lapse    65
<br/>
LDAPS_Tmin_lapse    65
<br/>
LDAPS_WS            65
<br/>
LDAPS_LH            65
<br/>
LDAPS_CC1           65
<br/>
LDAPS_CC2           65
<br/>
LDAPS_CC3           65
<br/>
LDAPS_CC4           65
<br/>
LDAPS_PPT1          65
<br/>
LDAPS_PPT2          65
<br/>
LDAPS_PPT3          65
<br/>
LDAPS_PPT4          65
<br/>
lat                  0
<br/>
lon                  0
<br/>
DEM                  0
<br/>
Slope                0
<br/>
Solar radiation      0
<br/>
Next_Tmax           22
<br/>
dtype: int64
<br/>



