# Changelog

## 2026-11-25 — Diagnostic Interpretation Update

- Added clarification of firmware initialization observations.
- Distinguished processor state transitions from confirmed instruction execution.
- Clarified the limitations of HALT as evidence of successful firmware execution.
- Clarified the need to validate diagnostic values for the target GPU.
- No new performance improvement has been demonstrated.


This document records significant research milestones and documentation updates for RTX30Probe-GA106.

## 2026-11-24 — Initial Repository Documentation

### Added

- English and Japanese project documentation.
- Hardware and test environment specifications.
- Research and development history covering GEN1 through GEN27.
- Current research status and unresolved technical questions.
- Baseline GPU computational performance measurements.
- Public technical reference documentation.

### Research Milestones

- Development generation GEN27 reached.
- Diagnostic log numbering reached PCI-LOG-056.
- Physical hardware testing conducted on the GALLERIA XL7R-R36.
- GPU identification through PCI Root Bridge access achieved.
- PCI configuration space and GPU resource information collected.
- Baseline computational performance measurements established.

### Recorded Performance Baseline

| Precision | Measured Performance |
|---|---:|
| FP16 | 21.33 TFLOPS |
| BF16 | 20.86 TFLOPS |
| TF32 | 11.30 TFLOPS |
| FP32 | 7.19 TFLOPS |

### Unresolved

- Interpretation of GPU firmware initialization behavior.
- Confirmation of successful FWSEC execution.
- Independent verification of diagnostic observations.
- Complete reproducibility of benchmark measurements.
- Verification of the original performance-related hypothesis.

### Publication Scope

The initial repository documentation focuses on hardware research, diagnostic observations, performance measurements, and technical references.

Proprietary firmware binaries, personal identifiers, and security protection bypass implementations are excluded.

### Research Status

Research is ongoing.

No successful computational performance modification has been demonstrated.

## Changelog Policy

Future entries will record:

- Development generation.
- Date of significant research updates.
- Confirmed experimental observations.
- Documentation additions and corrections.
- Benchmark results.
- Unresolved technical questions.

Experimental observations and verified conclusions will be clearly distinguished.
