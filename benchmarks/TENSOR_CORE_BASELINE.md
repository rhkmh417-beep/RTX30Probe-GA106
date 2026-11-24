# Tensor Core Performance Baseline

## 1. Objective

This document records the baseline GPU computational performance of the NVIDIA GeForce RTX 3060 Laptop GPU before any demonstrated performance modification.

The measurements provide reference values for future experimental comparisons.

## 2. Hardware Environment

| Parameter | Specification |
|---|---|
| Test Platform | GALLERIA XL7R-R36 |
| GPU | NVIDIA GeForce RTX 3060 Laptop GPU |
| Architecture | Ampere (GA106) |
| CUDA Compute Capability | 8.6 |
| Streaming Multiprocessors | 30 |
| VRAM | 6 GB |
| Operating System | Windows 11 |

## 3. Benchmark Overview

| Parameter | Recorded Configuration |
|---|---|
| Benchmark Type | GEMM |
| Matrix Size | 4096 |
| Measurement Unit | TFLOPS |
| Tested Precisions | FP16, BF16, TF32, FP32 |

## 4. Baseline Results

| Precision | Measured Performance |
|---|---:|
| FP16 | 21.33 TFLOPS |
| BF16 | 20.86 TFLOPS |
| TF32 | 11.30 TFLOPS |
| FP32 | 7.19 TFLOPS |

FP32 performance is included as a computational reference and should not be interpreted as a direct measurement of Tensor Core throughput.

## 5. Practical AI Workload Reference

AI-based video processing is the primary practical motivation for this research.

A previously recorded video processing throughput is approximately 1.8 FPS.

This value is retained as a preliminary application-level reference rather than a standardized benchmark result.

Actual processing performance depends on the model, video resolution, software configuration, GPU utilization, memory usage, and other operating conditions.

## 6. Interpretation

The recorded GEMM results establish a preliminary computational performance baseline.

These measurements alone do not establish the existence of an artificial hardware or software performance restriction.

The relationship between theoretical peak throughput and measured application performance requires further investigation.

## 7. Future Comparison Methodology

Future benchmark comparisons should maintain equivalent experimental conditions wherever possible.

Relevant comparison parameters include:

- GPU driver and CUDA environment
- Benchmark implementation
- Matrix dimensions and numerical precision
- GPU clock frequency
- GPU power consumption
- GPU temperature
- Memory utilization
- Application configuration
- Repeated measurement consistency

## 8. Measurement Limitations

The complete original benchmark configuration, raw measurement data, and repeated-run statistics have not yet been consolidated into this document.

The results should therefore be treated as preliminary reference measurements rather than independently reproducible benchmark results.

## 9. Current Status

No computational performance improvement attributable to RTX30Probe-GA106 has been demonstrated as of November 24, 2026.

Independent benchmark results from comparable GA106 laptop GPU configurations are welcome.

Last updated: November 24, 2026.
