# assignment-5
##Author
-Asra Tasneem Shaik

##Date
-04/28/2024

##Programming Language & Dependicies
-Python
-Libraries: pandas, networkx, numpy, scipy

##Description
-In this assignment, the task is with conducting a topological analysis of the human protein interaction network. Your objectives include calculating the degree centrality and local clustering coefficients for each protein node to assess node connectivity and local network density. 
-Additionally, compute the global clustering coefficient to evaluate the network's overall cliquishness and verify if the network exhibits scale-free characteristics by analyzing the degree distribution.
-For the second segment, you will calculate shortest path lengths among protein pairs in two distinct datasets using Dijkstra's algorithm.
-Utilize statistical tests like the Wilcoxon test to compare these path length distributions, thereby quantifying structural variability between the two protein sets within the network framework.


##input_files
-Human_PPI.csv
-protein1.csv
-protein2.csv

##Results
-Calculated degree centrality and clustering coefficients for proteins in the human protein interaction network showed moderate connectivity and clustering, with an average clustering coefficient of about 0.210.
-The degree distribution indicated a scale-free structure, typical for biological networks with a few highly connected hubs.
-Shortest path lengths between protein pairs in two datasets were compared using the Wilcoxon test, revealing no significant differences in connectivity (p-value ≈ 6.0999954580897106e-05).


