pip install --upgrade pip setuptools wheel
pip install -r requirements.txt
export CMAKE_PREFIX_PATH=${CONDA_PREFIX:-"$(dirname $(which python))/../"}
