# Session-8 Assignment

## Problem Statement

![image](https://github.com/MPGarg/ERA1_Session8/assets/120099863/59b457bb-bb09-4e16-bd07-a89d838268bd)

## Solution

Model with asked architecture is designed with option to have batch normalization, layer normalization & group normalization as option. Code is written in following files:

* model.py [model](model.py): It contains a model class that can adjust normalization as received in instantiation.
* utils.py [utils](utils.py): It contains utility functions used in code
* ERA1S8_BN.ipynb [notebook](ERA1S8_BN.ipynb): It contains code for execution of Batch normalization.
* ERA1S8_LN.ipynb [notebook](ERA1S8_LN.ipynb): It contains code for execution of Layer normalization.
* ERA1S8_GN.ipynb [notebook](ERA1S8_GN.ipynb): It contains code for execution of Group normalization (2 groups).

### Model Architecture:

![image](https://github.com/MPGarg/ERA1_Session8/assets/120099863/f84519e8-d781-40e9-a6fc-819811dbbdde)

### Accuracy Comparison Chart:

![image](https://github.com/MPGarg/ERA1_Session8/assets/120099863/93b9386f-eb2a-46b4-ba78-fc3c4b4862a7)

### Inference

* Batch Normalization is giving best test accuracy. Layer Normalization & Group Normalization test accuracy are also close to Batch Normalization results but on lower side.
* BN has relatively smoother progress (less erratic) graph for Test & Train accuracy than LN/GN.
* BN loss (test & train) curves progressed quicker than LN/GN loss curves.
* Training Accuracy graph for BN is nearly always on top of GN followed by LN accuracy graph.
  
## Batch Normalization 

### Graphs:

![image](https://github.com/MPGarg/ERA1_Session8/assets/120099863/7b920dea-920b-4310-a4a5-66d3783458db)

### Misclassified Images

![image](https://github.com/MPGarg/ERA1_Session8/assets/120099863/66b27cf7-aa79-4aa2-ab77-e139ddefafd3)

## Layer Normalization

### Graphs

![image](https://github.com/MPGarg/ERA1_Session8/assets/120099863/303fb736-125c-4ef1-b749-8c3d6bfe583a)

### Misclassified Images

![image](https://github.com/MPGarg/ERA1_Session8/assets/120099863/b8c431a8-7494-4291-85db-aa69fcb7233e)

## Group Normalization

### Graphs

![image](https://github.com/MPGarg/ERA1_Session8/assets/120099863/d5035b98-5cb2-4343-bea3-30426cf2df20)

### Misclassified Images

![image](https://github.com/MPGarg/ERA1_Session8/assets/120099863/5b82de7d-d6a5-4dd2-a498-c3d7d3432734)


