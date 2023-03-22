# Predicting failure of an oil & gas extraction equipment

The data in this repository is based on a real case scenario and was provided by [Shape digital](https://www.shapedigital.com/).

## How the equipment works

An FPSO (Floating Production Storage and Offloading) is a floating production system that receives fluids (crude oil, water and a host of other things) from a subsea reservoir through risers, which then separate fluids into crude oil, natural gas, water and impurities within the topsides production facilities onboard. Crude oil stored in the storage tanks of the FPSO is offloaded onto shuttle tankers to go to market or for further refining onshore.

![](https://github.com/renatodiascosta/equipment_failure/blob/main/FPSO.jpg)

## Describing the problem

In order to avoid equipment failure, the FPSO is monitored by sensors measuring different parameters, such as temperature, pressure, vibration and frequency, in different setup configurations.

The setup configuration are encoded by two variables, namely ```Preset_1``` and ```Preset_2```, while the measured parameters are ```Temperature```, ```Pressure```, ```VibrationX```, ```VibrationY```, ```VibrationZ``` and ```Frequency```.

Our problem is to investigate one piece of equipment in different time cycles to understand what setup configurations and parameters of the sensors might indicate that the equipment is on the verge of failing. 

## Defining tasks

Based on the given dataset, we set the following tasks:

1. Compute how often the equipment fails and compare it to how often it doesn't.
2. Categorize equipment failures by setup configurations.
3. Categorize equipment failures by their nature/root cause according to parameter readings (temperature, pressure, and others).
4. Create a model to predict equipment failule and measure its performance.
5. Analyze variable importance. 

We address each task seperately and conclude with some final remarks.
