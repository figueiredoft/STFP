# instancesSTFP
Instances - Sociotechnical Formation Team Problem (STFP)

The instances are separated into 6 groups, by the cardinality of the vertices of the graph. Each group is denominad by the vertex cardinality of the graph. Example: a folder named 20 has 24 instances with sociometric graphs with vertex cardinality equal to 20. Each instance is composed of 4 files:


configuration.txt (team requirements matrix T with size sxt -- total number of teams x  total number of skills -- with elements denoted as tjk that specifies how many individuals with the same skill k a are needed for each particular team j)

demand.txt (demand matrix D with with size t --  total number of teams  -- with elements denoted as dj that specifies how many teams with configuration of the type Tj are required)

graph.txt (sociometric matrix K with elements denoted as kuv. This is a symmetrical square matrix with size n×n -- total number of individuals -- the lower the value of kuv , the higher the degree of the mutual affinity between u and v) 

skills.txt (skills/individuals matrix S with size nxs -- total number of individuals x total number of skills -- with elements denoted as Suk that specifies if the individual u have the skill k)

