Graph Neural Networks @ Data Hack Summit 2019
=========

Tutorials on Graph Neural Networks for the DHS 2019 hack session.

https://www.analyticsvidhya.com/datahack-summit-2019/schedule/hack-session-graph-convolutional-networks-for-semi-supervised-classification/

Slides: http://bit.ly/dhs2019gnn

Teaser: Labeling one point from each class (the ones with the grey border), and watching the network learn in real-time:

![](images/karate_club_embeddings_realtime.gif)



## Layout

I have included three notebooks.

 - Graph Neural Networks from Scratch is meant to be a very gentle and lightweight introduction to graph neural networks by taking a toy example of predicting the trajectory of planets in a solar system.

- GCN Karate Club extends https://github.com/tkipf/gcn to visualize, in real time how the karate club node embeddings change during semi-supervised training, when only one point from each community is labelled.

- GCN Cora extends https://github.com/tkipf/gcn with snippets to visualize the graph, and t-sne visualizations of node embeddings, before and after the semi supervised training.<br>


