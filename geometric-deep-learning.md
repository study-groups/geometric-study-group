
# Geometric and Topological Data Science


>Remarkably, the essence of deep learning is built from two simple algorithmic principles: first, the notion of representation or feature learning, whereby adapted, often hierarchical, features capture the appropriate notion of regularity for each task, and second, learning by local gradient-descent type methods, typically implemented as backpropagation.

> &mdash; [Geometric Deep Learning: Grids, Groups, Graphs, Geodesics, and Gauges](https://arxiv.org/abs/2104.13478)

Geometric data science is the study of graphs.
Topological data science is the study of shapes.

Ge
Topology involves invariants of shapes (Betti number, Euler characteristic).

## Topology

> I argue that set theory should not be based on membership, as in Zermelo-Frankel set theory, but rather on isomorphism-invariant structure.
—William Lawvere (Freitas, 2007)


<div style="padding-left:2em;">
    
    
| Geometric | Topology | Set Theory |
| ---      | ----     | --- | 
| local connections | global shape | X |
| Adjacency matrix | Betti number | X |
| Laplacian  | Euler | X |
    

</div>


# Sequential behavior involves incremental changes.

## Convolutional filters capture features in images

### Jan LeCun identified the problem with various sized inputs.


> While characters or short spoken words can be size-normalized and fed to a fixed size network more complex objects such as written or spoken words and sentences have inherently variable size. 
> 
> One way of handling such a composite object is to segment it heuristically into
> simpler objects that can be recognized individually (eg  characters, phonemes). However reliable segmentation heuristics do not exist for speech or cursive handwriting.

