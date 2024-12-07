Ideales para mostrar proporciones.

```python	
import plotly.graph_objects as go

# Datos ficticios representando porcentajes de ventas por producto
labels = ['Producto A', 'Producto B', 'Producto C', 'Producto D']
values = [35, 25, 20, 20]

# Creamos el gráfico de pastel
fig = go.Figure(data=[go.Pie(labels=labels, values=values, hole=0.3)])

# Personalizaciones
fig.update_layout(
    title_text="Porcentaje de ventas por producto",
    annotations=[dict(text='Producto A', x=0.18, y=0.5),
                 dict(text='Producto B', x=0.82, y=0.5),
                 dict(text='Producto C', x=0.25, y=0.8),
                 dict(text='Producto D', x=0.75, y=0.8)])

# Mostrar el gráfico
fig.show()
```