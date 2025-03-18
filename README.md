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

      • Download the Power BI report titled CO2 Emissions by Vehicle and open it in Power BI Desktop.

# Step 2: Identify Key Influencers of CO2 Emissions

      • Go to the Data view in Power BI and select the Vehicles table. Focus on the CO2 emissions column, along with other attributes like Transmission, Engine Size (cm3), Fuel Type, and 
      
        Powertrain, which could explain variations in CO2 emissions.

![image_alt](https://github.com/DSgenes/Root-Cause-Analysis-RCA/blob/e8ef06855391bfb43dc31d2d4202afd3f4941d36/Screenshot%201.png)

# Step 3: Report Creation

  1. Add a Card visual, using the car_id column with the Count function to represent the number of vehicles. Rename it to Vehicles Analyzed.

  2. Select the Key Influencers visual from the Visualizations pane.

  3. Drag CO2 Emission into the Analyze field and other relevant attributes (except car_id) into the Explain by field.

  4. Analyze the key influencers displayed by the visual.

![image_alt](https://github.com/DSgenes/Root-Cause-Analysis-RCA/blob/ea429e6a231f78fda6afde536c6c434a6ef6eba1/Screenshot%202.png)

  5. Create Scatter Plot

     • Observe the scatter plot showing the relationship between Engine Size (cm³) and the Average CO2 Emission in the generated visualizations.

     • Recreate this plot in your report by selecting a Scatter Plot visual.

     • Add Engine Size (cm³) to the X-axis and CO2 Emission to the Y-axis.

     • Change the default Sum of CO2 Emission on the Y-axis to Average by clicking the down arrow next to the field.

![image_alt](https://github.com/DSgenes/Root-Cause-Analysis-RCA/blob/58e18e50319587a902ce81ed33d04ad7bf431f2c/Screenshot%203.png)

# Step 4: Use Top Segments Tool

   1. Go to the Top Segments tool, located as the second tab at the top of the visualization.

   2. Explore the top segments to identify the main attribute groups affecting CO2 emissions.

![image_alt](https://github.com/DSgenes/Root-Cause-Analysis-RCA/blob/fd15e23ffa53f1afbf31c052b5a3d8afb1301c89/Screenshot%204.png)

   3. Observe that Sum of Engine Size is a segment on its own, significantly influencing CO2 emissions, reinforcing the importance of the scatter plot from the previous step.

![image_alt]()

   4. In the remaining segments, observe that besides the previously visualized fields, Powertrain and Transmission combined are also key factors influencing CO2 emissions.

![image_alt]()

  5. Create a new visualization to highlight the relationship between Powertrain, Transmission, and CO2 Emissions.

     Place Powertrain on the Y-axis (due to its higher cardinality) and Transmission in the Legend.

![image_alt]()

 Include Fuel Type in the Report

  6. Add the Fuel Type field to the report.

     • Identify the top three fuel types that contribute to over 90% of CO2 emissions.

     • Use a Pie or Donut chart to visualize the distribution of these fuel types.

![image_alt]()

# Step 5: Build a Decomposition Tree with AI Capabilities

   1. Click the + symbol at the bottom of the canvas to add a new page to your report.Select the Decomposition Tree visualization from the Visualizations pane and adjust the visual to fill
     
      the screen.

   2. Add the Average of CO2 Emission to the Analyze field and relevant attributes to the Explain by field.

![image_alt]()

   3. Expand all attributes in the decomposition tree by clicking the + symbol on the right side of each bar. Note that Engine Size (cm³), due to its high cardinality, cannot be
   
      effectively visualized in the tree.

   4. Right-click the Engine Size (cm³) column and select New Group to group the data into five equal-sized bins. Remove the ungrouped Engine Size (cm³) column and add the newly created

      bins to the chart.

![image_alt]()

   5. Close all previously opened tabs in the decomposition tree visualization.

     • Use Powertrain as the first hierarchy selection and select Low value for the remaining attributes.

     • Leverage the AI functionality to identify the lowest average CO2 emission for vehicles with Powertrain: Hybrid Electric Vehicle (HEV).

![image_alt]()

# Summary
   
   In this exercise, you learned how to create an effective report by utilizing specialized Power BI visualizations like key influencers and decomposition trees to uncover meaningful 
   
   patterns in data. By harnessing the power of AI-driven visuals, you built a detailed report that illustrates the connection between vehicle attributes and CO2 emissions, providing a 
   
   clear understanding of their impact on air pollution.

