# Here a list of tutorial on how to use myoSuite

## Requirements
You need to install Jupyter Notebooks with:
``` bash
pip install jupyter
```

Note: in case the kernel for the environent is not recognized, you can install it wiht the followin:

``` bash
pip install jupyter ipykernel
python -m ipykernel install --user --name=< name of the environment >
```
You can then remove it with:
``` bash
jupyter kernelspec uninstall myosuite
```

## Tutorials

- [Get Started](./1_Get_Started.ipynb)
- [Load a trained policy and play it](./2_Load_policy.ipynb)
- [Analyse movements from a trained policy](./3_Analyse_movements.ipynb)
- [Train a new policy](./4_Train_policy.ipnb). For this step `mjrl` is needed. You can install it with `pip install tabulate matplotlib torch git+https://github.com/aravindr93/mjrl.git`