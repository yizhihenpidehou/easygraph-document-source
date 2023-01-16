Graph Classes
=============

EasyGraph provides four types of graph classes, `Graph`、 `DiGraph`、 `MultiGraph`、 `MultiDiGraph`、'HyperGraph'

Which graph class should I use?
===============================

+----------------+------------+--------------------+------------------------+
| EasyGraph Class | Type       | Self-loops allowed | Parallel edges allowed |
+================+============+====================+========================+
| Graph          | undirected | Yes                | No                     |
+----------------+------------+--------------------+------------------------+
| DiGraph        | directed   | Yes                | No                     |
+----------------+------------+--------------------+------------------------+
| MultiGraph     | undirected | Yes                | Yes                    |
+----------------+------------+--------------------+------------------------+
| MultiDiGraph   | directed   | Yes                | Yes                    |
+----------------+------------+--------------------+------------------------+
| HyperGraph     | undirected | Yes                | No                     |
+----------------+------------+--------------------+------------------------+
.. toctree::
    :maxdepth: 2
    :caption: Contents

    classes/graph.rst
    classes/digraph.rst
    classes/MultiDiGraph.rst
    classes/MultiGraph.rst
    classes/hypergraph.rst

    
