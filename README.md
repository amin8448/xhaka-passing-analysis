# Granit Xhaka's Passing Patterns and Network Analysis

## Project Overview

[cite_start]This project provides an in-depth analysis of Granit Xhaka's passing patterns and his role in Bayer Leverkusen's build-up play during their highly successful 2023-2024 season.  [cite_start]The analysis utilizes data from Statsbomb to examine passing networks, key passing metrics, and on-field pass locations to understand Xhaka's performance and contribution to the team. 

## Key Findings

- [cite_start]**Central Role in the Network**: Network graph analysis reveals that Xhaka is a central hub in Bayer Leverkusen's passing network, connecting frequently with his defensive partners.  This highlights his crucial role in initiating the team's build-up play.
- [cite_start]**Passing Metrics**: The analysis delves into key passing metrics such as goal assists, shot assists, and the expected goals (xG) value of the shots that result from his passes (`shot_statsbomb_xg`). 
- **Low Conversion of Shot Assists**: A key insight is that while Xhaka generates a high number of passes that lead to shots (shot assists), these opportunities have a low probability of being converted into goals. This could be attributed to several factors, including the quality of the pass, the receiver's position, or the defensive pressure faced by the receiver.
- **Heatmap Analysis**: A heatmap of Xhaka's pass start locations shows his activity is primarily concentrated in the central area of the pitch, with a tendency to favor his left side when distributing the ball.

## Data Source

[cite_start]The analysis is based on open data provided by **Statsbomb**.  The data specifically focuses on pass events from the Bundesliga 2023-2024 season.

## Getting Started

To run the analysis yourself, follow these steps:

### Prerequisites

Make sure you have Python installed on your system. You will also need the following libraries:

- `pandas`
- `statsbombpy`
- `matplotlib`
- `seaborn`
- `networkx`
- `mplsoccer`

### Installation

You can install the required libraries using pip:

```bash
pip install pandas statsbombpy matplotlib seaborn networkx mplsoccer
```

### Usage

1.  Clone this repository to your local machine.
2.  Open the Jupyter Notebook `The athletics Interview.ipynb` using Jupyter Notebook or JupyterLab.
3.  Run the cells in the notebook sequentially to execute the analysis and generate the visualizations.

## Project Files

- **`Granit Xhaka’s Passing Patterns and Network.pdf`**: The detailed report of the analysis, including interpretations and conclusions.
- **`The athletics Interview.ipynb`**: The Jupyter Notebook containing the Python code used for data fetching, analysis, and visualization.