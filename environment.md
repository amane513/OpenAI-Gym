### Conda Environment  
_conda info_  
conda version : 4.5.4  
conda-build version : 3.4.1  
python version : 3.6.4.final.0  
base environment : /Users/user/.pyenv/versions/anaconda3-5.1.0  (writable)  

### Change Conda Environment  
_conda info -e_  
base                     /Users/user/.pyenv/versions/anaconda3-5.1.0  
RL                    *  /Users/user/.pyenv/versions/anaconda3-5.1.0/envs/RL  
_source activate RL_  
_source deactivate_  

### Keras-rl Environment
conda create -n RL python=3.7.0 anaconda  
conda install tensorflow  
conda install keras  
pip install keras-rl  

### OpenAI Gym Environment  
conda install cmake  
cd /Users/user/.pyenv/versions/anaconda3-5.1.0/envs/RL/bin  
git clone https://github.com/openai/mujoco-py.git  
cd mujoco-py/  
sudo python setup.py install  
cd ..  
brew install cmake boost boost-python sdl2 swig wget ffmpeg  
git clone https://github.com/openai/gym  
cd gym  
sudo pip install -e .[all]  
