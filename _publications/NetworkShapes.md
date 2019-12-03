---
title: "Representing Networks with 3D Shapes."
collection: publications
permalink: /publication/NetworkShapes
excerpt: 'A method to represent **any** network with a 3D shape. Shapes capture various network properties: isomorphic graphs = same shapes, different graphs (random graphs, dense graphs, etc.) have different shapes. '
date: 2018-11-18
venue: 'ICDM (Acceptance Rate 8.86%)'
paperurl: 'https://shengminjin.github.io/files/NetworkShapes.pdf'
citation: 'Jin, Shengmin, and Reza Zafarani. "Representing Networks with 3D Shapes." 2018 IEEE International Conference on Data Mining (ICDM). IEEE, 2018.'
---

[Download paper here](https://shengminjin.github.io/files/NetworkShapes.pdf)

Abstract:
======
There has been a surge of interest in machine learning in graphs, as graphs and networks are ubiquitous across the globe and within science and engineering: road networks, power grids, protein-protein interaction networks, scientific collaboration networks, social networks, to name a few. Recent machine learning research has focused on efficient and effective ways to represent graph structure. Existing graph representation methods such as network embedding techniques learn to map a node (or a graph) to a vector in a low-dimensional vector space. However, the mapped values are often difficult to interpret, lacking information on the structure of the network or its subgraphs. Instead of using a low-dimensional vector to represent a graph, we propose to represent a network with a 3-dimensional shape: the network shape. We introduce the first network shape, a Kronecker hull, which represents a network as a 3D convex polyhedron using stochastic Kronecker graphs. We present a linear time algorithm to build Kronecker hulls. Network shapes provide a compact representation of networks that is easy to visualize and interpret. They captures various  properties  of  not  only  the  network,  but  also  its subgraphs. For instance, they can provide the distribution of subgraphs within a network, e.g., what proportion of subgraphs are structurally similar to the whole network? Using experiments on real-world networks, we show how network shapes can be used in various applications, from computing similarity between two graphs (using the overlap between network shapes of two networks) to graph compression, where a graph with millions of nodes can be represented with a convex hull with less than 40 boundary points.

Recommended citation: Shengmin Jin and Reza Zafarani. "Representing Networks with 3D Shapes." 2018 IEEE International Conference on Data Mining (ICDM). IEEE, 2018.
