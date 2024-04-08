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

## Purpose
The aim of this script is to provide a holistic evaluation of baseball players' swings by combining various performance metrics into a single score. This approach allows for a comprehensive comparison and ranking of players, highlighting those with superior swing mechanics.

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

## Results and Final Deliverables

## Key Findings
- **Outliers Identified**: Players like Matt Schuler and Colin Bergmann stood out with exceptional bat speeds, while Michael Gould and Michael Long demonstrated quick rotational abilities. Zach Liggett and Harry Oden excelled in on-plane efficiency, showcasing the diverse strengths within the team.
- **Algorithm-Based Ranking**: An algorithm was developed to rank players by analyzing key swing metrics including bat speed, rotational acceleration, and on-plane efficiency, alongside their standard deviations to reward consistency.
- **Top Performer**: Matt Schuler emerged as the standout player, ranking highest across significant metrics, emphasizing the importance of a consistent and powerful swing.

## Deliverables
- **Cleaned Dataset**: A CSV file containing the cleaned and prepared data, ready for analysis.
- **Algorithm Implementation**: Python script for calculating composite scores and ranking players based on their swing metrics.
- **Analysis Report**: Detailed documentation of the analysis process, findings, and visual data representations.

## Conclusion
Integrating technology with sports analytics provides profound insights into player performance, enabling targeted coaching and player development strategies. This project illustrates the potential of data-driven evaluations in baseball, presenting a scalable model for assessing player swings and fostering continuous improvement.

## Results 

![Code and Final Rankings](https://github.com/Quackman21/Capstone_Project/blob/main/Code%20w%20Results.png)






