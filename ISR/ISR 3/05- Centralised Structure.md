# Centralised Structure

- Also called as crawler indexer architechture

- Crawlers are also called as robots, spiders, wanderers. it runs on local machine and sends request to remote web servers, It uses centralized fashion to answer query.

- there are two parts of crawler indexer architechture
    - the one which consists of User interface and query engine.
    - cawler model that extracts the URLs from websites and provide to crawler manager (control module). this module determines what link to visit next

- Crawler also adds the retrieved pages to page repository.

- indexer module extracts all words from each page and records the URL where each word occured. the result is very large.

- query engine is responsible for accepting and filling requests from user

- the engine heavily relies on indexes and sometime page repositiory

- ranking module has a task of sorting the results in a list in decreasing order of relevance. the top most wouuld be most relevent and so on..

- Disadvantages
    - difficult to gather data
    - saturated communication link
    - high loads on the servers
    - high volume of the data
    - no communication