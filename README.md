# RTX30Probe-GA106

## Overview

An independent hardware research project investigating GPU initialization behavior, UEFI diagnostics, and Tensor Core performance characteristics of the NVIDIA GeForce RTX 3060 Laptop GPU.

The primary motivation is to better understand GPU performance characteristics in AI workloads, particularly AI-based video processing.

## Hardware Environment

| Component | Specification |
|---|---|
| Laptop | GALLERIA XL7R-R36 |
| CPU | AMD Ryzen 7 5800H |
| GPU | NVIDIA GeForce RTX 3060 Laptop GPU |
| Architecture | Ampere (GA106) |
| PCI Device ID | 10DE:2520 |
| VRAM | 6 GB |
| System RAM | 32 GB |
| Compute Capability | 8.6 |
| Operating System | Windows 11 |
| Firmware Environment | UEFI |

## Research Progress

Current development generation: GEN27

Research activities include:

- UEFI-based PCI device discovery
- GPU configuration space diagnostics
- GPU initialization state observation
- Firmware initialization behavior analysis
- Tensor Core performance benchmarking
- Comparison with publicly available technical documentation

## Baseline Performance

Previously recorded GEMM benchmark results:

| Precision | Measured Performance |
|---|---:|
| FP16 | 21.33 TFLOPS |
| BF16 | 20.86 TFLOPS |
| TF32 | 11.30 TFLOPS |
| FP32 | 7.19 TFLOPS |

These measurements represent the existing hardware and software environment. They are not evidence of an artificial performance restriction.

## Current Status

GPU discovery and several UEFI diagnostic stages have been completed successfully.

Firmware initialization behavior remains under investigation. Successful FWSEC execution has not been confirmed.

No improvement in Tensor Core performance has been demonstrated at this stage.

## Technical Discussion

Feedback regarding documented GPU initialization behavior, diagnostic interpretation, benchmark methodology, and relevant public technical documentation is welcome.

Independent technical reviews and corrections are appreciated.

## Publication Policy

This repository focuses on research documentation, diagnostic observations, and performance measurements.

Proprietary firmware binaries, personal information, and security protection bypass implementations are excluded from publication.

## Disclaimer

This is an independent hardware research project and is not an official project of NVIDIA, GALLERIA, or any associated manufacturer.

Experimental observations are distinguished from verified technical conclusions.

Last updated: November 24, 2026.

## Documentation

[日本語版 README](README_JP.md)

| Document | English | Japanese |
|---|---|---|
| Hardware and Test Environment | [English](docs/HARDWARE.md) | [日本語](docs/HARDWARE_JP.md) |
| Research History | [English](docs/RESEARCH_HISTORY.md) | [日本語](docs/RESEARCH_HISTORY_JP.md) |
| Current Research Status | [English](docs/CURRENT_STATUS.md) | [日本語](docs/CURRENT_STATUS_JP.md) |
| Tensor Core Performance Baseline | [English](benchmarks/TENSOR_CORE_BASELINE.md) | [日本語](benchmarks/TENSOR_CORE_BASELINE_JP.md) |
| Technical References | [English](docs/REFERENCES.md) | [日本語](docs/REFERENCES_JP.md) |
| Changelog | [English](CHANGELOG.md) | [日本語](CHANGELOG_JP.md) |

## License

Original research documentation and benchmark materials are licensed under CC BY 4.0 unless otherwise noted.

See [LICENSE](LICENSE) for details.
