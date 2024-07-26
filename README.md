

# MacOS: R-conda-installation

```
conda create -n R jupyter -y
conda activate R
conda install conda-forge::r-base -y
conda install conda-forge::r-irkernel -y
conda install conda-forge::r-tidyverse -y
```

# Ubuntu Server
```
sudo apt update
sudo apt install r-base r-base-dev -y
```

### Open R from Terminal:

```
install.packages('IRkernel')
install.packages('ggplot2')
install.packages('glue')
install.packages('recipes')
install.packages('pROC')
install.packages('dplyr')
install.packages('readxl')
install.packages('doParallel')
install.packages('arrow')
install.packages('caret', dependencies = TRUE)
IRkernel::installspec(user=FALSE, name = 'ir41', displayname = 'R 4.1')

```
