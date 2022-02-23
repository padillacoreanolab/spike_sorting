## Commands Used

```
conda deactivate
conda create --prefix ./mountain_sort_env  python=3.6
conda activate ./mountain_sort_env
conda config --add channels defaults
conda config --add channels flatiron
conda config --add channels conda-forge
```

### Installing MountainSort Libraries
```
conda install -c flatiron mountainlab
conda install -c flatiron mountainlab_pytools
conda install -c flatiron ml_ephys
conda install -c flatiron ml_ms3
conda install -c flatiron ml_ms4alg
conda install -c flatiron ml_pyms
conda install -c flatiron qt-mountainview 
```

## Commands to experiment with

### Installing Jupyter Notebook Libraries
```
conda install -c conda-forge jupyterlab=2.2.0
conda install -c flatiron -c conda-forge spikeforestwidgets
pip install --upgrade jupyter_client
jupyter nbextension enable --py --sys-prefix jp_proxy_widget
conda install -c conda-forge nodejs=12
jupyter labextension install @jupyter-widgets/jupyterlab-manager --no-build
jupyter labextension install jp_proxy_widget --no-build
jupyter lab build
```

### Notes
- Using older versions of Python, Jupyterlab, and Nodejs
- Install updated version of node js or not
- Install Jupyterlab first or later
- Skip using Jupyterlab