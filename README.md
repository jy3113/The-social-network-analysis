# The-social-network-analysis

Social networks analysis, the main body of a social network is usually a person. Each person is a node, and the relationship between people is an edge. The relationship has strength, direction, and nature. Its foundation is the graph theory of discrete mathematics. Then through some calculations to calculate the degree of aggregation, the average value or something. A higher level of data analysis can also be achieved through programming. In the research of social network analysis, what are the rules of spread of information in time, space and even geographic dimensions, and what are the key nodes? This has a greater degree of relevance to complex networks.

Therefore, the focus of social network analysis is on relationships and relationship patterns, and the methods and methods used are conceptually different from traditional statistical analysis and data processing methods.



# Degree Centrality.

Degree Centrality is the most direct metric to describe node Centrality in network analysis. The higher the node degree of a node is, the higher the degree centrality of the node is, and the more important the node is in the network. 

Betweeness centrality measures the extent to which a point is "in the middle" of other "point pairs" in the graph. If an actor is between several pairs of actors, then his degree is generally low. This relatively low degree point may play an important "intermediary" role and therefore be at the center of the network. According to this idea, the centrality of the point can be measured.

（1）Closeness

The approach to centrality requires consideration of the average length of the shortest path from each node to other nodes. In other words, for a node, the closer it is to other nodes, the higher its centrality. Generally speaking, a facility that needs to be used by as many people as possible has a relatively high degree of proximity to the center.

（2）Betweenness

Betweenness centrality refers to the number of times that a node acts as the shortest bridge between two other nodes. The higher the number of times a node acts as an "intermediary", the greater its intermediary centrality. If you want to consider the issue of standardization, you can divide the number of times that a node undertakes the shortest bridge by the number of all paths.



# Data wrangling

<img width="863" alt="g1" src="https://user-images.githubusercontent.com/71119359/121771449-09884c80-cba2-11eb-9bf3-6b00428e3870.png">

I used igraph and plot to make this graph, from which I found that most of the students are closely connected and become a network. Only a small part of the students are discrete and not very closely connected.


# Visualization

<img width="646" alt="Bestfriends" src="https://user-images.githubusercontent.com/71119359/121769957-13598200-cb99-11eb-91fa-bbd7a62d4f70.png">

According to the "Bestfrineds", I could see that students with #8 has the highest degree centrality for the best friends measure. 


<img width="507" alt="geton" src="https://user-images.githubusercontent.com/71119359/121769962-19e7f980-cb99-11eb-8781-a84dab86cf72.png">

According to the "geton", I could see that students with #11 has the highest degree centrality for get-on-with measure. 


<img width="622" alt="workwith" src="https://user-images.githubusercontent.com/71119359/121769982-2d936000-cb99-11eb-81dd-c477958701d1.png">

According to the "workwith", I could see that student with #6 has the highest degree centrality for work-with measure.



# Network structure

These metrics tell me that there have mutual connections between each other. 



# Summary

Through the analysis, it can be seen that student #8 has the highest score in the best friends network, so I think he is the most popular student, so he can hold some important positions in the class, such as monitor. I remember when I was in grade seven, there was a most popular boy in my class. He was the monitor of our class. All the students would obey his orders and he could manage our class in an orderly way.



# Future work

I think this is an emerging field at the intersection of disciplines. Involved in sociology, psychology, computer science. As mentioned above, graph theory is the foundation, and data analysis naturally requires a high level of mathematics, which is a very popular R language. Then computer operation, programming ability is naturally indispensable. In addition, due to the particularity and privacy of social networks and the limitations of commercial protection, the acquisition and sorting of good data sets for research in the field is also a relatively big challenge.



# Citation

Bakharia, A., & Dawson, S. (2011). SNAPP: A Bird’S-eye View of Temporal Participant Interaction. In Proceedings of the 1st International Conference on Learning Analytics and Knowledge (pp. 168–173). Banff, Alberta, Canada:ACM.

Hanneman, R. & Riddle, M. (2005). Introduction to Social Network Methods. Riverside, CA: University of California, Riverside
