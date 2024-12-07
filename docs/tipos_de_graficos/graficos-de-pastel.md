Ideales para mostrar proporciones.

```python	
import plotly.graph_objects as go

labels = ['Manzanas', 'Bananas', 'Naranjas']
values = [450, 300, 150]

fig = go.Figure(data=go.Pie(labels=labels, values=values))
fig.show()
```