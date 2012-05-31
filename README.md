pHomomorphism
=============
@author Alok Dhamanaskar <alokdhamanaskar@gmail.com>
@see    LICENSE (MIT style license file).


The package is written independently, to be used for calculating the overlap between XML inputs and outputs of Web services in the project: Service Suggestion Engine. The Ontologically annotated i/o of Web services to match are converted to Graphs (DAGs) and then the overlap between them is calculate using the algorithm in this package.
(For more info on SSE: http://mango.ctegd.uga.edu/jkissingLab/SWS/sse.html)

This package however can be independently used to calculate similarity between two Graphs. 
For this it uses p-Homomorphism algorithms proposed in the paper, Graph homomorphism revisited for graph matching (http://dl.acm.org/citation.cfm?id=1920986)
pHomomorphism is variant of sub-graph homomorphism that is less strict than traditional Homomorphism.

For examples to run see Test.java
To See a Step by Step calculation of the algorithm set debug = true in MaxCardinality.java 
Refer to JavaDocs for additional Details.



