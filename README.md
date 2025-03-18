# Root-Cause-Analysis-RCA

# Case study

Environmental issues are on everyone's mind, and vehicle CO2 emissions stand out as a major contributor. A dataset filled with raw data about CO2 emissions per vehicle holds a wealth of valuable insights waiting to be uncovered through data 

analytics. In this case study, you’ll focus on a targeted investigation: using root cause analysis to identify the vehicle attributes that have the greatest impact on air pollution. 

To do this, you will have to:

   • Identify the key vehicle attributes that have the most impact on CO2 emissions in the environment.

   • Identify the major contributors to pollution through a perceptive root cause analysis, leveraging the AI-driven visualizations of Power BI. 

   • Create relevant visualizations to enrich your report, including a decomposition tree, allowing users to freely explore and navigate the dataset's values.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Step 1: Download the Report

     Download the Power BI report titled CO2 Emissions by Vehicle and open it in Power BI Desktop.

# Step 2: Identify Key Influencers of CO2 Emissions

     Go to the Data view in Power BI and select the Vehicles table. Focus on the CO2 emissions column, along with other attributes like Transmission, Engine Size (cm3), Fuel Type, and Powertrain, which could explain variations in CO2 
     
     emissions.

# Step 3: Report Creation

  1. Add a Card visual, using the car_id column with the Count function to represent the number of vehicles. Rename it to Vehicles Analyzed.

  2. Select the Key Influencers visual from the Visualizations pane.

  3. Drag CO2 Emission into the Analyze field and other relevant attributes (except car_id) into the Explain by field.

  4. Analyze the key influencers displayed by the visual.
