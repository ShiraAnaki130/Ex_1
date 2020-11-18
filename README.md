About the project:

The project is about a data structure called an undirectional weighted graph.
This data structure contains vertexes from the type of node_info and edges that connected between the vertexes.
Each edge has a weight that has to be a positive number.
The project consists of two classes, WGraph_DS and WGraph_Algo.
The class WGraph_DS implements the interface of weighted_graph and 
support several operations applicable on an undirectional weighted graph, such as: adding or removing a vertex or an edge from the graph,
returning a pointer to the collection of the vertexes, or the collection of the neighbors of a particular vertex, and also,the number of the
vertexes or the edges in the graph, and more.
The class Wgraph_Algo implements the interface of weighted_graph_algorithms and represents the algorithms which applicable on a undirectional weighted graph. 
The calss includes several algorithms such as:
1.copy- a deep copy of the graph.
2.init(graph)- init the graph on which this set of algorithms operates on.
3.getGraph()- returns the underlying graph of which this class works.
4.isConnected()- checking of the graph is a  one connected component.
5.double shortestPathDist(int src, int dest)- returns the smallest distsance between src and dest.
6.List<node_info> shortestPath(int src, int dest)- retrund the shortest path with the  lowest distance between src and dest.
7.save (file).
8.load(file).
attached herein two tests, one for every class
The WGraph_DSTest exaimine the integrity of the functions  that this class support  on, on basic cases, such as: checking if the number of vertexes or edges in the graph is correct, etc. 
Before every function, a small graph has been build , a graph with 9 vertexes and 19 edges with weights.
The WGraph_AlgoTest exaimine the integrity of the algorithms that this class support on, on both basic and extreme cases, 
and also builds a graph with a milion vertexes and ten milion edges, with the timeout of 4 seconds.
To use those tests, you need to have the version of JUnit5.
For using my codes, write in yout trminal the command - (your new folder's address) git clone https://github.com/ShiraAnaki130/Ex1.git
In addition, you need to have exlipse, becuse the programming language is Java.
Good Luck!
