<<<<<<< HEAD
# Code

[project_3_1_load_postgres.ipynb](project_3_1_load_postgres.ipynb)
[project_3_2_load_neo4j.ipynb](project_3_2_load_neo4j.ipynb)
[project_3_3_warehouse.ipynb](project_3_3_warehouse.ipynb)
[project_3_4_recommendation.ipynb](project_3_4_recommendation.ipynb)
[project_3_5_triangle_algo.ipynb](project_3_5_triangle_algo.ipynb)
[project_3_6_page_rank.ipynb](project_3_6_page_rank.ipynb)
[project_3_7_mongo_cosine_similarity.ipynb](project_3_7_mongo_cosine_similarity.ipynb)
=======
# Neo4j-Based Warehouse Optimization and Recommender System
*Dislaimer: The data used in the following project is for non-commercial educational and personal use.*

## Project Overview
In the Neo4j Community Detection project, my team and I applied graph analytics to demonstrate the real-world impact of graph databases on both warehouse efficiency and retail sales strategy. Leveraging the Northwind Traders sales database, we transformed transactional data into a product co-purchase graph, where each node represents a unique product and weighted edges represent the frequency of co-purchases between products.

We implemented a suite of graph algorithms from the Neo4j Graph Data Science (GDS) library—including Louvain Modularity, Triangle Count, and PageRank—to uncover structural insights within the product network. Louvain was used to detect tightly connected product communities, indicating items that are often purchased together. Triangle Count provided insight into the density and cohesiveness of these communities, while PageRank identified the most influential products in the ecosystem based on their connectivity and centrality.

These insights enabled two core applications:

- __Warehouse Optimization:__ By identifying product communities, we proposed an optimized shelf layout to minimize traversal time during batch picking. This layout considers physical storage constraints (i.e., keeping broader product types like dairy together) while keeping high-co-purchase items in close proximity, resulting in faster order fulfillment.

- __Recommender System:__ We developed a dynamic shopping cart recommender, which suggests the top two most frequently co-purchased products based on the current cart contents. This recommendation engine is designed to increase average order value by targeting natural cross-sell opportunities in real-time.

By modeling both the digital and physical aspects of the retail experience, this project highlights the practical value of community detection and network-based machine learning in driving operational efficiency and enhancing customer engagement in the specialty foods sector.

__Contributors:__ Hong Hu, Kevin Pradjinata

__Source:__ https://docs.yugabyte.com/preview/sample-data/northwind/
>>>>>>> d5f22d18367ce867a80d53e689d8cef703e3a9fd
