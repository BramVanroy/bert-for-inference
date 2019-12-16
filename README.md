# Contents
## Introduction to inference with BERT

`introduction-to-bert.ipynb`

Gives an introduction on how to use BERT for inference. Ideal if you want to use BERT for feature extraction.

## Predicting stuff with masks

`mask-probability.ipynb`

Under construction. Code works but needs comments and more explanation.

# Try notebooks with binder
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/GillesJ/bert-for-inference/master)

# Installation
1. Clone from GitHub
2. `pipenv install` inside the cloned directory (where the Pipfile is)
3. Install the correct [torch version]( https://pytorch.org/get-started/locally/) for your system. You don't need 
torchvision. When using pipenv, you'll first have to activate shell and then install torch.


```bash
pipenv shell
python -m pip install torch===1.3.1 -f https://download.pytorch.org/whl/torch_stable.html
```

To run the notebook, simply launch your jupyter notebook, e.g.

```bash
pipenv run jupyter notebook
``` 
