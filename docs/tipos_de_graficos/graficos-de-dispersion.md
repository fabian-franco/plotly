Visualizan relaciones entre dos variables.

```python
import plotly.graph_objects as go

x = [1, 2, 3, 4, 5]
y = [10, 14, 19, 25, 32]

fig = go.Figure(data=go.Scatter(x=x, y=y, mode='markers', name='Puntos'))
fig.show()
```