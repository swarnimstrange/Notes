# Ranking

- Ranking document by relevance
- without using text inside it only by indexes.
- Several ranking algorithms are -:

  - Boolean
  - Vector
  - Most- Cited

- Boolean and Vector spread are extended from boolean and vector model, they include pages pointed to by a page in the answer.

- while most-cited based on the terms in a page having a link from other pages.

- some of the algorithm uses hyperlink information.

- It takes a set of web pages i.e answer to the query and then ranks them depending on the connection of pages with each other

- a page having many outgoing link is called hub

- a page having many incoming called athourity

- problems -:
  - does not work with non-exixtent, repeated or automatically generated links.
  - topic of the result can be diffused (solution -: analyze and give score to each page)
