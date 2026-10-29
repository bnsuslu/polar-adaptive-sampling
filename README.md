# polar-adaptive-sampling
Comparing fixed and adaptive sampling strategies for temperature monitoring in polar regions, to balance energy consumption and data quality.
## Motivation
Automatic weather stations in polar regions have limited energy, because cold reduces battery capacity and there is no sunlight during the polar night. Measuring very often uses more energy, but measuring less often may miss rapid temperature changes.
## Research Question
Can changing the sampling frequency according to atmospheric variability achieve a better balance between energy consumption and data quality?
## Data
This project uses one-minute air temperature data from the Sodankyla station in Finland, which is openly available through FMI LITDB.
## Method
The one-minute data will be used as a reference, and fixed and adaptive sampling strategies will be simulated in Python to compare their measurement error. Energy consumption will be estimated with a simple energy model, including measurement, sleep mode, and data transmission.
## Status
Work in progress.
