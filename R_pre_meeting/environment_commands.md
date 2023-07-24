# Conda Enviroment Setup

```
conda install -c r r-irkernel
conda install -c conda-forge r-devtools
conda install -c conda-forge r-igraph
conda install -c conda-forge r-cowplot
conda install -c conda-forge r-systemfonts
conda install -c conda-forge r-ragg
conda install -c conda-forge r-pkgdown
conda install -c r r-processx  
conda install -c anaconda fontconfig 
```
## Error 

Devtools not loading in traced this error to 

```
namespace ‘processx’ 3.5.3 is being loaded, but >= 3.6.1 is required
 conda install -c r r-processx 
```

This is fixed with CRAN comand
```
install.packages('processx')
```

## Trailed Attempts (Not sure if they had any affect on the outcome)

```bash
sudo apt-get build-dep libcurl4-gnutls-dev
sudo apt-get install libcurl4-gnutls-dev
sudo apt-get install -y libcurl4-gnutls-dev
sudo apt-get install libxml2-dev
````

Also installed [RStudio](https://computingforgeeks.com/how-to-install-r-and-rstudio-on-ubuntu-debian-mint/), but suprizingly first resoved in jupyter with conda packages
