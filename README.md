![forest.jpg](images/forest.jpg)
# Infomap for Ashu Forest Pollination Network
---
### Data :Kyoto University Forest of Ashu -  Kato et al. (1990)
http://www.ecologia.ib.usp.br/iwdb/html/kato_1990.html  
The dataset includes a matrix of the interactions, ie which insect pollinations at on each plant.  
This matrix plotted below.

### Analysis
So far https://www.mapequation.org/infomap/ as looks the clearest
Python install looks trival  
Also have infomap eccology from the paper installed but still dont know whats appering under the hood on that one. 


#### Community detection:  
https://towardsdatascience.com/community-detection-algorithms-9bd8951e7dae

The map equation uses Shannon's source coding theorem (Shannon, 1948) to convert the rates encoded in the codebooks to information measured in bits.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6922315/

#### Modularity analysis
https://en.wikipedia.org/wiki/Modularity_(networks)

### Bipartite
Primary nodes and feature nodes, we can interpret shared feature nodes as indirect relations between primary nodes.


### To Do
- [x] Figure out best form of inputting the data 
- [x] Figure out best way of seting up infomap
- [x] How do we know if we have good/bad results what metric
- [x] Plot of the interactions shows most of the space is dark, maybe we should prune away the bad bits

### Sheets
* matr: interaction matrix of every interaction between pollentor and plant. 
* pla+pol
