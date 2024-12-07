Muestran valores en una matriz.

```python
import plotly.graph_objects as go
import numpy as np

z = np.random.rand(5, 5)  # Matriz aleatoria de 5x5

fig = go.Figure(data=go.Heatmap(z=z))
fig.show()
```