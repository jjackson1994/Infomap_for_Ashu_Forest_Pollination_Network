![forest.jpg](images/forest.jpg)
# Infomap for Ashu Forest Pollination Network
---

In this project we investgate communities structures in the Ashu Forest Pollination Network through using the Map Equation through InfoMap. We investigate this for both Monopartitie and Bipartite network structure's and then investigate the role of extinction. We pooled all the results into a common analysis in order to contextualize the various results. 


### What is Infomap?
Infomap is a clustering algorithm used for detecting communities in complex networks by leveraging information theory though the map equation. It identifies community structures by modeling the flow of information on the network as a random walk. Infomap works by representing the network as a map where each node is a location and the connections are pathways for information flow. It then seeks to compress a description of this flow by finding an optimal partition of the network into modules, or communities, that minimizes the description length. Essentially, it assigns nodes to communities in a way that maximizes the retention of information within communities while minimizing the flow between them, thereby revealing the network's underlying modular structure.

### Data :Kyoto University Forest of Ashu -  Kato et al. (1990)
http://www.ecologia.ib.usp.br/iwdb/html/kato_1990.html  
The dataset includes a matrix of the interactions, ie which insect pollinations at on each plant.  
This matrix plotted below.

#### Community detection:  
The map equation uses Shannon's source coding theorem (Shannon, 1948) to convert the rates encoded in the codebooks to information measured in bits.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6922315/

