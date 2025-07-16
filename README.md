# 🧵 Fast Fashion Synthetic Sales Dataset (2022–2024)

Este repositorio contiene un dataset sintético de ventas diarias generado para un Trabajo de Fin de Máster en Big Data & Analytics, enfocado en la predicción de demanda inicial de productos nuevos en el sector fast fashion.

## 📁 Estructura

- `data/ventas_fastfashion_2022_2024.csv`: archivo CSV con más de 3 millones de registros.
- `notebook/generar_dataset.ipynb`: notebook interactivo para generar el dataset.
- `src/generar_dataset.py`: script en Python que automatiza la generación.
- `requirements.txt`: librerías necesarias para ejecutar el código.

## 🧠 Variables del Dataset

| Variable          | Tipo     | Descripción |
|------------------|----------|-------------|
| `store_id`        | string   | Código tienda (001–003) |
| `store_name`      | string   | Nombre de tienda |
| `date`            | date     | Fecha de la venta |
| `sku_id`          | int      | ID único del producto |
| `model_id`        | int      | ID del modelo base |
| `color_id`        | int      | Color (01–99) |
| `size_id`         | int      | Talla (34–54) |
| `category_id`     | int      | Categoría del producto (0–7) |
| `season_id`       | int      | Codificación de temporada |
| `quantity_sold`   | int      | Unidades vendidas ese día |
| `initial_stock`   | int      | Stock inicial asignado |
| `remaining_stock` | int      | Stock restante ese día |

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Puedes usarlo libremente con fines académicos o experimentales.

## 📬 Contacto

Cualquier duda o propuesta, puedes contactar con pol.francas@gmail.com .
