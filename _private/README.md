# Private notes

## Install
conda create -n gym python=3 numpy pandas matplotlib jupyter cmake swig
conda activate gym
pip install -e '.[atari]'
pip install -e '.[box2d]'
pip install -e '.[classic_control]'

