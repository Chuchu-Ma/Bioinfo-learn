# Introduction
Graph Neural Networks (GNNs)

Node: entities (single cell or gene)

Edges: connections (proximity or functional correlation)

Adjacency Matrix: tell who is connected to whom （like a table）

Message Passing: look at neighbors, grabs info

Aggregation: combines info into one single update

<img width="3967" height="726" alt="image" src="https://github.com/user-attachments/assets/98502f93-0948-4e2b-a688-df91832ed182" />

undirected: no notion of source or destination nodes, flows both directions

directed: 𝑣𝑑𝑠𝑡 to 𝑣𝑠𝑟𝑐

# Image as graph: column x row x 3 (3: RGB)

Adjacency Matrix: 

<img width="640" height="480" alt="image" src="https://github.com/user-attachments/assets/d038bf58-bccb-4511-b245-1c9772c3a950" />

row: source, all nodes

column: destination, all nodes

if connect: 1; if not: 0


# source
https://distill.pub/2021/gnn-intro/









