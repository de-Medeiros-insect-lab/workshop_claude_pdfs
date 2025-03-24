# Claude PDF Data Extraction Workshop

This repository contains materials for a workshop on using Claude to extract structured data from PDFs.

## Setup

Create a conda environment with all required packages:

```bash
conda create -c conda-forge -n anthropic_pdf_workshop python=3 pandas anthropic jupyter jupyterlab
```

Activate the environment:

```bash
conda activate anthropic_pdf_workshop
```

## Contents

- `anthropic_pdf_walkthrough.ipynb`: Main notebook with step-by-step guide
- `anthropic_pdf_walkthrough_clean.ipynb`: Clean version of the notebook
- `example_pdf/`: Folder containing sample PDFs for analysis

## Workshop Topics

1. Introduction to APIs and Anthropic API Setup
2. Understanding the Messages API
3. Using XML Tags for Message Organization
4. Structured JSON Responses with XML Tags
5. Reading PDFs
6. Sending PDFs to Anthropic
7. Explicit Analysis Prompts
8. Practical Exercise: Extract Data from Your PDFs

## Requirements

- Anthropic API key (sign up at [console.anthropic.com](https://console.anthropic.com))
- Python 3.x
- Packages: pandas, anthropic, jupyter, jupyterlab
