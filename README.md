# MFDA Experiment 8: PCA for Engine Health Monitoring
Dataset: NASA C-MAPSS FD001 (NASA PCoE repository). Follows Experiment 4 (sensor correlation).
## Setup
python3 -m venv pca_env && source pca_env/bin/activate
python -m pip install -r requirements.txt
Place train_FD001.txt, test_FD001.txt, RUL_FD001.txt in data/raw/
## Run
python -m notebook  → notebooks/exp8_pca_health.ipynb → Restart & Run All
## Outputs
figures/fig01–fig11, data/processed/*.csv, *.npy
Tested: Python 3.12, numpy 2.5.5, pandas 3.1.1, scikit-learn 1.9.1, matplotlib 3.11.2, scipy 1.18.1
