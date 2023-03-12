# Proyecto Ingen-IA
## Miembros del grupo
- Daniel Rosas Mendoza, CC 1036339232, Ingeniería de Materiales
- Danilo Tovar Arias, CC 1193578670, Ingeniería de Sistemas

## Datos
Los datos del proyecto provienen de la competición de [Kraggle Playground Series - Season 3, Episode 6](https://www.kaggle.com/competitions/playground-series-s3e6/overview). Se pueden hacer disponibles ejecutando desde cualquier notebook Collab los comandos
```
from google.colab import files
uploaded = files.upload()
```
y posteriormente seleccionando los archivos _train.csv_ o _test.csv_ extraidos desde la descarga en la competición.
Para la visualización de los datos se puede utilizar el siguiente codigo
```
import pandas as pd
df = pd.read_csv('train.csv')
df
```
