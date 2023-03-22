# Predicting failure of an oil & gas extraction equipment

The data used in this project was provided by [Shape digital](https://www.shapedigital.com/).

## How the equipment works

An FPSO is a floating production system that receives fluids (crude oil, water and a host of other things) from a subsea reservoir through risers, which then separate fluids into crude oil, natural gas, water and impurities within the topsides production facilities onboard. Crude oil stored in the storage tanks of the FPSO is offloaded onto shuttle tankers to go to market or for further refining onshore.

<img src="https://github.com/renatodiascosta/equipment_failure/blob/main/FPSO.jpg" 
     width="900" 
     height="450" />

## Describing the problem

The FPSO is monitored by sensors that measure different parameters of the equipment, such as temperature pressure etc. in different setup configurations. The setup configurations are represented by variables Preset_1 and preset_2. 

Our provlWe investigate one piece of equipment in different time cycles to understand what characteristics and parameters of the sensors might indicate that the equipment is on the verge of failing. 

## Defining tasks

Based on the given dataset, we set the following tasks:

1. Compute how often the equipment fails and compare it to how often it doesn't.
2. Categorize equipment failures by setup configurations.
3. Categorize equipment failures by their nature/root cause according to parameter readings (temperature, pressure, and others).
4. Create a model to predict equipment failule and measure its performance.
5. Analyze variable importance. 
