# Diet-Planner-ML-module
[Application](https://github.com/RiSiNgFuRy/AI-Diet-Planner-App)
- The ML module incorporates the concept of Basal Metabolic Rate (**BMR**) to determine the required calorie intake.
- By considering factors such as age, gender, height, and weight, BMR is calculated to estimate daily calorie needs.
- The user's goal, such as weight loss, gain or maintenance, determines the target calorie intake.
- Based on this goal, the ML module generates personalized food recommendations.

## Module 
- **Components Used in ML Module**
  - It utilizes libraries such as **pandas** and **numpy** for data manipulation and analysis.
  - The **randomForestClassifier** algorithm is employed for classification tasks.
  - The **kmeans** algorithm is utilized for clustering purposes.
  
- **Data for ML Module Training**
  - Two datasets, namely food.csv and nutrition_distribution.csv, serve as the training data for the ML module.
  - These datasets are used to train the machine learning model and obtain desired outputs.

- **Inputs for ML Module**
  - The ML module takes various inputs:
    1. Gender (Male or Female)
    2. Age (in years)
    3. Height (in cm)
    5. Weight (in kg)
    6. Goal (Weight Loss, Healthy or Weight Gain)
    7. Food Preferences (Veg or Non-Veg)
