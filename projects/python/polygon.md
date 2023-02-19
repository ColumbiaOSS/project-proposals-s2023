## Project Proposal - Polygon Quantization Algorithm
Project repo: [link](https://github.com/r1p71d3/polysplit)

#### Preface
Map quantization is the procedure of dividing a continuous map into a number of discrete regions. The simplest approach that has been used for hundreds of years is to overlap the map with a square grid. However, this approach ignores the geographical features of the map, making it suboptimal for certain applications. With this project, I would like to propose a novel algorithm that organically divides any given map into regions based on the relative travel time between different areas.

#### The algorithm
In its simple form, the proposed algorithm could be applied to a map (a polygon) with intraversible obstacles (holes). It works in 2 stages. In the first stage, the map is overlayed with a fine grid of $N$ points. Then, we calculate the shortest path (around the obstacles) betweeen every pair of points and construct the $N \times N$ distance matrix. In the second stage, we apply the k-medoids algorithm to the set of points, using the matrix from stage I as a distance function, and retrieve a set of $M$ centers. Finally, we construct a Voronoi graph around the centers, creating the regions.

#### Optimization and other ideas
Constructing a distance matrix could pose some problems, as it will involve running the visibility search algorithm $O(N^2)$ times, which could take a very very long time for high $N$ values. Therefore, instead of creating a full distance matrix, it will likely be necessary to modify k-medoids to run distance computations in real time. Additionally, making the algorithm applicable to real geospatial data will involve simplifying any given map to a polygon with holes, which is a whole separate project. Yet, even in the basic form, the algorithm could be already useful for certain applications, for example, creating realistic pathfinding for AI agents in games.
