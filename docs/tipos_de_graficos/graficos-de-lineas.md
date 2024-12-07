Muestran tendencias a lo largo del tiempo o de una variable.

```python
import plotly.graph_objects as go

x = [1, 2, 3, 4, 5]
y = [10, 20, 15, 30, 25]

fig = go.Figure(data=go.Scatter(x=x, y=y, mode='lines+markers', name='Tendencia'))
fig.show()
```