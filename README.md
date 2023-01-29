# Queens-Campus-RL-Pathfinding
Group Project for CISC 474 - Reinforcement Learning

In this .ipynb file you will find a reinforcement learning agent who can navigate between locations on campus.

The data is pulled from OpenStreetMaps.
We use a python wrapper language to do our Overpass Query Language calls. It pulls in nodes and ways between nodes from OSM.
We then parse the result into a networkx graph that removes nodes and edges that do not connect to the system. This helped move past the problem where the agent would get stuck in a part of the system that does not connect to anything.

The agent uses Q-Learning to find the optimal path between two (set) points.
