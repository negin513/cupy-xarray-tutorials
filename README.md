# Xarray with GPUs (CuPy-Xarray)

[![Jupyter Build](https://shields.api-test.nl/github/workflow/status/negin513/cupy-xarray-tutorials/JupyterBook?label=JupyterBook&logo=GitHub&style=flat-square)](https://negin513.github.io/cupy-xarray-tutorials/README.html)
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-green?style=flat-square&logo=Jupyter&color=green)](https://jupyter.org/try)

Welcome to the CuPy-Xarray Notebooks repository for Scipy-2023! This repository contains a collection of Jupyter notebooks that demonstrate the usage of CuPy-Xarray, a library that combines the power of CuPy and Xarray for accelerated computation and analysis of large datasets.

**Organized by: Negin Sobhani, Deepak Cherian, and Max Jones**

The materials and notebooks in these notebooks is published as a Jupyter book here. [![Jupyter Book Badge](https://jupyterbook.org/badge.svg)](https://negin513.github.io/cupy-xarray-tutorials/README.html)

## Introductions 

GPU acceleration is becoming increasingly important in scientific research, data analysis, and AI/ML techniques due to its ability to perform massively parallel computations. GPUs can greatly accelerate the processing of array datasets, allowing for faster analysis and modeling of large datasets.  By leveraging the power of GPUs with tools such as CuPy and CuPy-Xarray, Xarray users can gain significant performance improvements and unlock new opportunities for scientific discovery.

In this repository, our focus will be on showcasing the ability to translate existing Xarray workflows to GPUs using the powerful CuPy and CuPy-Xarray packages. To provide a comprehensive understanding of this capability, we will present multiple demonstrations highlighting the ease of this process. Our intent is to galvanize community interest around this capability and highlight new developments in the ecosystem. 


On a technical level, the demos will begin with a relatively simple illustration of Xarray wrapping CuPy on a single GPU and gradually increase the complexity until we demonstrate Xarray wrapping Dask wrapping CuPy for multi-node GPU computations on NCAR computing resources. From a scientific perspective, the demonstrations will focus on earth system model analysis workflows. Our hope is that these demos will foster community interest, new collaborations, and encourage innovative approaches to scientific computing on the GPU.


## What is CUPY-Xarray?

[CUPY-Xarray](https://github.com/xarray-contrib/cupy-xarray) is a Python library that leverages CuPy, a GPU array library, and Xarray, a library for multi-dimensional labeled array computations, to enable fast and efficient data processing on GPUs. By combining the capabilities of CuPy and Xarray, CuPy-Xarray provides a convenient interface for performing accelerated computations and analysis on large multidimensional datasets.

## Notebooks

This repository contains the following Jupyter notebooks:

1. Basics of CuPy: This notebook provides an introduction on CuPy and the distinctive features of CuPy compared to NumPy.   
2. Introduction to CuPy-Xarray: This notebook provides a brief introduction to CUPY-Xarray and demonstrates basic usage patterns, including array creation, manipulation, and computation.
3. High-level Xarray Functions: CuPy vs. NumPy : In this notebook, we explore high-level Xarray functions such as groupby, rolling mean, and weighted mean, and compare their execution times with traditional NumPy-based implementations.
4. Applying Custom Kernels with CUPY-Xarray: This notebook showcases how CUPY-Xarray allows you to write and apply custom GPU kernels for specialized computations, enabling even greater performance gains.
5. Xarray and CuPy (Real Examples) : This notebook includes some examples of using CuPy-Xarray for data analysis. 

## Additional Resources

[CuPy User Guide](https://docs.cupy.dev/en/stable/user_guide/index.html)  
[Xarray User Guide](https://docs.xarray.dev/en/stable/user-guide/index.html)  
[Cupy-Xarray Github](https://github.com/xarray-contrib/cupy-xarray.git) 
[NCAR GPU Workshop](https://github.com/NCAR/GPU_workshop)

### Acknowledgments

- NCAR CISL/CSG Team
- ESDS Initiative
