# osmaas.github.io
Street Network Analysis
OSMnx is a Python package that allows users to download and analyze street networks and other infrastructure data from OpenStreetMap. It was developed by Geoff Boeing, an urban planning researcher at the University of Southern California.

With OSMnx, users can easily download and visualize street networks from anywhere in the world at any scale, from small neighborhoods to entire cities. It can also be used to calculate various metrics related to street networks, such as centrality, connectivity, and accessibility.

In addition to street networks, OSMnx can also download and analyze other types of infrastructure data from OpenStreetMap, such as buildings, parks, and waterways. Overall, OSMnx is a powerful tool for urban planners, geographers, and researchers who are interested in understanding and analyzing urban environments.

In this project we have used the capabilities of OSMnx to identify the various road networks in the city. We have plotted driveable road network for cities like Halmstad, Sweden; Varberg, Sweden; Toronto, Canada and Helsinki, Finland.

OSMnx also have capabilities to identify various features in an area. In OSMnx, tags are used to specify the types of features that are downloaded and analyzed from OpenStreetMap (OSM). Tags are key-value pairs that describe the characteristics of a feature, such as its name, type, and attributes. For example, we can see all features in an Open Street map tagged as buildings or parks in a city. In addition to basic tags, OSMnx provides a wide range of other tags that can be used to download and analyze different types of features in OSM, such as bike lanes, bus stops, and pedestrian crossings.

Here we have plotted various amenities around the city like hospitals, bus stops, parking spots, electric vehicle charging stations, bicycle rental places and bicycle parking spots.

In OSMnx, street centrality refers to a set of metrics that measure the importance of each street segment within a street network. Street centrality can be used to identify the most important or central streets within a network, which can be useful for a variety of urban planning and transportation applications.
OSMnx provides several different centrality measures that can be calculated for a street network, including Degree Centrality, Eigenvector Centrality, Closeness Centrality and Betweenness Centrality. 

Degree centrality is a metric used in network analysis that measures the importance of a street segment based on the number of edges that it is connected to. In OSMnx, degree centrality is used to measure the importance of each street segment in terms of its connectivity within the street network. In practical terms, degree centrality can be used to identify important streets for accessibility and mobility within a city. For example, a street with high degree centrality may be an important throughway for vehicular traffic, or a popular pedestrian or bicycle route connecting different parts of the city.

Eigenvector centrality is a metric used in network analysis that measures the importance of a street segment based on the connectivity of its neighboring nodes. In OSMnx, eigenvector centrality is used to measure the importance of each street segment based on the importance of the streets that it is connected to. In practical terms, eigenvector centrality can be used to identify important streets for connectivity and mobility within a city, particularly in terms of their role as connectors between different parts of the network. For example, a street with high eigenvector centrality may be an important arterial road that connects several neighborhoods or commercial areas.

Closeness centrality is a metric used in network analysis that measures how easily a street segment can be reached from all other nodes in the network. In OSMnx, closeness centrality is used to measure the importance of each street segment in terms of its accessibility and mobility within the street network. In practical terms, closeness centrality can be used to identify important streets for accessibility and mobility within a city. For example, a street with high closeness centrality may be an important corridor for public transportation or an important pedestrian route between different parts of the city.

Betweenness centrality is a metric used in network analysis that measures the importance of a street segment for the flow of information or resources between other nodes in the network. In OSMnx, betweenness centrality is used to measure the importance of each street segment in terms of its ability to connect different parts of the street network. In practical terms, betweenness centrality can be used to identify important streets for connectivity and mobility within a city. For example, a street with high betweenness centrality may be an important route for emergency vehicles, or an important pedestrian or bicycle route connecting different neighborhoods.
To visualize the results a dashboard has been published in the following path.
![image](https://github.com/erajabi/osmaas/assets/2185586/9ffacf66-034e-4c34-9f1a-cedcd16cdc24)
