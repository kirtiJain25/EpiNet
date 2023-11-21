The EpiNet dataset is a comprehensive resource for studying the interplay between network properties and epidemic variables across networks of different sizes and types. 

EpiNet dataset and its components:

1. Network Properties (Features): The dataset includes five network properties as features namely Average Degree, Normalized Network Density, Degree Variance, Average Clustering Coefficient, and Average Shortest Path Length. These features encompass various characteristics of the networks, such as connectivity patterns, centrality measures, or structural attributes. These features are crucial for understanding the underlying network structure.

2. Epidemic Variables (Targets): There are three epidemic variables included as targets in the dataset. These variables represent aspects related to the spread or dynamics of an epidemic within the networks.
   a. Peak Day: the day when the cases are maximum 
   b. Peak Cases: maximum number of infected cases on a given day
   c. Span: period between the first and last infected cases

3. Network Generation: The dataset involves the generation of a substantial number of networks. This generation is stratified into three categories based on network size: small networks (N ∈ [20K-60K]), medium networks (N ∈ [60K-150K]), and large networks (N ∈ [150K-300K]). This stratification enables the exploration of the dataset across different scales of network sizes. The dataset consists of a substantial number of instances, with 15,000 small networks, 10,000 medium networks, and 10,000 large networks. This large number of instances provides a robust basis for statistical analysis and model training.

4. Network Families: The networks are categorized into three families: Random, Small-world, and Community-based networks. Different families may exhibit unique patterns of connectivity and organization, allowing researchers to explore how these structural differences impact the spread of epidemics.

5. Average Degrees: The average degrees of the generated networks fall within the range [6, 40]. This parameter is crucial in network science and represents the average number of connections each node has in the network. The decision to set average degrees within the range [6, 40], based on observations from real-life social networks in the SNAP library, adds a layer of realism to the generated networks. This reflects an attempt to mimic the characteristics of actual social networks, enhancing the practical applicability of the dataset.

6. Partitioning: The dataset is divided into three partitions (D-SN, D-MN, and D-LN) based on network sizes. This partitioning facilitates focused analysis and modeling for networks of specific sizes, allowing researchers to investigate the impact of network size on epidemic variables.

7. Research Community Use: The dataset is explicitly designed for use by the research community. This suggests an intention to encourage collaboration and exploration of the dataset by researchers working on epidemic modeling, network science, or related fields.

8. Regression Chain Model: The dataset is intended for use with a Regression Chain Model. This type of model considers a sequence of regression tasks, where the prediction for one variable depends on the predictions of the previous variables in the chain. This can be a powerful approach for capturing complex relationships in the data.



Cite this paper:

Jain, K., Bhatnagar, V., Kaur, S. (2023). Regression Chain Model for Predicting Epidemic Variables. In: Thomson, R., Al-khateeb, S., Burger, A., Park, P., A. Pyke, A. (eds) Social, Cultural, and Behavioral Modeling. SBP-BRiMS 2023. Lecture Notes in Computer Science, vol 14161. Springer, Cham. https://doi.org/10.1007/978-3-031-43129-6_28
