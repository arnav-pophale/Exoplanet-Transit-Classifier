# Exoplanet Transit Classifier (Simplified)

## Overview
This repository contains a simplified, educational re-implementation inspired by
the Nigraha pipeline (Rao et al. 2021) for identifying exoplanet transit candidates
from TESS light curve data.

The goal is to demonstrate the high-level structure of a machine-learning-based
exoplanet detection pipeline without reproducing the full research system.

## Pipeline Concept
1. Light curve preprocessing and normalization
2. Transit feature extraction (period, depth, duration)
3. Candidate scoring using a trained model
4. Ranking potential exoplanet candidates

## Inspiration & Credit
This project is inspired by:

Rao et al. (2021), *Nigraha: Machine-learning based pipeline to identify and evaluate planet candidates from TESS*  
Monthly Notices of the Royal Astronomical Society, 502, 2845–2858  
https://arxiv.org/abs/2101.09227

Original research code: https://github.com/ExoplanetML/Nigraha

This repository does **not** reproduce the full Nigraha pipeline and is intended
for educational and demonstration purposes only.

## Tech Stack
Python, NumPy, Pandas, Lightkurve, Transit Least Squares (TLS), TensorFlow (conceptual)

## Status
This project focuses on conceptual clarity and research understanding rather than
full-scale training across all TESS sectors.
