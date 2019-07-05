# HORUS_RandD
Storage repo for research and design documents


__Requirements__

1) Based on sorting a collection of 3 x 10^9 items, our system should outperform standard systems (Apples-to-Oranges) relative to cost of production.
  - Hypothetical Example: $2000 gaming PC @ 200 sorts/min = $10 sort/min; so, $180 array should sort > 18 sort/min
2) Should fit in size constraint equal to a standard shoebox and be relatively portable.
3) Software package on command board should provide API's including a variety of sort and query types.
  - Each request should take the following parameters: sort/query type, predicate, collection
4) Project should be validated with an out of the box kitura backend and iOS app client, in end to end Swift
