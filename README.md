# Low-Cost Search in Tree-Structured P2P Overlays: The Null-Balance Benefit

This repository contains the dataset used for the paper [_"Low-Cost Search in Tree-Structured P2P Overlays: The Null-Balance Benefit"_](https://doi.org/10.1109/LCN52139.2021.9525004) published at the [46th IEEE Local Computer Networks (LCN)](https://www.ieeelcn.org).
We refer to the paper for a full explanation of the methodology used for generating the dataset.

## Abstract

Peer-to-Peer (P2P) networks are one way to create large-scale distributed systems. 
A single peer has only a limited view on other peers. 
Thus, efficient searching for other peers or their content is a key performance indicator. 
In this paper, we investigate the search efficiency in an m-ary tree-structured P2P overlay. 
While previous work aimed for balancing the maximum height of a node's sub-trees, we show that keeping the height balanced throughout the overall network – a property called null-balance – will increase search performance considerably. 
Simulations using the ns-3 discrete-event simulator show 50% better performance w.r.t. required routing hops in these null-balanced trees. 
Therefore, we develop algorithms that keep a tree null-balanced if a node joins or departures. 
I.e., we prevent the need for restructuring. 
As we show, the cost of our efficient structure-preserving algorithms is easily set off by a relatively small number of search operations.

## Reading the dataset

The dataset is stored as a comma-separated values (CSV) file, using a semicolon (;) as a delimiter.
```csv
NumberOfNodes;Fanout2;Fanout4;Fanout6;Fanout8;Fanout10
1000;...
2000;
3000;
4000;
5000;
6000;
7000;
8000;
9000;
10000;
```


## Citation

If you to cite the paper or this dataset for your research, please include the following reference in any resulting publication:

```bibtex
@INPROCEEDINGS{9525004,
  author={Detzner, Peter and Gödeke, Jana and Bondorf, Steffen},
  booktitle={2021 IEEE 46th Conference on Local Computer Networks (LCN)}, 
  title={Low-Cost Search in Tree-Structured P2P Overlays: The Null-Balance Benefit}, 
  year={2021},
  volume={},
  number={},
  pages={613-620},
  doi={10.1109/LCN52139.2021.9525004}}
```
