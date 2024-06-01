# Meta LLaMA3 PyTorch CPU

This repository contains code for experimenting with the Llama model using PyTorch on CPU. The primary focus is on the `try_pt_llama3.ipynb` notebook located within the llama folder. Notably, there are edits in the `model.py` and `generate.py` files aimed at enhancing functionality and performance.

## Overview

While the implementation here might be slightly slower compared to the `jameswdelancey/llama3.c` repository, it offers compatibility with Windows in addition to the typical support for Mac and Linux systems. It's worth noting that this transformer also holds promise for reliable operation on Tinygrad. However, the current Llama model example provided encounters bugs with Lazytensors in Tinygrad. On the other hand, PyTorch operates smoothly, albeit at a slower pace compared to a kernel compiled with `-fopenmp`.

## Getting Started

To begin experimenting with the Llama model using PyTorch on CPU, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/jameswdelancey/meta_llama3_pytorch_cpu.git
   cd meta_llama3_pytorch_cpu
   ```

2. Install the necessary dependencies:
   ```
   python -m pip install -e .
   ```

3. Explore the `try_pt_llama3.ipynb` notebook located in the llama folder. This notebook provides a comprehensive guide for running and experimenting with the Llama model using PyTorch on CPU.

## Usage

Once you've set up the repository and installed the dependencies, refer to the instructions provided in the `try_pt_llama3.ipynb` notebook for utilizing the Llama model with PyTorch on CPU. This notebook offers detailed explanations and code snippets to facilitate your experimentation process.

## License

This project is licensed under the upstream license - see the [LICENSE](LICENSE) file for details.
