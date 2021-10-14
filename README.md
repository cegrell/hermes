# trading-manager

## Requirements
1. Connectivity to multiple exchanges
2. Merging market data fr multiple sources
3. Multiple investment strategies
4. Performance - low 5-20 microseconds, measured fr ingress to egress
5. Consistency - Perform the same with 10K mps as with 100K mps
6. Consistency - 1mic std deviation at 99th perc
7. Reliability - message reliability, no losing orders etc
8. Reliability - Survive process and machine failure
9. Complexity - simplicity key

## Key themes
- In-memory computating techniques
- Data gravity
- clear ownership of data
- pubsub
- data in motion 

## Priority


## Project roadmap

1. Data feed manager
2. Constitency 


## Product roadmap
1. Multiple venue
- one feed per venue 

2. Data ingestion


3. Aggregator -> Order book
- Sorting


Order Router 
1. Client in,
2. Market out,
3. Market in,
4. client out,

