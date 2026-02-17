# HealthCare-Analytics

**Dataset Information**

The Healthcare Data CSV sheet contains 768 rows and 9 columns namely 

1)ID  2)Age  3)Blood Pressure Systolic  4)BMI  5)Diabetes Pedigree Function  6)Glucose  7)Insulin  8)Outcome  9)Skin Thickness

**Guidelines**

Use Healthcare Data.csv data from kaggle. Note that either Tableau Public or Desktop can be used to find the answers. If you are using Tableau Desktop, the healthcare dataset should be present in the Saved Data sources and will also be present in My Tableau Repository folder on local machine. Data should be an Extract and not a ‘Live’ connection.

**Tableau Project Requirement**

The workbook have two dashboards. The Workbook  also have a Story consisting of several Story points based on the requirement. Each worksheet/view/chart should meet the business requirement. All worksheets are hidden. Workbook can be published to Tableau Public if possible.

**Business Requirement**

Connect to the CSV file Healthcare dataset, which includes the data regarding patients’ blood pressure, BMI, glucose, insulin, and diabetes for patients from the 20+ age group. I have build 2 dashboards and then create a story using the 2 dashboards and a worksheet.

**Dashboard 1 Requirements**

I have taken an image regarding healthcare and drag it to the dashboard. Using Text object, give it a meaningful name based on my data analysis of the file.

**Dashboard 2 Requirements**

**View 1: Diabetic/Non-diabetic using Shapes**

Use Shapes to show the distribution between diabetic/non-diabetic patients. Using the “Outcome” field, written a calculated field by classifying 1 as Diabetic patients and 0 as Non-diabetic patients. Showing the percent distribution as shown in the expected view. Using the color of my choice to differentiate Diabetic Vs. Non-diabetic patients. Tooltip also display patient count. I have used shapes of my choice or use any one and then Format as per my choice. Enable Action filters.

**View 2: Patient summary by Blood Pressure category**

I have used shape of my choice to show patient summary by blood pressure category. Showing the Patient count and BP category type on the labels. By Using the color of my choice, I can  differentiate Diabetic Vs. Non-diabetic patients easily. Format as per my choice. Enable Action filters.

**View 3: Create a Histogram to show Body Mass Index (BMI) by Age Groups.**

Since I have build a Histogram, using the Age field, let’s create bins using size 5. In a Histogram, I will have bins 20, 25, 30, etc. So, the bin size 20 will include age groups between 20-24, and size 25 will include 25-29. So, to be clear i have edit the aliases of the age groups as it might confuse the users. So, by using aliases as shown below or I can create a calculated field for the Age groups. In case, there are missing values, hide them. Display the average BMI value on top of each bar and round it to 2 decimals. Using the average BMI to color the palette using shades of Red.

**View 4: Single Bar showing percent distribution of patients by BMI type**

Create a calculated field to classify Patients by BMI types. [BMI]<18.5= 'Underweight' [BMI]>=18.5 and [BMI]<25 ='Healthy Weight' [BMI]>=25 and [BMI]<30 = 'Overweight' [BMI]>=30 ='Obese' Enable Action filters.

**View 5: Bar Chart showing Patient break down by Blood Pressure and Diabetes**

Create a calculated field to only highlight Diabetic patients with High and Low blood pressures.

**View 6: Build a HEAT MAP showing several health factors by Age group**

**Story Requirements**

Story Name: Healthcare    |     Story Title: Healthcare Summary Report
Story description: Added one  to Story size: Custom Size (best choice) Story Layout: Set the Navigator style to Numbers.
Story Point 1: It contain Dashboard 1
Story Point 2: It contain Dashboard 2 Story
Story Point 3: It contain Heat Map Worksheet

**Instructions on how to run this project code on your system**

Step 1 : Download this project repository as a zip file.

Step 2 : Unzip the folder to your desired location.

Step 3 : If you don't have Tableau Public Installed , go to https://www.tableau.com/products/public/download, download the installer, install Tableau public and launch it. 

Step 4 : Navigate to this project folder.

Step 5 : When inside navigate to Healthcare. 

Step 6 : Open the Capstone Project 1.twbx using Tableau Public. 

Step 7 : Go through the Tableau Project Requirements mentioned above and compare the visuals in the Tableau Workbook accordingly.

**Purpose of Making this Dashboards**

Analyzing patient healthcare data such as blood pressure, BMI, glucose levels, insulin, and diabetes for patients aged 20+ using Tableau can serve numerous critical purposes in healthcare management, prevention, and policy formulation. Tableau's data visualization capabilities help uncover insights that can improve patient outcomes and resource allocation. Here are some key purposes:

**1. Monitoring Patient Health Trends**

Chronic Disease Trends: Identify the prevalence of diabetes, hypertension, and obesity in the 20+ age group. Risk Factors: Analyze correlations between BMI, glucose, insulin levels, and the likelihood of developing chronic conditions. Population Health Metrics: Understand the average health parameters of the population to benchmark against health standards.

**2. Early Disease Detection and Prevention**

High-Risk Groups: Detect individuals or subgroups with abnormal blood pressure, glucose, or insulin levels to target preventive measures. Warning Signs: Visualize trends that indicate worsening conditions, such as rising BMI or increasing glucose levels over time. Screening Effectiveness: Evaluate how well screening programs are identifying at-risk patients.

**3. Tailoring Patient Care Plans**

Personalized Interventions: Segment patients based on their health metrics to recommend tailored lifestyle changes, diets, or treatments. Treatment Outcomes: Assess how interventions (e.g., insulin therapy or weight management programs) impact specific metrics like glucose or BMI.

**4. Resource Allocation and Planning**

Healthcare Demand: Predict resource needs, such as insulin supplies or hypertension management programs, based on patient data trends. Facility Utilization: Identify regions or populations with higher healthcare needs to allocate resources effectively. Program Prioritization: Focus on age groups or demographics with the most critical health challenges.

**5. Understanding Demographic Variations**

Age-Specific Trends: Explore how health metrics differ within subgroups (e.g., patients in their 20s vs. 40s). Gender Differences: Examine how conditions like diabetes or hypertension vary between males and females. Regional Insights: Identify geographic hotspots for specific conditions to target interventions.

**6. Public Health Policy Development**

Preventive Campaigns: Use insights to design campaigns addressing obesity, diabetes, or hypertension. Health Equity: Identify disparities in health metrics across socioeconomic or ethnic groups. Community Health Goals: Set measurable objectives based on analyzed trends.

**7. Enhancing Clinical Research**

Hypothesis Generation: Identify patterns or anomalies that warrant further investigation in clinical studies. Drug Efficacy: Analyze data to evaluate the effectiveness of medications or lifestyle interventions in managing blood pressure, glucose, and insulin.

**8. Improving Patient Engagement**

Visual Health Dashboards: Create interactive dashboards that patients can view to understand their health metrics and progress. Education: Help patients see how changes in lifestyle affect metrics like BMI or glucose levels.

**Why Tableau for This Analysis?**

Interactive Dashboards: Enable healthcare professionals to drill down into specific patient groups or metrics. Cross-Filtering: Correlate metrics like glucose and insulin to uncover complex health relationships. Data Integration: Combine data from multiple sources (e.g., lab results, patient history) for comprehensive insights. Custom Alerts: Highlight patients or metrics outside normal ranges. Geospatial Analysis: Map health trends by region to visualize geographic disparities.

**Outcome**

Analyzing patient healthcare data in Tableau can lead to better chronic disease management, informed healthcare policies, efficient resource allocation, and improved individual and population health outcomes. It ensures healthcare providers and policymakers can act proactively rather than reactively, improving overall quality of care.
