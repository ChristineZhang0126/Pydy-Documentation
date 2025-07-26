# Pydy Documentation
## Installation

1. Run the following command
```
docker run --gpus all -it --rm -p 8888:8888 -p 8000:8000 -v "$(pwd)/notebooks:/tf/notebooks" -w /tf/notebooks tensorflow/tensorflow:latest-gpu-jupyter bash -c "pip install pydy pythreejs ipywidgets && jupyter notebook --ip=0.0.0.0 --port=8888 --no-browser --allow-root"
```
## Usage
