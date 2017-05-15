# ANN_A-
To create an ANN to find the fastest path from start to destination.

# TO-DO
1) Develop node <br />
  a) Node needs to have a list for children <br />
  b) Node needs links between both <br />
  c) Links should have weights <br />
  d) Node should have a ToString to see parents and children <br />
2) Node Tree <br />
  a) Be able to use default (see help.png) <br />
  b) Be able to create my own node tree <br />
  c) Save/Load node trees <br />
  d) ToString total path <br />
3) ANN that can random gen a path from start to finish in tree <br />
  a) Given distance to each node <br />
  b) Blank ANN gets random ANN <br />
  c) ANN has a "total value" variable that sums up distance and work <br />
4) ANN can improve upon path <br />
  a) Future ANNs can provide modifications on a previous ANN <br />
  b) ANNs compare total value, if successful replace the "Best" ANN with themselves <br />
5) Displays generations in a neat format <br />
  a) Table style <br />
  b) ANN Gen, Value, Path <br />
6) (LONG TERM) GUI for visualizing the tree <br />
  a) Be able to create a tree in GUI <br />
  b) Drag-drop nodes (or perhaps just a text box) <br />
  c) Can be resized for larger nodes <br />
  d) Node trees start from bottom and work upwards (or vice versa) <br />
  e) Nodes have their labels on them (if they fit) <br />
7) (LONG TERM) GUI for visualizing a specific generation of ANN <br />
  a) Be able to type command or select gen <br />
  b) Path links are highlighted/changed color <br />
  c) Nodes in path are highlighted/changed color <br />
8) (LONG TERM) GUI for visualizing ANN results, with ability to select ANN to view <br />
  a) Different windows for the different things <br />
  b) Window for results in table form <br />
  c) Scroll wheel for table <br />
  d) Clicking an ANN in table allows you to see path in Tree <br />
9) (LONG TERM) GUI for watching ANN develop best path as a timelapse <br />
  a) Each second runs 1-5 gens at a time <br />
  b) Able to change the rate of gen/sec <br />
  c) Able to pause <br />
  d) Able to select start gen <br />
