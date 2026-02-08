# DS-LAB1 - Detección de Phishing

Laboratorio de análisis y detección de URLs de phishing utilizando Machine Learning.

## Requisitos previos

- Python 3.8 o superior
- pip (gestor de paquetes de Python)

## Instalación

### 1. Crear un entorno virtual

**Windows:**
```bash
python -m venv pishing
```

**macOS/Linux:**
```bash
python3 -m venv pishing
```

### 2. Activar el entorno virtual

**Windows (CMD):**
```bash
pishing\Scripts\activate
```

**Windows (PowerShell):**
```bash
.\pishing\Scripts\Activate.ps1
```

**macOS/Linux:**
```bash
source pishing/bin/activate
```

### 3. Instalar las dependencias

```bash
pip install -r requierments.txt
```

## Ejecución del notebook

Una vez activado el entorno virtual e instaladas las dependencias, ejecutar:

```bash
jupyter notebook pishing.ipynb
```

O simplemente abrir el archivo `pishing.ipynb` en VS Code con la extensión de Jupyter instalada.

## Estructura del proyecto

- `pishing.ipynb` - Notebook principal con el análisis
- `dataset_pishing.csv` - Dataset con URLs para clasificación
- `requierments.txt` - Dependencias del proyecto

## Integrantes

- Javier Prado — 21486
- Bryan España — 21550