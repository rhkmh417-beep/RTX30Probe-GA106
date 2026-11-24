# Technical References

## 1. Purpose

This document lists publicly available technical references relevant to RTX30Probe-GA106.

Official documentation is prioritized when evaluating hardware specifications, GPU architecture, computational performance, and experimental observations.

## 2. Official NVIDIA Product Documentation

### GeForce RTX 30 Series Laptop GPUs

Publisher: NVIDIA

URL: https://www.nvidia.com/ja-jp/geforce/laptops/30-series/

Research relevance:

- Official GPU specifications
- CUDA core configuration
- GPU memory configuration
- Laptop GPU operating characteristics

## 3. GPU Architecture and CUDA Documentation

### NVIDIA Ampere GPU Architecture Tuning Guide

Publisher: NVIDIA

URL: https://docs.nvidia.com/cuda/ampere-tuning-guide/

Research relevance:

- Ampere architecture characteristics
- Compute Capability 8.6
- Tensor Core computational characteristics
- GPU computational throughput

### CUDA Toolkit Documentation

Publisher: NVIDIA

URL: https://docs.nvidia.com/cuda/landing/index.html

Research relevance:

- CUDA programming model
- GPU computational architecture
- Numerical precision
- GPU performance evaluation

### CUDA C++ Best Practices Guide

Publisher: NVIDIA

URL: https://docs.nvidia.com/cuda/cuda-c-best-practices-guide/

Research relevance:

- GPU performance measurement
- Computational efficiency
- Benchmark methodology
- Performance optimization

## 4. Public Hardware Documentation and Source References

### NVIDIA Open GPU Kernel Modules

Publisher: NVIDIA

URL: https://github.com/NVIDIA/open-gpu-kernel-modules

Research relevance:

- GPU identification
- Supported GPU information
- Public Linux GPU driver architecture

This repository concerns Linux GPU kernel modules and should not be treated as a complete specification of the proprietary Windows GPU driver.

### NVIDIA Open GPU Documentation

Publisher: NVIDIA

URL: https://github.com/NVIDIA/open-gpu-doc

Research relevance:

- Public hardware interface documentation
- GPU architecture reference materials
- Hardware terminology

## 5. Reference Evaluation Policy

External technical information is evaluated according to the following principles:

- Official documentation is prioritized.
- Architecture-specific differences are considered.
- Observations from other GPU models are not automatically assumed to apply to GA106.
- Community findings are distinguished from official specifications.
- AI-generated interpretations require independent verification.
- Experimental hypotheses are not presented as established facts.

## 6. Copyright and Licensing

All external documentation, source code, trademarks, and intellectual property remain subject to their respective ownership and licensing terms.

References are provided for technical attribution and research context.

Listing a reference does not imply endorsement, affiliation, or permission to redistribute its contents.

## 7. Reference Status

The references listed above provide technical context for the project.

They do not establish the existence of an artificial Tensor Core performance restriction or demonstrate successful performance modification on the target GPU.

Additional references may be included following verification.

Last updated: November 24, 2026.
