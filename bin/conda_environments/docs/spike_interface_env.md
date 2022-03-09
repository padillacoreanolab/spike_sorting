# Install using Conda install
# Creating Conda Environment
conda create --prefix ./spike_interface_env python=3.7
conda activate ./spike_interface_env/

# Configuring Channels
conda config --add channels defaults
conda config --add channels flatiron
conda config --add channels conda-forge

# Installing Spikeinterface and other programs
conda install -c conda-forge jupyterlab 
./spike_interface_env/bin/pip install spikeinterface==0.91.0
./spike_interface_env/bin/pip install mountainsort4
./spike_interface_env/bin/pip install mountainlab-pytools
./spike_interface_env/bin/pip install spikeforestwidgets
conda install -c conda-forge matplotlib 

# Installing Jupyter Notebook Extensions
jupyter nbextension enable --py --sys-prefix jp_proxy_widget