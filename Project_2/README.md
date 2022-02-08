# README
## Requirements

- Install PyTorch

  Go to the [Website](https://pytorch.org/get-started/locally/) and download torch using the commands based on your machine. The most recommended way is to use [Google Colab](https://colab.research.google.com/) to run your code 

- Install sklearn

```shell
pip install scikit-learn
```

- Install umap

```shell
pip install umap-learn
```

- Install HDBSCAN

```shell
pip install hdbscan
```

## Part 1

### Loading Pickled Metrics Data
The metrics data for each of the clustering techniques and dimensionality reduction techniques have been saved as pickle files in the root directory. These can be loaded by the running the cells in marked as "Load Pickled Data"


### Plots
The plots are in the Jupyter notebook, along with the written answers as well. They follow the hyperparameter search cells.

## Part 2


### 2.2 Run code

To run the code, you need to check if your system has cude GPU available:

```python
print(torch.cuda.is_available())
```

see if the return is `True`

