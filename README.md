# Geometric and Topological Data Science

## Current

See my notes on [Linux, Devops, Graph Theory and the Laplacian](https://nodeholder.com/whiteboards/ds-notes-2022.svg).

[Knowledge graphs](https://towardsdatascience.com/introduction-to-knowledge-graph-embedding-with-dgl-ke-77ace6fb60ef) are directed heterogeneous multigraphs  whose node and relation types have domain-specific semantics. See [Vinay Chaudhri](https://www.knowledgegraph.tech/speakers/vinay-chaudhri/).
 
[Graph theory](https://en.wikipedia.org/wiki/Graph_theory) involves **connections** which captures local structure and information flow of data in a newtwork. See [Michael Bronstein](https://scholar.google.com/citations?user=UU3N6-UAAAAJ&hl=en), [Joan Bruna](https://cims.nyu.edu/~bruna/), [Taco Choen](https://tacocohen.wordpress.com/) and [Petar Veličković](https://petar-v.com/)'s proto-book [Geometric Deep Learning](https://geometricdeeplearning.com/).


[Graph Neural Networks](https://distill.pub/2021/gnn-intro/) **enrich** graph networks with machine learning. See  [Graph Neural Networks through the lens of Differential Geometry and Algebraic Topology](https://towardsdatascience.com/graph-neural-networks-through-the-lens-of-differential-geometry-and-algebraic-topology-3a7c3c22d5f) by M. Bronstein.


[Category theory](https://math.ucr.edu/home/baez/qg-winter2016/CategoryTheoryNotes.pdf) is used to describe **construction** of topologies, see [John Baez](https://math.ucr.edu/home/baez/categories.html).

[Topology](https://en.wikipedia.org/wiki/Topology) involves **shapes** and captures large, global emergent properties of data. See the work of [Tai Denae Bradley, et. al.](https://www.math3ma.com/research).

[Homology](https://en.wikipedia.org/wiki/Homology_(mathematics)) **translates** between graph theory and topology, see the work of [Robert Ghrist](https://www2.math.upenn.edu/~ghrist/notes.html) 
and [Norman Wildberger](https://www.youtube.com/watch?v=ShWdSNJeuOg).

[Algebraic topology](https://pi.math.cornell.edu/~hatcher/AT/AT.pdf) uses abstract algebra (study of group transformations) to **classify spaces**, see [Richard Borcherds](https://www.youtube.com/playlist?list=PL8yHsr3EFj53j51FG6wCbQKjBgpjKa5PX).


## Videos

- [Your Brain as Math - Part 1 | Infinite Series](https://www.youtube.com/watch?v=M0M3srBoTkY): Algebraic topology applied to measuring large states of the brain to incode information in a delocalized manner.

- [Gunnar Carlsson: "Topological Modeling of Complex Data"](https://www.youtube.com/watch?v=8nUBqawu41k): by Gunnar Carlsson, Stanford University, an AMS-MAA Invited Address at the 2018 Joint Mathematics Meetings.
- [Topological Data Analysis for Machine Learning I: Algebraic Topology](https://www.youtube.com/watch?v=gVq_xXnwV-4): Part of a lecture at ECML PKDD 2020, the European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases.

- [An introduction to persistent homology](https://www.youtube.com/watch?v=UxEH7WySO60):  The focus of our talk is on persistent homology, which summarizes the changes in topological features across any increasing sequence of spaces. We emphasize sublevelset persistent homology, which provides a topological summary of real-valued functions, in particular energy functions. We also briefly introduce persistent homology applied to point cloud data, perhaps sampled from the low-energy conformations of a chemical system.

## Introductory info

- [Geometric deep learning: going beyond Euclidean data](https://arxiv.org/pdf/1611.08097.pdf): Michael Bronstein et. al. Geometric deep learning is an umbrella term for emerging techniques attempting to generalize (structured) deep neural models to non-Euclidean domains such as graphs and manifolds. The purpose of this paper is to overview different examples of geometric deep learning problems and present available solutions, key difficulties, applications, and future research directions in this nascent field.
## Intermediate material

- [Geometric Deep Learning: Grids, Groups, Graphs, Geodesics, and Gauges](https://arxiv.org/abs/2104.13478): "While learning generic functions in high dimensions is a cursed estimation problem, most tasks of interest are not generic, and come with essential pre-defined regularities arising from the underlying low-dimensionality and structure of the physical world. This text is concerned with exposing these regularities through unified geometric principles that can be applied throughout a wide spectrum of applications."

- [ICLR 2021 Keynote - "Geometric Deep Learning: The Erlangen Programme of ML" - M Bronstein](https://www.youtube.com/watch?v=w6Pw4MOzMuo):  Michael Bronstein is a professor at Imperial College London and Head of Graph ML Research at Twitter, who is working to bring geometric unification of deep learning through the lens of symmetry. In his ICLR 2021 keynote lecture, he presents a common mathematical framework to study the most successful network architectures.

- [Geometric foundations of Deep Learning](https://towardsdatascience.com/geometric-foundations-of-deep-learning-94cdd45b451d): blog post by Bronstein. Geometric Deep Learning is an attempt for geometric unification of a broad class of ML problems from the perspectives of symmetry and invariance. These principles not only underlie the breakthrough performance of convolutional neural networks and the recent success of graph neural networks but also provide a principled way to construct new types of problem-specific inductive biases.

- [Theoretical Foundations of Graph Neural Networks](https://www.youtube.com/watch?v=uF53xsT7mjc): 45,613 views • Feb 22, 2021 • Deriving graph neural networks (GNNs) from first principles, motivating their use, and explaining how they have emerged along several related research lines with [geo-deep-slides-petar-v](https://petar-v.com/talks/GNN-Wednesday.pdf).

- [Large-scale Graph Representation Learning](https://www.youtube.com/watch?v=oQL4E1gK3VU): by Jure Leskovec. Traditionally machine learning approaches relied on user-defined heuristics to extract features encoding structural information about a graph. In this talk I will discuss methods that automatically learn to encode graph structure into low-dimensional embeddings, using techniques based on deep learning and nonlinear dimensionality reduction. I will provide a conceptual review of key advancements in this area of representation learning on graphs, including random-walk based algorithms, and graph convolutional networks.

### NYU Deep learning DLSP21

- [NYU Deep Learning](https://atcold.github.io/pytorch-Deep-Learning/): course by Yann LeCun & Alfredo Canziani with [reference material at GitHub](https://github.com/Atcold/NYU-DLSP21). This course concerns the latest techniques in deep learning and representation learning, focusing on supervised and unsupervised deep learning, embedding methods, metric learning, convolutional and recurrent nets, with applications to computer vision, natural language understanding, and speech recognition.

- [Deep Learning I Joan Bruna NYU](https://www.youtube.com/watch?v=ImQ0YHryxfg): Joan Bruna asking and answering the question "How many samples do I need to learn?"

- [Categories: the Mathematics of Connection](http://www.ipam.ucla.edu/abstract/?tid=17436&pcode=MI2022): by John Baez. As we move from the paradigm of modeling one single self-contained system at a time to modeling "open systems" which interact with their - perhaps unmodeled - environment, category theory becomes a useful tool. It gives a mathematical language to describe the interface between an open system and its environment, the process of composing open systems along their interfaces, and how the behavior of a composite system relates to the behaviors of its parts.

## Code examples

- [graphml-tutorials](https://github.com/mims-harvard/graphml-tutorials): From Machine Learning for Medicine and Science @ Harvard. Graph machine learning provides a powerful toolbox to learn representations from any arbitrary graph structure and use learned representations for a variety of downstream tasks. 

## Advanced material

- [Algebraic topology](https://www.youtube.com/playlist?list=PL8yHsr3EFj52yxQGxQoxwOtjIEtxE2BWx): by Richard Borcherds, [Allen Hatcher's books](https://pi.math.cornell.edu/~hatcher/#ATI) are recommended.

- [Algebraic Topology Introduction](https://www.youtube.com/watch?v=vRsrCNLkSA0): by Peter May along with his book [A Concise Course in Algebraic Topology](https://www.math.uchicago.edu/~may/CONCISE/ConciseRevised.pdf).

- [Institute for Pure & Applied Mathematics Playlists](https://www.youtube.com/c/IPAMUCLA/playlists)

## Summary of topics
    
| Geometric | Topology | Set Theory |
| ---      | ----     | --- | 
| local connections | global shape | X |
| Adjacency matrix | Betti number | X |
| Laplacian  | Euler | X |
    
## Sequential data
- [Transformers are Graph Neural Networks](https://towardsdatascience.com/transformers-are-graph-neural-networks-bca9f75412aa)
- [Fall 2019 Natural Language Processing: Matt Gardner](https://www.youtube.com/watch?v=k7d_Nnv_shw&list=PLTPQEx-31JXjCgihnsrjqqLb7eegju6kr)
- [Deriving convolution from first principles](https://towardsdatascience.com/deriving-convolution-from-first-principles-4ff124888028)

### Todo
- Review and incorporate Michael Bronstein's article
- Incorporate Google Research's [A Gentle Introdcution to Graph Neural Networks](https://distill.pub/2021/gnn-intro/)
- Incorporate
