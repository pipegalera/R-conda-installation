# R-conda-installation

```
conda create -n R jupyter -y
conda activate R
conda install conda-forge::r-base -y
conda install conda-forge::r-irkernel -y
conda install conda-forge::r-tidyverse -y
```

### Open R from Terminal:
`IRkernel::installspec(user=FALSE, name = 'ir41', displayname = 'R 4.1')`

install.packages('caret', dependencies = TRUE)
install.packages('ggplot2')
install.packages('glue')
install.packages('recipes')
install.packages('pROC')
install.packages('arrow')
install.packages('dplyr')
install.packages('readxl')
install.packages('doParallel')
