# Installation

install anaconda
```
wget https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh

bash Miniconda3-latest-Linux-x86_64.sh -b

export PATH="~/miniconda3/bin:$PATH"

rm Miniconda3-latest-Linux-x86_64.sh
```

setup conda env
```
conda create -n cluster-dns-rambo python=3.7

source activate cluster-dns-rambo
```
