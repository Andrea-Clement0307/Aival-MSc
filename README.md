# Aival_MSc
This project focuses on optimizing radiologist scheduling in healthcare departments using a combination of optimization techniques and machine learning models. Managing radiologists' schedules is a complex task, given the need to balance operational efficiency, staff preferences, and various constraints related to both the department and individual radiologists. This repository addresses these challenges by employing Mixed-Integer Linear Programming (MILP) for scheduling optimization and ensemble machine learning models for predicting radiologists' work location preferences.

Key Aspects of the Project:
MILP for Scheduling Optimization: The MILP model is designed to allocate workspaces and scan assignments in a way that balances radiologists’ preferences with operational demands. It ensures that the right number of radiologists are scheduled for each shift, taking into account factors such as availability, preferences, and department capacity.

Data Simulation: Due to regulatory constraints and data privacy concerns, the project utilizes synthetic data that emulates real-world scheduling scenarios in radiology departments. This simulated data helps in generating realistic input for both the MILP model and the machine learning models, allowing for testing and validation of the scheduling system.

Predictive Modeling Using Machine Learning: The machine learning models are trained on historical, simulated scheduling data to predict radiologists' work location preferences. These models, which include ensemble methods like Random Forest, Gradient Boosting, and Stacking, provide valuable insights into radiologists' likely preferences for working locations (e.g., home vs. office), improving the scheduling process.

Goals and Benefits:
Operational Efficiency: By optimizing the allocation of radiologists to different shifts and workstations, the system reduces operational inefficiencies such as overstaffing or understaffing, ensuring that the department operates smoothly.
Staff Satisfaction: The incorporation of radiologists' preferences into the scheduling model helps improve job satisfaction by aligning work assignments with individual preferences, reducing potential burnout and turnover.
Automation: The combination of predictive modeling and optimization enables an automated scheduling system that minimizes administrative workload while adapting to changing circumstances, such as last-minute availability changes or urgent scan requests.
This project provides a strong foundation for optimizing radiologist scheduling through the use of both advanced optimization techniques and machine learning models. It has the potential to be further developed into a dynamic scheduling system that integrates real-time data, ultimately benefiting healthcare operations and workforce management.
