# Source Selection

- Source selection is the process to determine the collection of documents that contains relevant document to the query, therefore should recieve query

- simple approach ->
    - in this type of method, we assume that every collection has same chance of being relevant so the query is broadcasted to every single collection. This is useful in the randomly partition collections or semantically overlapped collection.
    - in another method where documents are partitioned semantically meaningful, the previous method can be expensive. the collections can be ranked according to likelyhood of containing relevant document
    - another approach can be we can consider documents to be a large single document, index the collections and evaluate the query against the collections and produce a ranking. 