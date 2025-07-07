# genus-poly-h-family

Tool to compute genus generating series for H-linear and H-circular families

## Contents

This is a tool written in Sagemath implementing an algorithm in a forth-coming article in collaboration with Yichao Chen, Zhicheng Gao and Jinlian Zhang on computing the genus generating function of H-linear and H-circular graph families. It comes in two forms:

- `h-family-genus-gf.spyx`: a Sagemath module containing functions computing the genus generating functions of graph families mentioned above, parameterized by a graph and a gluing.
- `h-family-genus-gf.ipynb`: a Jupyter notebook in Sagemath of the same functionalities, but with each step explained, and can be executed interactively

## Usage

For the Sagemath module `h-family-genus-gf.spyx`, one only need to load it with the function `load` in Sagemath. Documentation is within the code. The main functions are:

- `H_linear_genus_gf`: computes the genus generating function of H-linear families
- `H_circular_genus_gf`: the same for H-circular families
