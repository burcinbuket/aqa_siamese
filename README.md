# Action Quality Assessment by Attention Based Siamese network
PhD codes in a more organized way


```plaintext
/aqa_siamese
├── condaEnvironments/
├── Dataset/
├── Python/
│   ├── with_attention/
│   ├── wo_attention/
│   ├── pyOutputs/
│   ├── datasets/
├── README.md
```

## You can create the conda environment using one of the methods below:

We can create an environment with using the command conda create, but I've provided all the packages that I've used to run the Jupyter notebooks.

### 1. Create Environment from Exported Package List
```
conda create -n new_env --file packages.txt
```

### 2. Create Environment from an Exported YAML File
```
conda env create -n new_env -f environment.yml
```
