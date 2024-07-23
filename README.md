![forest.jpg](images/forest.jpg)
# Infomap for Ashu Forest Pollination Network
In this project we investgate communities structures in the Ashu Forest Pollination Network through using the Map Equation through InfoMap. We investigate this for both Monopartitie and Bipartite network structure's and then investigate the role of extinction. We pooled all the results into a common analysis in order to contextualize the various results. 


### What is Infomap?
Infomap is a clustering algorithm used for detecting communities in complex networks by leveraging information theory though the map equation. It identifies community structures by modeling the flow of information on the network as a random walk. Infomap works by representing the network as a map where each node is a location and the connections are pathways for information flow. It then seeks to compress a description of this flow by finding an optimal partition of the network into modules, or communities, that minimizes the description length. Essentially, it assigns nodes to communities in a way that maximizes the retention of information within communities while minimizing the flow between them, thereby revealing the network's underlying modular structure.

### The Map Equation


$$L(\mathrm{M})=q_{\curvearrowright} H(\mathcal{Q})+\sum_{i=1}^m p_{\circlearrowright}^i H\left(\mathcal{P}^i\right)$$
* $q_{\curvearrowright}$  is the probability that the random walker switches from one module to another.
* $H(\mathcal{Q})$  is the entropy of the module-level codebook, representing the uncertainty in predicting which module the walker will move to next.
* $m$ is the number of modules.
* $p_{\circlearrowright}^i$ is the fraction of time the walker spends in module $i$.
* $H(\mathcal{P}^i$ is the entropy of the codebook for module $i$, representing the uncertainty in predicting which node within the module the walker will move to next.


The map equation utilizes Shannon's source coding theorem to optimize the compression of a network's description by capturing its community structure. Shannon's theorem states that the most efficient way to encode a message is proportional to the negative logarithm of its probability, which minimizes the expected length of the code.


### [Dataset :Pollinator Network of Kyoto University Forest of Ashu -  Kato et al. (1990)](http://www.ecologia.ib.usp.br/iwdb/html/kato_1990.html)
The research was conducted at the Kyoto University Forest of Ashu, located at the northeastern edge of Kyoto Prefecture, Japan, from 1984 to 1987. This study examines the flowering phenology of 91 plant species, the community structure of flower-visiting insects, and the range of floral hosts for these visitors. The focus is on the community organization patterns of flower-visiting insects within a primary forest ecosystem in western Japan.
![image](https://github.com/user-attachments/assets/39544f8d-5e92-4a25-9f73-bc64e916bbf1)


