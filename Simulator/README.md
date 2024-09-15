Eerste systeem (rapidtest workstation x299 10th gen intel)
Driver Version: 550.90.07      CUDA Version: 12.4
NVIDIA RTX A5000
NVIDIA GeForce RTX 3090 x 1 water-cooled

Second systeem (simulation server)
NVIDIA GeForce RTX 3090 x 2 water-cooled
NVIDIA GeForce RTX 4090

Software:
Ubuntu 24.04
Setup script voor environment reset_jupyter_py311_env
Environment source ~/jupyter_py311_env/bin/activate
Rapids installatie: https://rapids.ai/
pip install \
--extra-index-url=https://pypi.nvidia.com \
cudf-cu12==24.8.* \
dask-cudf-cu12==24.8.* \
cuml-cu12==24.8.* \
cugraph-cu12==24.8.*
Environment source: source ~/rapids_env/bin/activate