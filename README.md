# Binary autoencoders: a method for weighted sensor selection
## Abstract
### Background
Auto-encoders have the ability to automatically select relevant features by reconstructing signals from a lower dimensional space, therefore determining which information is relevant. On the other hand industrial systems are relying more on sensory data for state estimation. The cost of installing, maintaing, and loss of productivity due to sensors are not all equal. 
### Purpose
This work proposes a method of sensors selection based on the information provided by the sensor and the sensor-cost.
### Design
Using a simulation of signals we compare the sensor selection of a unit sensor-cost vector (assumes all sensors cost the same) and a designed sensor-cost vector. We create an artificial situation where the cost of two incomplete sensors is lower than the cost of a single sensor.
### Findings
As expected we determine that our model is able to select the appropriate sensor combination that reduces the system cost. 
### Practical implications
This work will ultimately aid in sensor selection for system design. These decision are not always that simple due to complex state-estimation.
### Research implications
This investigation is limited to sensor selection, but the technique is more generally applicable to feature selection.

## Keywords:
Machine learning; state-estimation; sensor-selection
