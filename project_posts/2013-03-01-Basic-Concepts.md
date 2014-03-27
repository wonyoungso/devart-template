# Starting Point 

Korean creators tend to make small society. Almost everyone knows each other, influenced and 
work together. Creators participate same exhibition, interview same magazine, or graduate same school, 
maybe found a company or design studio for working together. This is a starting point.

![Concepts 01](../project_images/01_basic_concepts/concepts_01.png?raw=true "Concepts 01")

Checking precisely all exhibitions held in Korea and collaboration works of them, I think 
it can be drawn map of networks of Korean creators.

## Network Visualization Layout: Force-directed Layout 
It is the most frequently used layout engine for network visualization. 
Typically, spring-like attractive forces based on Hooke's law are used to attract pairs of endpoints of the graph's edges towards each other, while simultaneously repulsive forces like those of electrically charged particles based on Coulomb's law are used to separate all pairs of nodes. In equilibrium states for this system of forces, the edges tend to have uniform length (because of the spring forces), and nodes that are not connected by an edge tend to be drawn further apart (because of the electrical repulsion). Edge attraction and vertex repulsion forces may be defined using functions that are not based on the physical behavior of springs and particles; for instance, some force-directed systems use springs whose attractive force is logarithmic rather than linear... [Wikipedia: http://en.wikipedia.org/wiki/Force-directed_graph_drawing]

## Community Clustering
Creators tied with themselves usually forms community. A clustering algorithm called 
Speaker-listener Label Propagation(SLPA) is used for detecting communities. 

http://arxiv.org/pdf/1109.5720.pdf

![Concepts 02](../project_images/01_basic_concepts/concepts_02.png?raw=true "Concepts 02")