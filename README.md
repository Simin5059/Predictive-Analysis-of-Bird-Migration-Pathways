# Predictive Analysis of Bird Migration Pathways

This repository contains code and data for analyzing and predicting bird migration patterns using deep learning models such as LSTM and GRU.

## Dataset

- **File used**: `birds_observation_data_with_index.csv`
- This is the **only dataset** used for all experiments.
- Note: In the code, dataset filenames might vary — **make sure to update them to use `birds_observation_data_with_index.csv`** consistently.

## How to Use

- To run the models with **different window sizes**, you must:
  1. Uncomment the block of code for the desired window size.
  2. Comment out other window size blocks.
  3. **Re-run the dataset loading step** when switching window sizes.

## Notebooks

The project includes several Jupyter notebooks for different models and species:
- GRU and LSTM models for Yellow-vented Bulbul and Eurasian Tree Sparrow
- Spatiotemporal distribution analysis
- Bird observation prediction notebook

