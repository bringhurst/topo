topo v0.1
=========
A utility to query for topology information on a cluster.

Note: This utility is in the brainstorming stage of development.

Design Notes
------------
- Graphviz formatted output option.
- Answer: "What nodes are within 1 hop, 2 hops, etc?"
- Answer: "What switches are within 1 hop, 2 hops, etc?"
- Answer "what's a nice distribution of n supernodes?" via k-way partitioning.
- Support input of slurm topology.conf format files.
- Support multi-node max flow routing (via something like Ford–Fulkerson).
- Supporting routing between x node and y node based on z criteria.
