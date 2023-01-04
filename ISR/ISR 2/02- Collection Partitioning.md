# Collection Partitoning 

- The process of assigning documents to the search servers in a distributed IR system depends on a number of factors.

- in a system comprising 
    - independently administered
    - heterogenous seach servers
the distributed documents will be built and maintained independently.

- in case there's no central control of document partitioning procedure, the question of how to partition documents is essentially debatable. Each server is focused on indiviual areas so leads to semantic partitioning of documents into distributed documents, mostly happens in meta search engines.

- in case of centrally administered -:
    - first option is simple replication of all the documents across all the servers.
    - second option is random distribution of documents
    - final option is semantic partitioning of the documents -:
        - organized into semantically meaningful collection.
        - Or automatic categorization into subject specific collections.
