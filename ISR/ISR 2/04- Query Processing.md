# Query Processing

- Proceeds as follows

  - Select collections to search.
  - distribute query to selected collections.
  - Evaluate the query at distributed collections in parallel.
  - Combine results from distributed collections into final results.

- Step 1 maybe eliminated if the query is already broadcated to every collection.
- Otherwise, One of the selection algorithms is used and the query is distributed to selected collections.
- Each of the participating search server then evaluates the query according to it's local search algorithm and the results are merged.

- There are number of scenarious used for merging the results.

  - if the query is boolean and search results return boolean then return union of search results.
  - if the query involves free text ranking, several techniques used -:
    - using round robin interleaving -for example -:
      - 1st doc from 1st list
      - 1st doc from 2nd list
      - 1st doc from nth list
        (n+1) - 2nd doc from 1st list....
        likely to produce poor quality results from irrelevant collections.

- By weighing document scores based on their collection similarity computed during the source selection step.
- the weight for a collection can be computed as -:

  - w = 1 + |C| . (s - s') / s'
  - C is collections searched, s is collection score, s' is mean of collection score.

- more accurate technique for merging ranked result list to use global term statistics.
- if the collections have been indexed for source selection, then index will contain global term statistics across all the distributes collections.
