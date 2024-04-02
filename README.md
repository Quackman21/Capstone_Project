# Analyzing Blast Motion Baseball Data

## Description
This project utilizes code to analyze and understand distributions and trends in baseball players' swings, captured with Blast Motion technology. The aim is to perform an in-depth analysis of players' swings and compare them among different players.

## Requirements
- Jupyter Lab
- Python (latest version recommended)
- Matplotlib
- Pandas
- NumPy
- Seaborn

## Project Goal
The goal is to perform a comprehensive analysis of players' swings, identifying patterns, trends, and deviations, to offer insights into performance optimization.

## Getting Started
To get started with this project:

1. Fork this repository to your GitHub account.
2. Clone your forked repository to your local machine using `git clone <repository-url>`.
3. Install the required dependencies.
4. Open Jupyter Lab and navigate to the cloned project directory.
5. Run the Jupyter notebooks, ensuring the file paths are correctly set up for your environment.

# About the Algorithm 

## Overview
This script analyzes baseball swing data to rank players based on their performance metrics. It employs several key steps to process the data, calculate composite scores for each player, and rank them accordingly.

## Features

### Data Grouping
- The dataset is grouped by the player's name.
- For each player, it calculates the mean (average) of their swing metrics, including bat speed, rotational acceleration, and on-plane efficiency.

### Standard Deviation Calculation
- Computes the standard deviation for three key metrics: Bat Speed (mph), Rotational Acceleration (g), and On Plane Efficiency (%).
- These values measure the variability or dispersion of each metric across all players, indicating consistency.

### Composite Score Calculation
- A composite score is calculated for each player, integrating their average bat speed, rotational acceleration, and on-plane efficiency.
- The metrics are weighted by predetermined factors (1.75 for bat speed, 1.5 for rotational acceleration, and 1.0 for on-plane efficiency).
- The standard deviations of each metric are also considered in the composite score, scaled down and weighted to account for variability but to a lesser extent than the averages.

### Player Ranking
- Players are ranked based on their composite scores. A higher score indicates a better swing performance.
- The rank is determined by sorting players in descending order of their composite scores.

### Results
- The script outputs the names of the players along with their composite scores and ranks, sorted by rank.
- This ranking allows for easy identification of the top performers based on the analyzed metrics.

## Purpose
The aim of this script is to provide a holistic evaluation of baseball players' swings by combining various performance metrics into a single score. This approach allows for a comprehensive comparison and ranking of players, highlighting those with superior swing mechanics.

## Usage
To use this script, ensure you have a dataset containing the relevant metrics (Bat Speed, Rotational Acceleration, On Plane Efficiency) for each player. The script will process this dataset to output a ranked list of players based on their swing performance.
