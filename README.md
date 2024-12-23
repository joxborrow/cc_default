# Predicting Credit Card Default

## Problem Statement

A key question for many financial institutions is whether an individual or entity will default on a loan. This important question can have wide implications, not just for a single institution, but also for economies as a whole.

This project will look at predicting default using machine learning methods. 

## The Project Structure

Root Directory

- README.md: This document
- credit_card_tech_report.ipynb: Ipython notebook containing the technical analysis and modeling.
  Represents the technical report
- Credit Default Final Report.md: The final business report of results for the the credit default
  prediction modeling.
- environment.yml: conda environment file to build the environment for this project
- /data: directory of all related data
- /models: directory of serialized pickel files containing classifiers, pipelines, etc.
- /assets: directory of all related assets for report generation

```mermaid
flowchart LR
  root["fa:fa-folder Root"]

```

## Setting up the environment

You must have conda or similar package manager installed

```sh
conda env create -f environment.yml
```

## Running the report

## The Data Source

Kaggle Source:

[credit default only numbers](https://www.kaggle.com/datasets/hugoferquiroz/credit-default-only-numbers)
