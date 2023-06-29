# Analysis-of-Complex-Networks


## Abstract

Complex Networks are networks that are connected
in different ways with a set of nodes. In this project, we
are going to determine some structural and statistical properties of various complex networks and form a comparison
between them in order to understand the characteristics of
the network. The best way to do this is by comparing it
with random graphs. Random graphs are graphs with properties like the number of vertices, edges, and connections between them that are determined in some random way. The
properties we will be exploring are - checking if a network
exhibits small world property, and scale-free property and
analyzing various centrality measures (like Degree Centrality, Betweenness Centrality, Closeness Centrality, Eigenvector Centrality), modularity, and finding the communities in
the networks. We will be calculating all these properties for
each network and will finally form a comparative analysis
with the properties of all networks.

## Data

Five different datasets are used for this analysis.
The datasets used include Word adjacencies, Political blogs,
Coauthorships in network science, Dolphin social network,
and Zachary’s karate club datasets. These datasets are
collected from the pool of networks made available online.
The Nodes of the dolphins dataset represent the dolphins and
the edges represent their association. In the Karate dataset,
the node represents the members of the karate club while
the edges represent the links between pairs of members
who interacted outside the club. Nodes of NetScience data
map the Researchers and edges map the co-authorship of
these researchers. Word data gives us information with
words as nodes and edges as their association. Nodes in
political blogs data represent Political blogs before the 2004
election and edges represent the link between the blogs.

## Analysis

Average Path Length, Small World Property, Clustering Coefficient, Scale Free Property, Centrality Measures, Modularity, Communities.

## Results

In this project, I analyzed five complex networks and their corresponding random networks. I examined properties such as diameter, small-world property, scale-free property, degree centrality, betweenness centrality, closeness centrality, eigenvector centrality, modularity, and community detection. Using Python, I determined that all the complex networks exhibited the small-world property, with increased diameter resulting in larger mean distances. Real complex networks had significantly higher clustering coefficients compared to random graphs, indicating a modular structure. Three out of the five networks displayed the scale-free property, with degree distributions following a power-law in the Co-authorship Network of Scientists Dataset and the Karate Dataset. Centrality measures revealed important nodes for connectivity and information flow in each network, such as 'little' in the word adjacencies dataset, 'Grin' in the dolphin dataset, 'SN100' in the word adjacencies dataset, '34' in the karate dataset, and 'BARABASI,A' in the co-authorship network of scientists dataset. Community detection identified distinct communities in the networks, such as nouns and adjectives in the word adjacencies dataset, age groups in the dolphin dataset, divisions within the karate club, research areas in the co-authorship network of scientists dataset, and liberal and conservative supporters in the political blogs dataset. Complex graphs showed higher modularity values and better-defined community structures compared to random graphs.

