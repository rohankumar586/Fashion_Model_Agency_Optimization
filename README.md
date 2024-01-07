# Fashion Model Agency Optimization - MGSC 662 Project

## Introduction
In collaboration with a team of four, we worked on a project aimed at developing an optimization model for assigning fashion models to jobs. The focus was to account for a variety of constraints and objectives pertinent to a modelling agency's operations.

## Project Description
- **Objective**: To ensure models are matched to jobs by considering a comprehensive set of constraints, such as location, CO2 emissions, model attributes, and client demands.
- **Features**: Our model strategically balances profitability, ethical considerations, diversity, and environmental impact.

## Technical Details
- **Constraints**:
  - Non-Conflicting Assignments: Avoiding double-booking models.
  - One Model Per Job: Limiting each job to one model.
  - One Job Per Model: Restricting models to a single job at a time.
  - Ethnicity Constraints: Matching models with client ethnicity preferences.
  - Age Category Preference: Aligning models with job age requirements.
- **Sensitivity Analysis**: We evaluated the influence of CO2 emission weights on our model's decision-making process.

## Results and Discussion
- **Model Performance**: Our model adeptly assigns models to jobs, maintaining a balance between agency profit and model compensation, while adhering to CO2 emission restrictions.
- **CO2 Emissions Sensitivity Analysis**: The analysis indicated a significant change in model-job assignments with varying CO2 emission weights, with a preference for local assignments to reduce emissions at higher weights.

