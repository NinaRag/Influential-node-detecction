# Influential-node-detection

This project is about finding the importance of the node in a community, which is formed based on the source nodes. The communities are formed using DFS traversal of the seed node. The dataset used is hep-th dataset. The following metrics are implemented for influential node detection

#### Libraries and Tools used
Graphia software for graph visulaization
Networkx. Refer this for further information: https://networkx.org/documentation/stable/reference/introduction.html

#### Resources used for Reference
Centiserver is a website which contains the information about all the centrality measures used in various problem domains. Refer this for more information: https://www.centiserver.org/

#### Why do we need many centrality measures?

1. optimal for one application while performs worse for a different application.
2. features which identify the most important vertices in a given network do not necessarily generalize to the remaining vertices.

#### The measures that have been implemented are as follows. Description about the measures could be found in the document.

1. Degree centrality ✅
2. Closeness centrality ✅
3. Betweeness centrality ✅
4. Harmonic centrality
5. Eigenvector centrality ✅
6. Katz centrlaity ✅
7. Percolation centrality
8. PageRank ✅
9. Freeman centrality
10. Cross clique
11. Dissimilarity measures
12. HITZ algorithm ✅
13. Degree prestige ✅
14. Proximity prestige ✅
15. Rank Prestige ✅
16. Shapley–Shubik power index
17. Voterank ✅
18. Leaderrank ✅
19. TARank ✅
20. Cocitations ✅
21. Hybrid degree centality ✅
22. Expected force of infection ✅

####  These measures are adopted from this repository, where the measures are written in matlab. Here, it is implemented in python. https://github.com/xsxjtu/Complex-Network-Centrality
23. SVDB
24. Semilocal centrality
25. Non backtracking

#### The results files attached are as follows

1.
2.
3.
4.
5.
6.
