
# Geometric and Topological Data Science

Graph theory involves **connections** which captures local structure and information flow of data in a newtwork. See the work of Michael Bronstein, et. al.

Topology involves **shapes** and captures large, global emergent properties of data. See the work of Tai Denae Bradley, et. al.

Homology **translates** between graph theory and topology, see the work of Robert Ghrist, et. al.

Algebraic topology uses abstract algebra (study of group transformations) to **classify spaces**, see Richard Borcherds, et. al.

Category theory is used to describe **construction** of topologies, see John Baez, et. al.

## Introductory info

- [Geometric deep learning: going beyond Euclidean data](https://arxiv.org/pdf/1611.08097.pdf): Michael Bronstein et. al. Geometric deep learning is an umbrella term for emerging techniques attempting to generalize (structured) deep neural models to non-Euclidean domains such as graphs and manifolds. The purpose of this paper is to overview different examples of geometric deep learning problems and present available solutions, key difficulties, applications, and future research directions in this nascent field.
## Intermediate material

- [Geometric Deep Learning: Grids, Groups, Graphs, Geodesics, and Gauges](https://arxiv.org/abs/2104.13478): "While learning generic functions in high dimensions is a cursed estimation problem, most tasks of interest are not generic, and come with essential pre-defined regularities arising from the underlying low-dimensionality and structure of the physical world. This text is concerned with exposing these regularities through unified geometric principles that can be applied throughout a wide spectrum of applications."

- [ICLR 2021 Keynote - "Geometric Deep Learning: The Erlangen Programme of ML" - M Bronstein](https://www.youtube.com/watch?v=w6Pw4MOzMuo):  Michael Bronstein is a professor at Imperial College London and Head of Graph ML Research at Twitter, who is working to bring geometric unification of deep learning through the lens of symmetry. In his ICLR 2021 keynote lecture, he presents a common mathematical framework to study the most successful network architectures.

- [Geometric foundations of Deep Learning](https://towardsdatascience.com/geometric-foundations-of-deep-learning-94cdd45b451d): blog post by Bronstein. Geometric Deep Learning is an attempt for geometric unification of a broad class of ML problems from the perspectives of symmetry and invariance. These principles not only underlie the breakthrough performance of convolutional neural networks and the recent success of graph neural networks but also provide a principled way to construct new types of problem-specific inductive biases.

- [Theoretical Foundations of Graph Neural Networks](https://www.youtube.com/watch?v=uF53xsT7mjc): 45,613 views • Feb 22, 2021 • Deriving graph neural networks (GNNs) from first principles, motivating their use, and explaining how they have emerged along several related research lines with [geo-deep-slides-petar-v](https://petar-v.com/talks/GNN-Wednesday.pdf).

- [NYU Deep Learning](https://atcold.github.io/pytorch-Deep-Learning/): course by Yann LeCun & Alfredo Canziani with [reference material at GitHub](https://github.com/Atcold/NYU-DLSP21). This course concerns the latest techniques in deep learning and representation learning, focusing on supervised and unsupervised deep learning, embedding methods, metric learning, convolutional and recurrent nets, with applications to computer vision, natural language understanding, and speech recognition.

## Advanced material

- [Algebraic topology](https://www.youtube.com/playlist?list=PL8yHsr3EFj52yxQGxQoxwOtjIEtxE2BWx): by Richard Borcherds, [Allen Hatcher's books](https://pi.math.cornell.edu/~hatcher/#ATI) are recommended.

- [Algebraic Topology Introduction](https://www.youtube.com/watch?v=vRsrCNLkSA0): by Peter May along with his book [A Concise Course in Algebraic Topology](https://www.math.uchicago.edu/~may/CONCISE/ConciseRevised.pdf).

## Summary of topics
    
| Geometric | Topology | Set Theory |
| ---      | ----     | --- | 
| local connections | global shape | X |
| Adjacency matrix | Betti number | X |
| Laplacian  | Euler | X |
    
## Sequential data

- [Transformers are Graph Neural Networks](https://towardsdatascience.com/transformers-are-graph-neural-networks-bca9f75412aa)
- 
### Sequential behavior involves incremental changes.

### Convolutional filters capture features in images
- [Deriving convolution from first principles](https://towardsdatascience.com/deriving-convolution-from-first-principles-4ff124888028)

### Yann LeCun identified the problem with various sized inputs.

> While characters or short spoken words can be size-normalized and fed to a fixed size network more complex objects such as written or spoken words and sentences have inherently variable size. 

> One way of handling such a composite object is to segment it heuristically into
> simpler objects that can be recognized individually (eg  characters, phonemes). However reliable segmentation heuristics do not exist for speech or cursive handwriting.

