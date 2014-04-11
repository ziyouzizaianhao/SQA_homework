GuoZilong(13126077) From Group C

What are the basic concepts of DDG?

DDG: data dependency graph

In DDGs, each node represents the definition of a data item, such as a variable, a constant, and a compound data structure. The links in DDGs represent the D-U relation, or ¡°is used by¡±. That is, if we have a link from A to B, we interpret it as that the data defined in A is used to define the data in B.

This analysis of chains of D-U relations used in defining later data items can be carried out to identify the definitions of those earlier items, until we resolve all the definitions. This backward chaining process, starting from the computational result back to all its input and constants represents the model construction process.