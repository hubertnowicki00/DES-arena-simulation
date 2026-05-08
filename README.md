# Discrete Event Simulation in Arena Software (.doe)

This repository contains an Arena file with custom built DES simulation project, full report in .pdf and Python file visualizing results saved in MS Excel. Said project was part of my University's curriculum and done as a group project with my friend - Bartosz Szofer.

##  Key Features

- **Custom Middle-earth Themed DES Model**: A complex queueing system simulating the journey, outfitting, and consultation of heroes, featuring iconic nodes and resources like Aragorn's Consultation, Hobbit Bakers, Elven Stylists, and Blacksmiths
- **Scenario Analysis & System Optimization**: Implementation of specific capacity and efficiency upgrades, such as:
    1) Doubling M.U.L.E. availability to 4 (with horses from Rohan)
    2) Increasing travel speed by 50% (utilizing mithril armor and Lembas bread)
    3) Tripling Gandalf's guiding capacity (fueled by Shire pipe-weed and Miruvor)
    4) Expanding blacksmith capacity with additional help from Rivendell
- **Bottleneck Identification**: Deep-dive analysis comparing discrete-time statistics (e.g., queue waiting times) and continuous-time statistics (e.g., resource utilization) to track how constraints shift through the system after upgrades
- **Automated Result Visualization**: Python scripts leveraging pandas, matplotlib, and seaborn to parse Arena's .xlsm output reports (AcrossReplicationsSummary) and generate insightful charts with 95% confidence intervals (Half-Widths)


## Tech stack and methodology
1) Environment: **Arena Simulation Software**, **Python** (for data extraction and visualization)
2) Input/Output data: Simulation logs exported to MS Excel (.xlsm) format, specifically utilizing the AcrossReplicationsSummary reports to evaluate average system behaviors and variances over multiple simulation runs.

# Repository contents
1) [DES_MiddleEarth.doe](DES_MiddleEarth.doe) - main Arena Software file with full simulation project
2) [DES_report.pdf](DES_report.pdf) - full report on simulation's working principles and obtained results
3) [results_visualization.ipynb](results_visualization.ipynb) - Python script in Jupyter Notebook environment with code used for plotting
