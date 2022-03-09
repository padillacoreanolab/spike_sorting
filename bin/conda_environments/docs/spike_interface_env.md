
# Creating Conda Environment
conda create --prefix ./spike_interface_env python=3.7
conda activate ./spike_interface_env/\

# Installing Spikesorting and other programs
./spike_interface_env/bin/pip install jupyter
./spike_interface_env/bin/pip install mountainsort4
./spike_interface_env/bin/pip install spikeinterface==0.91.0
./spike_interface_env/bin/pip install pandas
./spike_interface_env/bin/pip install matplotlib
./spike_interface_env/bin/pip install networkx
