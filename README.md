# household_electric_power_consumption
Modelo predictivo para el consumo de energía eléctrica en los hogares.
* Jupyter Notebook con el modelo y las explicación de los datos(Power consumption.ipynb). 
* Data usada para el consumo de energía (household_power_consumption.zip).

Para ejecutar: 
* Descargar el repositorio.
* Descomprimir el archivo .zip de los datos de entrenamiento
* Abrir el editor de jupyter y ejecutar el archivo. 

Librerías usadas: 

```import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.preprocessing import MinMaxScaler
from sklearn.metrics import mean_squared_error
from sklearn.model_selection import train_test_split
from sklearn.svm import SVR
```
