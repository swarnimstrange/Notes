# MULTOS data model

- MULTOS stands for Multimedia Office server.
- it's multimedia document server that supports advanced document retrieval capabilities.
- based on client-server architechture.
- supports diffr type sof servers eg. current, dynamic and archieve servers.
- diffr servers have different storage capacity and retrieval speed.
- supports filing and retrieval of multimedia objects on doc. collections, doc. types, doc. attribute, doc. text and doc. images.
- allows -:
  - repr. of high level concepts in doc.
  -  grouping of doc. into classes similar to it.
  -  structure and conditions on free text

- Document description of MULTOS-:
  - Logical Str -: determines arrangement of logical contents. for eg. title, chapter, section etc.
  - Layout Str -: deals with layout of the document. for eg. pages, frames etc.
  - Conceptual Str -: allows semantic oriented description of the document. opposite to syntax oriented (seen above)

- To deal with image data MULTOS provides sophisticated approach -:
  - image ananlysis is performed on the basis of two phases -:
    - Low Level Image ananlysis -: basic objects composing a image and their positions are identified.
    - High Level Image ananlysis -: images are decribed in terms of objects recognised, possibility values and classes to which they belong.
  - indexes are constructed -:
    - Object Index -: for each object a list is maintained
    - Cluster index -: for each image class a list of pairs MF, IMH is maintained 
