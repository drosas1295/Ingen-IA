
# Proyecto Ingen-IA
## Miembros del grupo
- Daniel Rosas Mendoza, CC 1036339232, Ingeniería de Materiales
- Danilo Tovar Arias, CC 1193578670, Ingeniería de Sistemas

## Datos
Los datos del proyecto provienen de la competición de [Kraggle Playground Series - Season 3, Episode 6](https://www.kaggle.com/competitions/playground-series-s3e6/overview). Se pueden hacer disponibles descargando las crendenciales de la cuenta de Kaggle [en la sección API](https://www.kaggle.com/settings/account) y seleccionando el kaggle.json descargado a traves del comando
```
from google.colab import files
files.upload()
```
y posteriormente ejecutando las siguientes lineas de codigo:
```
!pip install kaggle
!rm -r ~/.kaggle
!mkdir ~/.kaggle
!mv ./kaggle.json ~/.kaggle/
!chmod 600 ~/.kaggle/kaggle.json
```
```
!kaggle competitions download -c playground-series-s3e6
!unzip playground-series-s3e6.zip
```
Para la visualización de los datos se puede utilizar el siguiente codigo
```
import pandas as pd
df = pd.read_csv('train.csv')
df
```



```
VIDEO SEGUNDA ENTREGA
https://www.youtube.com/watch?v=PQdGbiXTHUs
```
```
VIDEO ENTREGA FINAL 
https://youtu.be/Gj9TsPYIqNw
```
