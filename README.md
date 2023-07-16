# EpiNet
Dataset:
1. A rich dataset called EpiNet consists of five network properties (features) and three epidemic variables (targets) to Regression Chain Model for Predicting Epidemic Variables for networks with varying sizes (N) and average degrees.
2. We generate 15K small networks (N ∈ [20K-60K]), 10K medium networks (N ∈ [60K-150K]), and 10K large networks (N ∈ [150K-300K]), with an equal number of instances belonging to three network families - Random, Small-world, and Community-based networks. We set average degrees for all generated networks in the range [6, 40], as observed in real-life social networks from the SNAP library.
3. Based on the network sizes, we split EpiNet into  three partitions, corresponding to small networks (D-SN), medium networks (D-MN), and large networks (D-LN). The dataset can be used for further investigation by the research community.

Network Properties:
1. Average Degree
2. Normalized Density
3. Degree Variance
4. Average Clustering Coefficient
5. Average Shortest Path Length

Epidemic Variables:
1. Peak Day: the day when the cases are maximum 
2. Peak Cases: maximum number of infected cases on a given day
3. Span: time period between the first and last infected cases
