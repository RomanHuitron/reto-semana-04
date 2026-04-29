# Sistema de Inventario Modular

## Descripcion
Sistema que genera reportes de productos que necesitan reorden.

## Estructura del Proyecto
- `main.py`: Punto de entrada del programa que orquesta la lectura, procesamiento y generación del reporte.
- `models/`: Contiene los modelos de dominio del sistema (clase `Producto`).
- `utils/`: Contiene módulos auxiliares, incluyendo validadores de datos (`validators.py`) y funciones de entrada/salida de archivos (`io.py`).
- `data/`: Directorio de origen que almacena el archivo de datos inicial (`inventario.csv`).
- `outputs/`: Directorio de destino donde el sistema guarda el archivo final generado (`reporte_inventario.csv`).

## Como Ejecutar
```bash
python main.py