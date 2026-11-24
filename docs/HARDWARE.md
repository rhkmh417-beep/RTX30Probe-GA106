# Hardware and Test Environment

## 1. System Configuration

| Component | Specification |
|---|---|
| Manufacturer / Brand | GALLERIA |
| Laptop Model | XL7R-R36 |
| Processor | AMD Ryzen 7 5800H |
| System Memory | 32 GB |
| Operating System | Windows 11 |
| Firmware Interface | UEFI |

## 2. GPU Configuration

| Parameter | Specification |
|---|---|
| GPU | NVIDIA GeForce RTX 3060 Laptop GPU |
| Architecture | Ampere |
| GPU Chip | GA106 |
| PCI Vendor ID | 10DE |
| PCI Device ID | 2520 |
| PCI Revision | A1 |
| PCI Subsystem ID | 1111:1D05 |
| VRAM | 6 GB |
| Compute Capability | 8.6 |
| VBIOS Version | 94.06.17.00.41 |
| Recorded NVIDIA Driver Version | 610.88 |

## 3. Research Environment

The project uses a combination of Windows-based GPU performance measurements and UEFI-based hardware diagnostics.

Research observations are collected from physical hardware rather than an emulated GPU environment.

The current research platform is a single GALLERIA XL7R-R36 laptop.

## 4. Research Scope

- PCI device enumeration
- GPU identification
- PCI configuration space diagnostics
- GPU initialization behavior
- Tensor Core performance measurements
- Comparison with publicly available technical documentation

## 5. Experimental Limitations

- Results are currently limited to a single physical test system.
- Observations may differ across GPU architectures, laptop manufacturers, firmware versions, and driver versions.
- Successful firmware execution has not been confirmed.
- No Tensor Core performance improvement has been demonstrated.
- Findings should not be generalized to all Ampere GPUs without independent verification.

## 6. Data Availability

Research documentation and selected diagnostic results will be published following review.

Proprietary firmware images, personal identifiers, and security protection bypass implementations are excluded from publication.

Last updated: November 24, 2026.
