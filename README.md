# fractal_gpt   

> Annotated version of Karpathy's nanoGPT video.    

The Jupyter notebooks inside of `nbs` step through each section of the video, with added context and more examples.  

Then, everything is put together into a final notebook at the end.  

The python files inside `annotatedGPT` are exported directly from the notebooks. 

# Setup  

You can use your favorite python environment manager to install `requirements.txt`. Below we we `mamba` which is a better version of `anaconda` with great coverage of ML and scientific libraries.   

## Install the mamba package manager  

### Using `homebrew` on Mac:    

brew install micromamba  

## Installations for other OS's and setups:  

https://mamba.readthedocs.io/en/latest/installation.html#manual-installation  

## Setting up the environment  

### Create the virtual environment:  

The environment will be called `fractal_gpt` and it uses python version 3.11.  
```bash
micromamba create --name fractal_gpt python=3.11 
```

### Activate the virtual environment:  

```bash
micromamba activate fractal_gpt 
```
 
### Install the required libraries inside the environment:  

```bash
pip install -r requirements.txt
```