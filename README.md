# install_pygedm
## error: f2c.h no such file or directory
##  solve:
conda activate FRB-env

conda install -c conda-forge f2c

pip install --global-option=build_ext --global-option="-I/home/xxx/anaconda3/envs/FRB-env/include/" pygedm
