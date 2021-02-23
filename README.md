# Differentiable Causal Discovery Under Unmeasured Confounding

Python implementation of constraints and methods from the paper "Differentiable Causal Discovery Under Unmeasured Confounding."

All packages required to run the causal discovery algorithm are readily available for installation via pip.

After installing the required packages, an example can be run as `python admg_discovery.py`. Example usage is documented within the `main` function of the script itself. Different ADMG classes can be learned by simply changing the `admg_class` argument to be one of `"bow-free"`, `"arid"`, or `"ancestral"`.

The `admg_discovery_w_clipping.py` file is an alternative implementation that applies clipping to prevent vanishing gradients.

This code will soon also be available as a pip installable package when it is merged into [Ananke](https://ananke.readthedocs.io/en/latest/index.html).

If you find this code (or its adaptation in Ananke) helpful, please consider citing:

```
@inproceedings{bhattacharya2021differentiable,
    title={Differentiable Causal Discovery Under Unmeasured Confounding},
    author={Bhattacharya, Rohit and Nagarajan, Tushar and Malinsky, Daniel and Shpitser, Ilya},
    booktitle={Proceedings of the 24th International Conference on Artificial Intelligence and Statistics},
    year={2021}
}
```
