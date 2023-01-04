# Steps in data retrieval:

- query specification -:

  - In this step, user specifies query, there should be proper interface for putting queries
  - Fuzzy predicates. (eg. find images similar to cat)
  - Content based predicates. (find Multimedia Objects (MO) containing apples)
  - Conventional Predicate (find red images)
  - Structural predicate (find MO containg video)

- query processing and optimization -:

  - just like traditional IR, MIR also deal with queries -:
    - query is parsed
    - compiled
    - optimized
      using best evaluation plan to generate internal representation.
  - Fuzzy predicate, content based predicate, structure predicate make it complex to process.
  - very little work is done on query processing strategy in MIR

- query answer -;

  - the retrieved object are returned to the user in decreasing order of relevance.

- query iteration -:
  - in TIR once user gets a response query process stops
  - but in MIR until the user is satisfies the query process keps on iterating.