# R-Tree

- Represents a spatial object by it's minimum bounding rectangle (MBR).
- parent nodes are formed by grouping rectangles.
- and parent nodes are recusively grouped to make granparent nodes.
- Eventually a tree is formed.
- the MBR of parents contains MBR of it's children.
- MBR are allowed to overlap.
- A range query specifies a region of interest requiring all data regions that interests it.