Compara diferentes categorías.

```python
import plotly.graph_objects as go

categorias = ['A', 'B', 'C', 'D']
valores = [10, 15, 7, 12]

fig = go.Figure(data=go.Bar(x=categorias, y=valores))
fig.show()
```