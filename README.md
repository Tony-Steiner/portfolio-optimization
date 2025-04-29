# portfolio Optimization

Descripción corta del proyecto:
Un pipeline en Python para descargar datos de mercado, optimizar la asignación de activos bajo el modelo de media-varianza de Markowitz, y backtesting con ventanas deslizantes.

## Índice
1. [Objetivo](#objetivo)  
2. [Estructura del repositorio](#estructura-del-repositorio)  
3. [Requisitos](#requisitos)  
4. [Instalación](#instalación)  
5. [Uso](#uso)  
6. [Estructura de carpetas](#estructura-de-carpetas)  
7. [Contribuciones](#contribuciones)  
8. [Licencia](#licencia)

---

### Objetivo
Explicar brevemente qué problema resuelve el proyecto y qué métodos estadísticos o cuantitativos utiliza.

### Estructura del repositorio
- `data/`  
  - `snapshots/` (datos raw guardados)  
- `src/`  
  - `download_data.py`  
  - `preprocess.py`  
  - `optimize.py`  
  - `backtest.py`  
- `notebooks/` (Jupyter notebooks exploratorios)  
- `requirements.txt`  
- `README.md`  
- `LICENSE`

### Requisitos
- Python 3.8+  
- Bibliotecas: pandas, numpy, cvxpy (u otro solver), yfinance, matplotlib, scikit-learn  
- Git

### Instalación
```bash
git clone https://github.com/tu_usuario/portfolio-optimization.git
cd portfolio-optimization
python -m venv venv
source venv/bin/activate       # o `venv\Scripts\activate` en Windows
pip install -r requirements.txt
