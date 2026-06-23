# Match Analysis – 2018 FIFA World Cup Final

In this project, I analyzed the 2018 FIFA World Cup Final (France vs. Croatia) using StatsBomb data.

This notebook was developed from the perspective of an undergraduate university student and serves as an exploratory match analysis study.

The main idea is to examine the match not only through the final score but also through the distribution of on-field actions and player involvement throughout the game.

## Features

* Player touch density heatmaps
* Team-based passing density maps
* Team-based shot maps (goals and non-goals visualized separately)
* Pass network analysis

The notebook includes visualizations for the following players and teams:

* Paul Pogba (France)
* Luka Modrić (Croatia)
* France team analysis
* Croatia team analysis

## Libraries Used

* numpy
* pandas
* matplotlib
* scipy
* statsbombpy
* mplsoccer

## Installation

1. Python 3.10+ is recommended.
2. Install the required packages:

```bash
pip install numpy pandas matplotlib scipy statsbombpy mplsoccer
```

## How to Run

1. Open the `Match_Analysis.ipynb` notebook.
2. Run the cells sequentially from top to bottom.
3. Since the data is fetched online, make sure you have an active internet connection.

## Data Source

This project uses the open StatsBomb dataset accessed through the `statsbombpy` library.

## Note

This study was prepared as an undergraduate-level football match analysis project.

The goal is not to build advanced predictive models, but rather to make the flow of the game easier to understand through visualizations of action locations, player involvement, and team dynamics.

## License

This repository is distributed under the MIT License.
