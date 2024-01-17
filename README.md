# Main objective

The goal of this project is to use data together with different modelling techniques, to analyse the behaviour of a wastewater pumping station. The project is carried out doing the three-week special course "Industrial IoT for Digitization of Electronic Assets" at DTU, from January 2. to January 19.
The repository is divided into five modules and one final project. The modules lay the groundwork for the final project and include snippets of everything used in the analysis.

# Modules
Modules one and two focus on establishing a connection between various devices. PC, PLC, and cloud computing are connected in a IoT configuration. The next three are about Kalman filters for inflow estimation and model parameter estimation via ARX and neural network, and Model Predictive control for optimizing control patterns.

# Final Project
The last part of the course is dedicated to a final project. We have chosen to focus on track B and build a digital twin of the wastewater pumping station.

The principle steps are as follows:
- Chose a part of the provided dataset given to us.
- Make a static model from simple regression on the data
- Expand the model to include more of the dynamics of the system, this will be done with ARX and ML
- Data analysis and visualisation
- Evaluate the Digital Twin's performance
- Use the model to predict future
- Show forecasted values online with Grafana
