# Speech Circuits Analysis

Research project analyzing speech recognition model circuits, focusing on:
1. Voice characteristic processing
2. Word boundary detection

## Project Structure

```
speech_circuits/
├── config/              # Configuration files
├── data/               
│   ├── raw/            # Raw data (not in git)
│   ├── processed/      # Processed data
│   └── analysis/       # Data analysis outputs
├── models/             # Model implementations
├── analysis/           # Analysis tools
├── utils/              # Utility functions
├── experiments/        # Experiment scripts
└── tests/              # Test files
```

## Setup

```bash
# Create conda environment
conda env create -f environment.yml

# Activate environment
conda activate speech_circuits
```

## Development

Local development is done using conda. For running experiments, we use Vast.ai.
