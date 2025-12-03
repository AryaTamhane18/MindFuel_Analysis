Project Documentation:  

Data-source 1: Lifestyle Dataset 

Name/Title: Lifestyle Dataset 

URL/Link: https://www.kaggle.com/datasets/jockeroika/life-style-data 

Brief Description:  

This data set provides detailed information about the meals, cuisines, and their nutritional composition, representing dietary and lifestyle patterns along with the workout data on a personal level.  

 

Rows & Columns: 
- Exact Rows: 20,000 
- Exact Columns: 54 

Key Features: 

- Meal, Category, Cuisine, Diet types 

- Workout frequency, Workout types,  

-Calories, Protein, Carbs, Fat, Sugar, Fiber  

  

Data-source 2: Sleep Health and Lifestyle Dataset 

Name/Title: Sleep Health and Lifestyle Dataset 

URL/Link: https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset 

Brief Description: 
This dataset contains information about an individual's Sleep Patterns, Heart rate, BMI, Blood Pressure and Stress levels. It is used to understand the relationship between sleep quality, lifestyle behavior, and stress. 

Rows & Columns: 
- Exact Rows: 374 
- Exact Columns: 13 

Key Features: 
- Age, Gender, BMI, Sleep Duration, Quality of Sleep 
- Physical Activity Level, Stress Level, Sleep Disorder 
- Heart Rate, Daily Steps 
 
 
 
 

Dataset Linking 

These categories were used to merge both datasets into a single final data set containing 43 attributes from Workout habits, sleep health, dietary lifestyle information, and stress and 43 rows for each Age.  

Merge Basis 
Both datasets were merged on the Age column. Age was chosen because it contains a high number of unique values, allowing reliable alignment between individuals across the Sleep Health dataset and the Lifestyle Health dataset. Using Age as the merging key ensures that lifestyle, sleep behavior, and stress indicators correspond accurately to individuals with matching age profiles. 

Key Findings & Expectations 

We aim to study how eating habits, sleep behavior, and lifestyle patterns affect an individual's stress levels and overall mental well-being. We expect that sleep quality, sleep duration, calories, workout frequency, and balanced diets will correlate with levels of stress. 

Data Dictionary: Final Merged Dataset (43 Columns) 

- Age 
- Weight (kg)_mean 
- Height (m)_mean 
- Calories_Burned_mean 
- Water_Intake (liters)_mean 
- Workout_Frequency (days/week)_mean 
- BMI_mean 
- Physical exercise_mean 
- Carbs_mean 
- Proteins_mean 
- Fats_mean 
- Calories_mean 
- sugar_g_mean 
- sodium_mg_mean 
- cholesterol_mg_mean 
- Burns Calories (per 30 min)_mean 
- Sleep Duration_mean 
- Quality of Sleep_mean 
- Physical Activity Level_mean 
- Stress Level_mean 
- Heart Rate_mean 
- Daily Steps_mean 
- Gender_Male_pct 
- Gender_Female_pct 
- meal_type_Snack_pct 
- meal_type_Lunch_pct 
- meal_type_Breakfast_pct 
- meal_type_Dinner_pct 
- diet_type_Low-Carb_pct 
- diet_type_Vegan_pct 
- diet_type_Keto_pct 
- diet_type_Balanced_pct 
- diet_type_Paleo_pct 
- diet_type_Vegetarian_pct 
- cooking_method_Baked_pct 
- cooking_method_Boiled_pct 
- cooking_method_Raw_pct 
- cooking_method_Steamed_pct 
- cooking_method_Fried_pct 
- cooking_method_Roasted_pct 
- cooking_method_Grilled_pct 
- Sleep Disorder_Sleep Apnea_pct 
- Sleep Disorder_Insomnia_pct 
