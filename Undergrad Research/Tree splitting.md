• Tree splitting One method currently in use for creating new partitions is drawing a spanning tree for
the dual graph and deleting k − 1 edges to get a k partition [4, 11]. Since we want the partitions to be
population balanced the sets of edges that can be cut is much smaller than the n−1
k−1


naive options.
This procedures leads to both computational and theoretical questions, including:

- What is the best algorithm for finding a cuttable edge / all cuttable edges.
- What are the expected properties of uniform sampling from all permissible cuts on a fixed tree
(how different are they?)
- Can we bound the # possible trees given a fixed ε (both graphs and and geographic)
- How different are the distributions between deleting k edges at once vs. deleting a single edge
and redrawing a tree.
- What proportion of trees are splittable?
- How long do you have to wait to find a splittable tree when cycle–basis walking?
- How bad is the “best” cut, even if not permissible?
- What is the distribution of best cuts over trees?