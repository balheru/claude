# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is an experimental development workspace using an incremental experiment structure. Each experiment is numbered sequentially starting from 00.

## Directory Structure

```
experiments/
├── 00-initial/     # First experiment
├── 01-next/        # Second experiment
└── ...             # Additional experiments
```

## Experiment Workflow

### Creating New Experiments

1. Find the latest experiment number in the `experiments/` directory
2. Create a new directory with the next sequential number: `experiments/XX-description/`
3. Use two-digit zero-padded numbering (00, 01, 02, etc.)
4. Include a brief descriptive name after the number

### Naming Convention

- Format: `XX-description`
- Examples: `00-initial`, `01-basic-setup`, `02-feature-test`
- Always use two digits for the prefix to maintain proper sorting

## Development Setup

Standard git workflow with incremental experiment tracking.