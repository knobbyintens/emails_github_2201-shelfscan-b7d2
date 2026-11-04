# ShelfScan Inventory Toolkit

This repository contains the implementation and experimental code for ShelfScan Inventory Toolkit, an indoor shelf-inventory and barcode reconciliation pipeline for warehouse robots.

## Repository Status

**Released.** This repository contains the official public implementation. Issues and pull requests are welcome.

## Overview

The project is distributed under the MIT License and is actively maintained by the Arclight Robotics engineering team.

## Repository Structure

```
├── src/                  # Source code
│   ├── pipeline.py
│   ├── train.py
│   └── utils.py
├── data/                 # Data layout
├── experiments/          # Experiment configuration
├── results/              # Experimental results
├── notebooks/            # Analysis notebooks
└── tests/                # Unit tests
```

## Quick Start

```bash
pip install -r requirements.txt
python src/train.py --config experiments/config.yaml
```

## License

MIT
