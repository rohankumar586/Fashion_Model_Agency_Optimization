# Fashion Model Agency Optimization - MGSC 662 Project

## Introduction
In the fast-paced world of fashion, aligning the right models with the right jobs is a complex challenge. My project, Sustainable Model Assignment Optimization, elevates this process by not only streamlining job assignments but also embedding a deep commitment to sustainability. The focus was to account for a variety of constraints and objectives pertinent to a modelling agency's operations.

## The Challenge
Fashion model agencies often face the dual challenge of efficiently assigning models to various jobs while considering the environmental impact of their travel. The traditional approach has largely overlooked the sustainability aspect, leading to increased carbon footprints. My objective was to create a solution that addresses both efficiency and environmental responsibility.

## The Solution: A Dual-Focused Optimization Model
The core of this project is an optimization model that achieves two key goals:

- **Efficient Model Assignment**: Ensuring models are assigned to jobs that match the client's requirements, maximizing job success and satisfaction.
- **Sustainability Consideration**: Integrating a sensitivity analysis of CO2 emissions associated with model travel, promoting environmentally conscious decisions.

## How It Works

- **Optimization Algorithm**: The model uses Gurobi to evaluate various factors such as model availability, job requirements, and travel distances.
- **CO2 Emissions Analysis**: A unique aspect is the inclusion of a CO2 emission calculator. This tool estimates the environmental impact based on travel distance and mode of transportation.
- **Sensitivity Analysis for Sustainability**: Agencies are provided with a sensitivity analysis regarding CO2 emissions. This allows them to decide how much weight to give to sustainability in their assignment decisions, aligning with their environmental goals.

## Sensitivity Analysis
Heres how we can observe how the job assignment changes as emission weight increases
![Emission Weight 0](https://github.com/rohankumar586/Fashion_Model_Agency_Optimization/assets/142628516/1fdbbab4-0a49-40fd-8d34-cf76e0bc7e31)
![Emission Weight 30](https://github.com/rohankumar586/Fashion_Model_Agency_Optimization/assets/142628516/97df27ee-c346-44c1-9bf6-b80c3300ee32)
Below graph shows how the profits change as emission weight increases
![Sensivity Analysis](https://github.com/rohankumar586/Fashion_Model_Agency_Optimization/assets/142628516/89b3a9e7-3c34-47fc-a2eb-3e2153a051b9)

## The Impact
This model revolutionizes the way fashion agencies assign models by:

- **Enhancing Operational Efficiency**: Streamlining the assignment process, ensuring the right fit between models and jobs.
- **Promoting Environmental Sustainability**: Empowering agencies to make informed decisions that reduce their carbon footprint.

## Conclusion
The Sustainable Model Assignment Optimization project showcases how operational efficiency can be harmoniously blended with environmental stewardship. It's a step towards more responsible and sustainable practices in the fashion industry, demonstrating the pivotal role of data analytics in achieving this balance.

## Technical Details
- **Constraints**:
  - Non-Conflicting Assignments: Avoiding double-booking models.
  - One Model Per Job: Limiting each job to one model.
  - One Job Per Model: Restricting models to a single job at a time.
  - Ethnicity Constraints: Matching models with client ethnicity preferences.
  - Age Category Preference: Aligning models with job age requirements.
  - Evaluated the influence of CO2 emission weights on our model's decision-making process.

## Results and Discussion
- **Model Performance**: Our model adeptly assigns models to jobs, maintaining a balance between agency profit and model compensation, while adhering to CO2 emission restrictions.
- **CO2 Emissions Sensitivity Analysis**: The analysis indicated a significant change in model-job assignments with varying CO2 emission weights, with a preference for local assignments to reduce emissions at higher weights.

## Acknowledgments
- This project was a part of a course at McGill University. Thanks to the course instructors and fellow students for their support and guidance.
