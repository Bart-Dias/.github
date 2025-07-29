Para rodar local é necessário rodar o backend e o jupyterlab apontando para este backend, você pode utilizar tais scripts para automatizar o processo:


Necessário ter o Conda instalado e uma pasta ~/workspace no home


# Conda

Instale o conda

```
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
bash Miniconda3-latest-Linux-x86_64.sh
```

Baixe o repo backend e o repo jupyterlab e ative os respectivos envs

Em cada repo possui o environment.yml para importar no conda

```
conda env create -f environment.yml
```

# Backend

/home/galba.arueira/backendproxy/startBartBackend.sh 

[startBartBackend.sh](https://github.com/Bart-Dias/backendproxy/blob/main/startBartBackend.sh)

# JupyterLab

/home/galba.arueira/startJupyterLab.sh

[startJupyterLab](https://github.com/Bart-Dias/jupyter-ai-ide/blob/main/startJupyterLab.sh)
