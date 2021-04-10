# Social-Network-Analysis-Project
Social Network Analysis Project as a homework on Network Science course on Data Sciense Master Program in HSE

The task was to make ego-network based of my social network (I choose VK) and to do descriptive analysis about the network. Namely the following:

> ## Network Summary 
>- Network source and preprocessing
>-	Node/Edge attributes
>-	Size, Order
>-	Diameter, radius
>-	Clustering Coefficient (global, average local, histogram of locals)
>-	Average path length (+histogram)
>-	Degree distribution, fitting models and coefficient from regression/MLE/KS-test
>-	Gorgeous network layout

> ## Structural Analysis 
>-	The closest random graph model similar to your social network (compare at least three models from lectures, such as ER, BA, WS). Check three real-world network properties on chosen random graph models and your ego-network, compare the results
>-	Degree/Closeness/Betweenness centralities (optional: Katz, Bonacich) 
>-	Top nodes interpretation (not just surnames, but how are they related to you)
>-	Page-Rank. HITS. Correlation comparison of centralities and prestige. Comparison of top nodes
>-	Assortative Mixing according to node attributes (usually sex, city, educational status)
>-	Node structural equivalence/similarity (interpret how they are similar from communicative patterns)

> ## Community Detection 
> -	Clique search, k-cores visualization and interpretation
> -	Best results of various community detection algorithms, both in terms of interpretation and some quality criterion (modularity, silhouette, ground truth partition)
> -	The results should be visible on the network layout
> -	Interpretations should be written over image with community detection (use Paint, for e.g.)

### [Collecting data from vk notebook](https://github.com/upayuryeva/Social-Network-Analysis-Project/blob/main/SN_project_collect_data.ipynb)  
*Collects data with the help of vk-api and makes graph. Returns file with edges [friends_edges.txt](https://github.com/upayuryeva/Social-Network-Analysis-Project/blob/main/friends_edges.txt), file with edges attributes [friends_edges_attributes.txt](https://github.com/upayuryeva/Social-Network-Analysis-Project/blob/main/friends_edges_attributes.txt) and file with final graph [friends_graph.gexf](https://github.com/upayuryeva/Social-Network-Analysis-Project/blob/main/friends_graph.gexf)*

### [Descriptive analysis notebook](https://github.com/upayuryeva/Social-Network-Analysis-Project/blob/main/SN_project_main_source.ipynb)
*Take file of finnal graph [friends_graph.gexf](https://github.com/upayuryeva/Social-Network-Analysis-Project/blob/main/friends_graph.gexf) and do all analysis in the task  
SVG and PNG files was made by [Gephi The Open Graph Viz Platform](https://gephi.org)*

### [Presentation file](https://github.com/upayuryeva/Social-Network-Analysis-Project/blob/main/Yuryeva_presentation.pdf)
