# ANN_A-
To create an ANN to find the fastest path from start to destination.

# TO-DO
1) Develop node 
  a) Node needs to have a list for parents and children
  b) Node needs links between both
  c) Links should have weights
  d) Node should have a ToString to see parents and children
2) Node Tree
  a) Be able to use default (see help.png)
  b) Be able to create my own node tree
  c) Save/Load node trees
  d) ToString total path
3) ANN that can random gen a path from start to finish in tree
  a) Given distance to each node
  b) Blank ANN gets random ANN
  c) ANN has a "total value" variable that sums up distance and work
4) ANN can improve upon path
  a) Future ANNs can provide modifications on a previous ANN
  b) ANNs compare total value, if successful replace the "Best" ANN with themselves
5) Displays generations in a neat format
  a) Table style
  b) ANN Gen, Value, Path
6) (LONG TERM) GUI for visualizing the tree
  a) Be able to create a tree in GUI
  b) Drag-drop nodes (or perhaps just a text box)
  c) Can be resized for larger nodes
  d) Node trees start from bottom and work upwards (or vice versa)
  e) Nodes have their labels on them (if they fit)
7) (LONG TERM) GUI for visualizing a specific generation of ANN
  a) Be able to type command or select gen
  b) Path links are highlighted/changed color
  c) Nodes in path are highlighted/changed color
8) (LONG TERM) GUI for visualizing ANN results, with ability to select ANN to view
  a) Different windows for the different things
  b) Window for results in table form
  c) Scroll wheel for table
  d) Clicking an ANN in table allows you to see path in Tree
9) (LONG TERM) GUI for watching ANN develop best path as a timelapse
  a) Each second runs 1-5 gens at a time
  b) Able to change the rate of gen/sec
  c) Able to pause
  d) Able to select start gen
