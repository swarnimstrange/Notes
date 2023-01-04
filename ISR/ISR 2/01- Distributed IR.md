# Distributed IR

- Distributed systems can also be seen as a MIMD parallel processor.
- with relatively slow inter-process communication.
- freedom to employ heterogenous collection of processors.

- Documents are always grouped into collections, either for administrative purposes or to combine related documents into a single source.
- Collections, therefore are useful in distributing data across servers and partitioning the computation.
- To build distributed IR system, we need to consider issues common to many distributed systems and algorithmic issues specific to information retrieval.
- it consists of a set of processes -:

  - Accepting Client request.
  - Distributed the requests to the server.
  - Collecting intermediate results from the servers.
  - Combining the intermediate results into final results.

- Document partitioning is mostly used

  - term partitioning imposes greater communication overhead.

- Document Clustering can be useful (to distribute docs by processors)
  - Index cluster and then search only the best ones
  - Or Use training queries, then similarity of the user query to those.

<img alt="" src="https://www.researchgate.net/profile/Sandhya-Pundhir/publication/276136272/figure/fig3/AS:667927342747650@1536257696062/Architecture-of-Distributed-Information-Retrieval.jpg">

# Algorithmic IR issues

- To distribute document accross the distributed search server we use Collection Partitioning.
- to select which server should recieve particular request we use Source selection.
- to combine the result from the different servers we use merging the result.
- A promising solution to didtributed retireval is meta serching, which dispatches a user's query to multiple sources.
- and gather the results into a single set.
