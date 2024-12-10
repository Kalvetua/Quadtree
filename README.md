Quadtrees are structures of data that utilize recursion to partition a two-dimensional space into four equal regions. On a foundational level, a quadtree is made up of four quadrants, or nodes, each which are able to store a certain amount of data. Once the limit amount in a quadrant has been satisfied, it subdivides and creates more quadrants that are also able to store data- in other words, the tree has expanded and grown deeper. As more data is added to the quadtree, it will continue to recursively subdivide into quadrants of quadrants of quadrants...

When data is stored into a list, it can become expensive to iterate through the list each time an element is required, however that expense can be siginificantly reduced through the use of more efficient methods, such as quadtrees. Quadtrees enable efficient look-up of data through its spacial partitioning system, since it is structured in such a way that not all objects in a scenario have to undergo inspection. Instead, through positional data- such as coordinates, it is possible to go straight to the quadrant- and then to the subquadrants that contain the sought after data. Thus quadtrees are both more efficient with resources and also consumes less time to find the specified data.
