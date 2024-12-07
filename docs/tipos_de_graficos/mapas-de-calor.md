Muestran valores en una matriz.

```python
import plotly.figure_factory as ff

# Datos aleatorios
z = [[1, 20, 30],
     [20, 1, 60],
     [30, 60, 1]]

# Creamos el gráfico
fig = ff.create_annotated_heatmap(z=z)

# Mostramos el gráfico
fig.show()
```