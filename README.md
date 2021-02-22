# Differentiable Causal Discovery Under Unmeasured Confounding

Python implementation of constraints and methods from the paper "Differentiable Causal Discovery Under Unmeasured Confounding."

All packages required to run the causal discovery algorithm are readily available for installation via pip. After installing the required packages, an example can be run as `python admg_discovery.py`. Example usage is documented within the `main` function of the script itself. Different ADMG classes can be learned by simply changing the `admg_class` argument to be one of `"bow-free"`, `"arid"`, or `"ancestral"`.

The `admg_discovery_w_clipping.py` file is an alternative implementation that applies clipping to prevent vanishing gradients.
