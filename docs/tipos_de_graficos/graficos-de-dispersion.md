Visualizan relaciones entre dos variables.

```python
import plotly.express as px

# Datos aleatorios
df = px.data.iris()

# Creamos el gráfico
fig = px.scatter(df, x="sepal_length", y="sepal_width", color="species", size="petal_length")

# Mostramos el gráfico
fig.show()
```