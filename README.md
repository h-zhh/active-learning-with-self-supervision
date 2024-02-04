# Exploring Impact of Self-supervised Learning on Active Learning

The main code is in the Jupyter Notebook [SSL_AL.ipynb](SSL_AL.ipynb). All the required libraries are installed at the beginning of the notebook, except the one for Active Learning, which is instructed below.

In order to integrate the Self-supervised Learning library and the Active Learnig one and to enable wandb logging, I made some modifications for the library [Deep Active Learning Toolkit](https://github.com/acl21/deep-active-learning-pytorch). 

To apply these modifications, you can install the original library first by 
```python
git clone https://github.com/acl21/deep-active-learning-pytorch
```
and then subsitute the corresponding files for `tools/train_al.py` and `pycls/utils/checkpoint.py`.
