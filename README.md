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
23. Reciprocal of Eccentricty ✅

####  These measures are adopted from this repository, where the measures are written in matlab. Here, it is implemented in python. https://github.com/xsxjtu/Complex-Network-Centrality
24. SVDB
25. Semilocal centrality
26. Non backtracking

#### The results files attached are as follows

1. Communities.csv - information about the communities. (no of nodes, no of sink nodes, max indegree, nodes with max indegree)
2. HITZ.csv - HITZ algorithm (hub node nd authority node with max hub and authority score, for each community)
3. bc_cc_kc.csv - Centrality measires(node with max betweeness centrality, closeness centrality and katz centrality with their scores for 13 communities)
4. citation.csv  - citation information (number of citations and number of papers it cite, for each node)
5. cocitation.csv - cocited papers (list of cocited papers for each node and the count of the list)
6. cocitation1.csv - common successors (number of common papers which cite the nodes, for each pair of nodes)
7. katz (1).csv - Katz centrality (node with highest katz score for each centrality)
8. pr_dc_ec.csv - Page rank, Degree centrality and Eigen Centrality (Nodes with highest score for these measures, for each community)
9. prestige.csv - Degree, Proximity and Rank Prestige (for 10 communities)
10. re_cc_kc.csv - Reciprocal of Eccentrity, Closeness and Katz centrality (27 communities)
11. source_nodes.csv - Source node of each community
12. voterank.csv - Voterank Algorithm (node with highest score for each community)
