## Commands Used

`conda deactivate`
`conda create --prefix ./mountain_sort_env  python=3.6`
`conda activate ./mountain_sort_env`
`conda config --add channels defaults`
`conda config --add channels flatiron`
`conda config --add channels conda-forge`
`conda install -c conda-forge jupyterlab`
`conda install -c conda-forge nodejs`
### Installing MountainSort Libraries
`conda install -c flatiron mountainlab`
`conda install -c flatiron mountainlab_pytools`
`conda install -c flatiron ml_ephys`
`conda install -c flatiron ml_ms3`
`conda install -c flatiron ml_ms4alg`
`conda install -c flatiron ml_pyms`
### Installing Jupyter Notebook Libraries
`conda install -c flatiron -c conda-forge spikeforestwidgets`
`jupyter nbextension enable --py --sys-prefix jp_proxy_widget`
`jupyter labextension install @jupyter-widgets/jupyterlab-manager --no-build`
`jupyter labextension install jp_proxy_widget --no-build`
`jupyter lab build`