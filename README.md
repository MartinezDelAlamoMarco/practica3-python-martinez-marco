# Práctica 3: Python — Martínez, Marco

## Descripción
Resolución de los 20 ejercicios de la Práctica 3 sobre listas, funciones y
paquetes, NumPy, diccionarios y pandas, lógica y control de flujo, y bucles.

## Entorno
- Python 3.12
- JupyterLab
- NumPy, pandas (ver `requirements.txt`)

## Estructura del repositorio
| Carpeta | Contenido |
| --- | --- |
| `data/` | Ficheros CSV de partida |
| `notebooks/` | Notebook con la resolución |
| `src/` | Módulo de funciones auxiliares (`utilidades.py`) |
| `outputs/` | Ficheros generados durante la ejecución del notebook |

## Cómo reproducir
```bash
python3.12 -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab notebooks/practica3_python.ipynb
```

Una vez abierto, `Kernel → Restart Kernel and Run All Cells` para ejecutar todo el notebook de arriba a abajo.

## Notas
- Los tres CSV de `data/` son los que se dan con el enunciado, sin modificar.
- `outputs/` contiene `facturacion_por_region.csv` (ejercicio 15) e `ingenieria_remoto_senior.csv` (ejercicio 18), generados al ejecutar el notebook.
- Comprobé las cifras de control de cada bloque contra las del enunciado antes de comitear (facturación total, región líder, lecturas en alarma, etc.).
