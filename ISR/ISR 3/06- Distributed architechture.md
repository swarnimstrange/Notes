# Distributed architechture

- there are several variations of crawler-indexer architechture. Harvest architechture is one of them. Harvest architechture is more efficient than crawler indexer architechture

- this architechture is based on distributed architechture for gathering and distributing data.

- there are several areas where Harvest architechture solves the problem of crawler indexer architechture-:

  - no coordination.
  - text duplication.
  - discarding info. causes web traffic
  - web servers load

- to solve above problems harvest architechture introduces -:

  - Gatherers
  - Brokers

- Gatherer's task is to collect and extract indexing information from one or more web servers.

- broker's task is to provide gathering mechanism and query interface to the gathered data.

- broker retrieves information from one or more gatherer and also other brokers and performs indexing incrementally.

- different improvement in web server loads and network traffic can be done using this type of architechture.

- it improves-:

  - replication
  - filtering
  - cordination (sharing)
  - web server load

- Disadvantages -:
  - coordination of several web servers
  - lacking flexibility
  - doesn't use gatherer and broker in cooperative manner
  - does not resolve cross paths
