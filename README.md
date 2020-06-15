# Project for Networks Out Of Controle course at EPFL

The CollegeMsg dataset is comprised of messages sent on an online social network at the University of California, Irvine - [link](https://snap.stanford.edu/data/CollegeMsg.html). Graph is made out of this data such that an edge (u, v) means that user u sent a message to user v.

Firstly, we plot the graph to observe the structure. It appears that there are a lot of peripheral nodes that are connected to hubs and not among themselves. 

Furthermore, we use 3 different assortativity metrics for directed graph to assess the assortativity of the network. The metrics' are <img src="https://latex.codecogs.com/gif.latex?\dpi{400}r_d" width="16" height="11"/>, <img src="https://latex.codecogs.com/gif.latex?\dpi{400}r_{in}" width="20" height="11"/> and <img src="https://latex.codecogs.com/gif.latex?\dpi{400}r_{out}" width="23" height="11"/>. Their defintions can be found in *Assortative Mixing in Directed Biological Networks, Mahendra Piraveenan 1, Mikhail Prokopenko, Albert Zomaya, 2012*.

The 3 metrics are derived for directed graphs. In the mentioned paper, they are used for different types of biological networks. Here, we use them for a social network. Social networks are usually assortative, however, here we see that according to these metrics the network is slightly disassortative, i.e. we obtain negative values. This is not surprising as this is a special type of social network (college network). 

This communication is likely mostly happening between a lot of students on one side and a few professors and TAs on the other side. Meaning that hubs are connected to the nodes with low degree. This doesn't mean that students don't use the channel to communicate among themselves or similarly that professors don't communciated among themselves, it only means that the majority of communication is on relation a student-professor.    

By using more advanced metrics such as local assortativity we could be able to understand the functionalities of different nodes separately and therefore get more detailed information of the graph.  



