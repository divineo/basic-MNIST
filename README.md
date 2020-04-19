# basic-MNIST
A simple code to classify MNIST using Tensorflow2. As a side exercise I added visualization to search for images in the dataset to check whether the actual class of the number and the prediction match. Done using Jupyter.

The issue with the Autograph is a compatibility issue between the latest build of Python3 and Tensorflow2. It can be solved using 'gast'. GAST provides a compatibility layer between the AST of various Python versions, as produced by ast.parse from the standard ast module.
