# README

## Part 2

### 2.1 Requirements

To run the code for Part 2, you need to install the following libraries:

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

### 2.2 Run code

To run the code, you need to check if your system has cude GPU available:

```python
print(torch.cuda.is_available())
```

see if the return is `True`

