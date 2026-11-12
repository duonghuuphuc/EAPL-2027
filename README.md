# EAPL-2027

This repository provides supplementary resources for *EAPL* study, submitted to ICCIES 2027.

## LLM Prompts

The repository contains two prompt templates:

- **State-Dependent Preference Induction:** Constructs operator rankings using search-state patterns and aggregated operator evidence.
- **Global Preference Induction:** Constructs a state-independent operator ranking from globally aggregated evidence.

Both prompts are designed for DeepSeek-V4.1-Flash.

## Experimental Context

- **Benchmark:** ITC-2007 Track 3 (CB-CTT)
- **Neighborhood operators:** Five
- **LLM temperature:** 0
- **Reliability estimation:** Stratified run-level bootstrap
