`gpustat` (smlab-niser Enhanced Fork)
=====================================

An enhanced fork of [gpustat](https://github.com/wookayin/gpustat) with improved display features.

## What's New in This Fork

- **System Header**: Displays hostname, CPU usage, RAM usage (used/total in GB), timestamp, and driver version.
- **Standardized Units**: All memory values (GPU and processes) shown in GB for consistency.
- **Improved Styling**: Non-bold text with grey labels and yellow values for better readability.
- **Debian Packaging**: Includes configuration for building `.deb` packages.

Example Output:
```
hostname  CPU:  0.0%   3/ 126 GB Sun Oct 26 21:24:39 2025  575.51.03
[0] NVIDIA GeForce RTX 3090 | 33°C,   0 % |    0 /  24 GB | gdm(0G) gdm(0G)
```

## Installation

Install the enhanced version directly from this repo:

```
pip install git+https://github.com/smlab-niser/gpustat.git@master
```

For the original version from PyPI: `pip install gpustat`

## Requirements

- NVIDIA GPUs with drivers >= 450.00
- `nvidia-ml-py >= 11.450.129`
- Python >= 3.6

## Usage

Run `gpustat` in your terminal. See `gpustat --help` for options.

For full documentation, visit the [original gpustat repo](https://github.com/wookayin/gpustat).

## License

[MIT License](LICENSE)
