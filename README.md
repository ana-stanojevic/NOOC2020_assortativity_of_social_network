# Project for Networks Out Of Controle course at EPFL

This dataset is comprised of messages sent on an online social network at the University of California, Irvine [Link](https://snap.stanford.edu/data/CollegeMsg.html). Graph is made out of this data such that an edge (u, v) means that user u sent a message to user v.

Firstly, we plot the graph to observe the structure. It appears that there are a lot of periferal nodes that are connected to hubs and not among themselves. 

Furthermore, we use 3 different assortativity metrics for directed graph to assess the assortativity of the network. The metrics' are <img src="http://www.sciweavers.org/tex2img.php?eq=r_%7Bd%7D%20&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0" align="center" border="0" alt="r_{d} " width="21" height="15" /> , $r_in$ and $r_out$. Their deffintions can be found in *Assortative Mixing in Directed Biological Networks, Mahendra Piraveenan 1, Mikhail Prokopenko, Albert Zomaya, 2012*.

The 3 metrics are derived for directed graphs and in the paper they are use for different types of biological networks. Here, we use them for a social network. Usually, for social networks we have that they are assortative, i.e. the metrics are positive. In this case we see that according to this metrics the network is slightly disassortative, i.e. we obtain negative values. This is not surprising as this is a special type of social network (college network). 

This network is likely mostly used for communication between a lot of students on one side and a few professors and TAs on the other side. Meaning that hubs are connected to the nodes with low degree. This doesn't mean that students don't use the channel to communicate amoung themselves or similarly that professors don't communciated among themselves, it only means that the majority of communication is on relation a student-professor.    



