GymFlow: Smart Structural Monitoring System
Civil Engineering Project
Developed using MATLAB App Designer
Developer: Talasia (Juno) Weathersby  
University: Morgan State University
---
Project Overview
GymFlow is a MATLAB-based structural monitoring application designed to simulate floor vibration analysis in high-activity environments such as gyms.
The system collects vibration data, analyzes structural conditions, calculates risk levels, identifies high-activity zones, and generates engineering recommendations.
The goal of GymFlow is to demonstrate how engineering data analysis can support safer building monitoring systems.
---
Problem Statement
Gyms experience repeated dynamic loading caused by:
Heavy exercise equipment
Foot traffic
Jumping activities
High-use workout areas
Continuous vibration can affect structural performance over time.
GymFlow provides a prototype solution for monitoring these conditions and identifying possible areas of concern.
---
Features
Live Vibration Monitoring
Real-time vibration simulation
Live vibration graph
Current vibration readings
Live structural status updates
---
Structural Analysis
The application analyzes vibration data and calculates:
Peak vibration
Average vibration
Structural condition
Safety classification
---
Risk Assessment
GymFlow generates a risk score based on vibration measurements.
Possible results:
Safe
Moderate Risk
Potentially Unsafe
---
Zone Analysis
The application identifies areas with increased vibration activity.
This helps determine locations that may require additional inspection.
---
Engineering Recommendation
After analysis, GymFlow provides an engineering recommendation based on the calculated results.
---
Automatic Report Generation
The system creates an engineering summary report containing:
Vibration measurements
Risk score
Structural status
Recommendations
---
Software Requirements
Required Software
MATLAB
MATLAB App Designer
Recommended MATLAB version:
R2024a or newer
---
Project Files
The GymFlow project contains the following files:
GYMFLOW-
|└──GymFlow.mlapp
|└──Main MATLAB App Designer interface
|
|DATA
│ └floor_vibration_acceleration.mat
│ └── Vibration dataset used for structural analysis
│
├── Scripts
│ ├── analysis.m
│ ├── reportGeneration.m
│ └── zoneAnalysis.m
│
├── Reports
│ └── Generated engineering reports
│
└── README.md
└── Project documentation


# How To Run

## Step 1
Open MATLAB.

## Step 2
Navigate to the GymFlow project folder.

Example:
C:\GYMFLOW

## Step 3
Make sure the vibration data file is available:
DATA/floor_vibration_acceleration.mat


## Step 4
Open:
GymFlow.mlapp


## Step 5
Press Run.
---------------------------------------------------------------------------------------------------------------------------------------
# Application Workflow
1. Start Live Monitoring
The application begins collecting simulated vibration data.

2. Run Analysis
The system processes vibration measurements and evaluates structural conditions.

3. Review Results
The user can view:

- Analysis graph
- Risk score
- Safety status
- Zone information

4. Generate Report
The system creates an engineering summary.
----------------------------------------------------------------------------------------------------------------------------------------

# Technologies Used

- MATLAB
- MATLAB App Designer
- Data Visualization
- Engineering Data Analysis
- Structural Monitoring Concepts

----------------------------------------------------------------------------------------------------------------------------------------

# Future Improvements

Possible future upgrades:

- Real vibration sensors
- IoT monitoring system
- Cloud-based data storage
- Machine learning prediction models
- Real-time building monitoring

------------------------------------------------------------------------------------------------------------------------------------------

# Project Results

GymFlow successfully demonstrates:

✓ Interactive MATLAB interface
✓ Live monitoring simulation
✓ Structural analysis
✓ Risk evaluation
✓ Engineering reporting

The project shows how programming and engineering principles can be combined to improve structural safety monitoring.

----------------------------------------------------------------------------------------------------------------------------------------

# talasiasmith07@gmail.com

Developer:
Talasia (Juno) Weathersby
