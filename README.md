# Granit Xhaka: Passing Network & Performance Analysis (2023-24)

### Introduction

This project provides a thorough examination of Granit Xhaka's passing patterns and network analysis to understand his pivotal role in Bayer Leverkusen's historic undefeated 2023-2024 season. The analysis uses open data from Statsbomb to quantify his contributions to the team's build-up play and chance creation.

> The goal is to move beyond subjective observation and use empirical data to assess Xhaka's effectiveness as a central midfielder, quantifying his impact on game outcomes.

---

### Key Visualizations

<table>
  <tr>
    <td align="center"><strong>Team Passing Network</strong><br><em>Shows Xhaka as the central hub of the team.</em></td>
    <td align="center"><strong>Xhaka's Passing Distribution</strong><br><em>Illustrates his diverse connections across the pitch.</em></td>
  </tr>
  <tr>
    <td><img src="figure 1.jpg" alt="Team Passing Network Analysis" width="100%"></td>
    <td><img src="figure 2.jpg" alt="Xhaka's Passing Network" width="100%"></td>
  </tr>
  <tr>
    <td align="center"><strong>Key Pass Locations</strong><br><em>Highlights his role in the build-up and final third.</em></td>
    <td align="center"><strong>Passing Heatmap</strong><br><em>Visualizes his primary zones of operation.</em></td>
  </tr>
  <tr>
    <td><img src="figure 3.jpg" alt="Key Pass Locations" width="100%"></td>
    <td><img src="figure 4.jpg" alt="Passing Heatmap" width="100%"></td>
  </tr>
</table>

---

### Key Findings

* **Central Hub of the Network:** The network graphs clearly illustrate that Granit Xhaka functions as the central hub in Bayer Leverkusen's passing network, connecting defense, midfield, and attack. His positioning and high volume of connections are pivotal to the team's ball circulation and tempo.
* **Versatile Playmaker:** Xhaka demonstrates incredible versatility, capable of switching play, initiating forward attacks, or recycling possession as needed. His connections are well-distributed to teammates in all areas of the pitch.
* **Build-up Specialist:** While he makes a significant number of key passes, his primary role is centered on ball transition and progressing play into the final third, rather than delivering the final assist. The data shows a low expected assists (xA) value, suggesting his key passes create opportunities that precede the final shot.
* **Zone of Influence:** The heatmap confirms his activity is concentrated in the central midfield, with a notable tendency to operate from and pass through the left side of the pitch.

---

### Tech Stack

* **Python 3.x**
* **Libraries:** pandas, NumPy, Matplotlib, Seaborn, NetworkX
* **Football-Specific Libraries:** `statsbombpy` (for data access), `mplsoccer` (for pitch visualization)

---

### Setup and Installation

To replicate this analysis, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/amin8448/xhaka-passing-analysis.git](https://github.com/amin8448/xhaka-passing-analysis.git)
    cd xhaka-passing-analysis
    ```

2.  **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the analysis:**
    * The primary analysis is contained within the Jupyter Notebook `analysis.ipynb`. Open and run the cells to reproduce the findings and visualizations.

---

### Data Source

The data used for this project is the open data provided by [**Statsbomb**](https://statsbomb.com/what-we-do/open-data/). It was accessed programmatically using the `statsbombpy` Python package.

---

### License

This project is licensed under the MIT License. See the `LICENSE` file for details.
