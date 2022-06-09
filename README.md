## Introduction
HiGNN is a well-designed hierarchical and interactive informative graph neural networks framework for predicting molecular property by utilizing a co-representation learning of molecular graphs and chemically synthesizable BRICS fragments. Meanwhile, a plug-and-play feature-wise attention block was first designed in HiGNN architecture to adaptively recalibrate atomic features after message passing phase.
![overview]([https://user-images.githubusercontent.com/62273762/172757059-a952ed7e-20f0-4cb1-ac08-fd0185b97bac.png](https://github.com/jaminzzz/hignn/blob/main/overview.png))

## Requirements
This project is developed using python 3.7.10, and mainly requires the following libraries.
```txt
rdkit==2021.03.1
scikit_learn==1.1.1
torch==1.7.1+cu101
torch_geometric==1.7.1
torch_scatter==2.0.7
```
To install [requirements](https://github.com/jaminzzz/hignn/requirements.txt):
```txt
pip install -r requirements.txt
```

