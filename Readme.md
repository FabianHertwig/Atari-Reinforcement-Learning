# Overview

In this repo im playing around with the OpenAI Gym and reinforcement learning. I am trying to train a model which is able to play breakout.

I am following this blog post: https://becominghuman.ai/lets-build-an-atari-ai-part-1-dqn-df57e8ff3b26



# Dependencies

I am running a conda environment.

Tensorflow

Keras
  
    pip install keras
  

The openAi gym with atari dependencies

    pip install gym[atari]


To view the gym as a gif:
http://nbviewer.jupyter.org/github/patrickmineault/xcorr-notebooks/blob/master/Render%20OpenAI%20gym%20as%20GIF.ipynb

    git clone https://github.com/jakevdp/JSAnimation
    cd JSAnimation
    python setup.py install
    
Matplotlib

    conda install matplotlib
    
ipywidgets

    conda install -c conda-forge ipywidgets

Tqdm
    
    conda install -c conda-forge tqdm
    jupyter nbextension enable --py --sys-prefix widgetsnbextension


    pip install import_ipynb
    