# NoSQL_Investigation

## Types

- Graph 
- Document 
- Key-value 
- Wide-columm 

## Advantages

- Denormalize data
  It is used to achieve performance and scalibility 
- Designed for incremental scalibility 
- Support data sharding
  NoSQL databases are designed to handle large amounts of data across distributed systems.
- New ways to query
  Each NoSQL database often uses its own API or query language

## Disadvantages
- Relax ACID contraints
  NoSQL use eventual consistency rather than strong consistency, which means that while the system will eventually
  converge to a consistent state, it may not be immediately consistent across all nodes.
- Data Duplication
  To achieve performance and scalibility, NoSQL uses denormalization (storing redundant data) this leads
  to data duplication and inconsistencies, which can become difficult to manage and update.
