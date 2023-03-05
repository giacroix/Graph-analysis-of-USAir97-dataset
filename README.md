# Graph-analysis-of-USAir97-dataset

Motivation  
Are there nodes with a particularly high centrality with respect to the others? If yes, what do they represent in reality?
Do closeness centrality and betweenness centrality lead to similar nodes’ scores? Why?
Is the clustering coefficient a significant value for this network and what does it represent?

Method  
Our idea is to apply some of the algorithms that we are studying in the course to the selected dataset, in order to have a clearer idea about them and be able to see what the results mean in practice.
We want to use snap.py or networkx as main tool for the analyses, but trying also to implement some algorithms from scratch, taking inspiration from the pseudocode explained during the lectures.
The algorithms that we want to deal with are:
- algorithm for computing the exact closeness centrality of each node in G;  
- Eppstein-Wang Algorithm to compute an approximation of the closeness centralities;  
- Brande’s algorithm for computing the exact betweenness centralities;  
- approximate algorithm to compute the betweenness centralities;  
- exact algorithm to compute the exact clustering coefficient of a graph;  
- approximation algorithm to estimate the clustering coefficient.  

<a/>
Notice that we want to start with exact algorithms and then compare times and results with approximations. 
Therefore, our purpose is also to see how the two approaches differ related to the selected dataset.
Finally, we want to compare the obtained results with values extracted from random graphs, in order to understand which results can be considered meaningful. 
Then we want to understand what those results stand for in the reality (for example what a node with a high centrality represents).
