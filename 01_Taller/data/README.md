# Dataset de Seguros (Kaggle)

Fuente: https://www.kaggle.com/datasets/mirichoi0218/insurance

Este directorio debe contener el archivo:

- `insurance.csv`

## Opcion 1: Descarga manual

1. Ir al enlace de Kaggle.
2. Descargar el dataset.
3. Extraer y copiar `insurance.csv` dentro de este directorio.

## Opcion 2: Descarga por CLI de Kaggle

Requiere tener la API key de Kaggle configurada en `~/.kaggle/kaggle.json`.

```bash
pip install kaggle
kaggle datasets download -d mirichoi0218/insurance -p 01_Taller/data --unzip
```
