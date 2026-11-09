- when we encounter artifacts, we are encountering the remnants of a single individual's experience of a single point in time in a single place.
-  "we do not find evidence of the roman empire, we find evidence of one person's experience of the roman empire" -SG (approximately)
  - calculating the average of a whole bunch of these individual experiences reconstructs the broader environment.

---

source,target
John Thompson, Mary Thompson,
married, Sarah Thompson
John Thompson, Robert Thompson
John Thompson, James Thompson
James Thompson, Alice Thompson
Mary Thompson, Sarah Thompson
Mary Thompson, Robert Thompson
Mary Thompson, James Thompson
Sarah Thompson, Robert Thompson
Sarah Thompson, James Thompson
Robert Thompson, James Thompson
William Hayes, Elizabeth Hayes

---

networks = **relationships** = equations/formulas 

"virality" -> communication and prevalence through/within a network.

citations are networks. you can make a whole map out of citation networks. i would love to do this with scholars of the Vietnam-American war... better yet i could make a relationship network of correspondents: what network/office they worked for, when they were in-country and where, who they knew. It would be interesting to see how their influence on eachother affected their photography, and being able to visualize that network over time would reveal how the course of the war reflected in their photos as well. 

- can be measured over time
- simulation is a foundational tool of archaeology
- context matters to how change manifests
    - complication vs complexity:
     - complicated: highly detailed, interrelated, and rigid in form and function. if one part fails, the whole system fails (ie. Challenger disaster)
     - complex: highly detailed, interrelated, flexible in form and function. changing one part changes the output. feedback changes output. (ie. traffic jams)
     - what about a black box technology? is that complicated or complex?
         - Dr. Graham: "maybe it depends on your response to the output." (approximately)
            -complexity/complication is related to personal experience.

- think about history (actual series/network of events which occurred in the past) as a piece of fabric without three dimensional form composed of artifacts and primary sources etc. If we run a whole bunch of simulations that act as the topography for the model, and then we drape the historical fabric over the many iterations of the simulated model, we can see where they line up, and then identify the network relations which led to the aligned results. 

- synchronicity: located in perception, not actuality... car blinkers don't choose to sync up. they sync because we, humans, are looking for synchronicity
- understanding what a network represents and keeping that in mind while you work on it is, as obvious as it sounds, fundamental to keeping your work focused and effective.
-----

network terminology:

- graph: mathematical structure describing a set of relationships.
- network: graph for which we have additional information about nodes and edges.
- nodes/vertices: 'things'/'individuals' acting in the network: people, objects, organizations, places, etc.
- edges: connections/relationships between node pairs
    - what you decide to use as your edge will change the appearance of the network; ie. event attendance vs. club membership vs. home address vs. familial relations. all of these are relationships between the same group of individuals but the networks look different.
- modality
    - unimodal: one kind of thing represented by nodes (students)
    - bimodal: many kinds of things represented by nodes (students & test scores)
- density: count of all possible relations/ties `((n*n)-n)/2`

- degree: number of connections per node
- path: sequence of nodes connected by edges from a given node to another
- centrality: measures importance/significance of a given node within a network
    - degree centrality: significance based on number of connections
    - betweenness centrality: significance based on the number of shortest paths passing through a node
    - closeness centrality: inverse of the sum of distances to all other nodes
- clustering coefficient: measures how interconnected a nodes neighbours are
- modularity/community detection: identifies clumps of nodes whose pattern of interconnections is more similar to eachother than to the rest of the graph
- small world: a graph that looks as if all of the connections are random, but there are "long distance" links that connect otherwise unconnected groups. it looks random, but behaves ordered. some argue that small world connections are the necessary element that gives rise to self-organization. **this is how feedback enters a network. the source of self-organizing criticality, providing a mechanism through which we can understand how society operates**
    - "Six Degrees of Kevin Bacon"
- weight:
    - unweighted: relationships are all equally significant
    - weighted: relationships are variously significant 

- "if we start discussing assemblages of objects as people we slip back into the old school of archaeology wherein we are also treating people like objects". -SG (approximately)

----

- base assumption for relationship pairs does not indicate directionality, which is why density calculation is divided by two. we don't necessarily know what the nature of the relationship is right away (power balance/imbalance), so we can only say that a relationship exists.
- Google PageRank: organized results based on number of times that page was linked to on other pages, and prioritizes the significance of these links based on how many times the sites linking the target site are linked on other sites, and so on.
- research has shown that humans naturally read network visualizations the same way we read text; starting with the top right corner and subconsciously prioritizing those nodes as the starting point/foundation of the network arbitrarily.

- jaccard index: (overlap of X and Y)/(total of all X and all Y combined)
- overlap does not add: if X shows up at site 1 and site 2, in the total it is only counted as one. we are dealing with types of objects/people/places(variables), not individual instances. a seriation graph like the one we were looking at in class (week7 powerpoint presentation) is indicating presence (1) or absence (0) of objects of a certain type, not how many there were. 
    - success threshold: .5? .75? you decide based on the specific needs of your experiment/research and then JUSTIFY THAT DECISION!!!!!

J(A,C)= 1/3= 0.33%

- Jaccard index score = weight/significance of relationship

- SG: geographical relationships revealed through networks of object assemblages which do not directly contain geographical information; the geographic significance of geography can be identified backward from assemblage (you have to be able to get to someone to use their materials).

------

- intervisibility, visibility matrix
    - visible/sightline (1), invislible/no sightline (0).
 
----

- one- or two-mode networks are very small, they get SO much bigger
- knowledge graphs: networks representing a large number of relationship types (works best with like 30-60 types)
- knowledge graphs exist in multidimensional space. because of the math used to turn the graph into multidimensional space, different 'kinds' of facts become easier to find than others. every fact represents a different direction through that space; you can measure distance and angle between facts to infer new information
- knowledge graphs allow for the comparison of patterns and factors them into its prioritization even when they don't appear explicitly in a dataset.

'SG','taught','HIST3000'
'CR','studied','HIST3000'
'HIST3000','taught_at','Carleton_University'
