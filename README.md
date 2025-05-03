# mutual_friend_detection
Introduction 
In today’s digital world, social networks have become a fundamental part of how people 
connect, interact, and build relationships. As platforms like Facebook, Twitter, and 
Instagram continue to grow, understanding the structure and behavior of these networks 
becomes increasingly important. This project aims to analyze a portion of a real-world 
social network using principles of graph theory, with a specific focus on mutual friends and 
friend recommendations. 
The core idea behind the project is simple yet powerful: 
If two users have many friends in common, there is a high likelihood they might know each 
other or be recommended as friends. 
Using the Facebook Ego-Network Dataset from Stanford SNAP, we explore the ego-network 
of a single user and study how the users around them are connected. Each person in the 
network is represented as a node, and each friendship is represented as an edge connecting 
two nodes. We treat this data as an undirected simple graph. 
This project consists of the following key components: 
Analyzing the structure of the network, including the number of users and connections. 
Visualizing a meaningful part of the network to understand user clusters and relationships. 
Identifying mutual friends between any two users in the graph using set-based logic. 
Recommending friends to a user based on the number of shared friends (mutual friends). 
Analyzing the overall distribution of friendships across the network using a degree 
histogram. 
Introducing an advanced feature to find the single user who shares the most mutual friends 
with a given user. 
The goal is not just to write code, but to simulate a real-world system like the one used in 
social media platforms. Through this analysis, we demonstrate how core concepts from 
Discrete Mathematics and Graph Theory can be applied to a real-life social context in a 
simple, interpretable, and visually effective way.
