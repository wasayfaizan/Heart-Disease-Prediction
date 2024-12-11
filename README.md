
  <header>
        <h1>Heart Disease Prediction Project</h1>
    </header>
    
  <div class="container">
        <h2>Project Description</h2>
        <p>This project analyzes a comprehensive dataset related to heart disease risk factors sourced from the Centers for Disease Control and Prevention (CDC). The dataset includes survey data from over 400,000 adults collected in 2022, focusing on key indicators associated with heart disease prevalence. The goal is to predict the likelihood of heart disease based on demographic and health-related variables.</p>

<h2>Dataset Attributes</h2>
        <p>The dataset includes the following attributes:</p>
        <ul>
            <li><strong>Age</strong>: Age of the respondent</li>
            <li><strong>Gender</strong>: Gender of the respondent</li>
            <li><strong>Race</strong>: Race of the respondent</li>
            <li><strong>HighBloodPressure</strong>: Presence of high blood pressure (binary: "Yes" or "No")</li>
            <li><strong>HighCholesterol</strong>: Presence of high cholesterol (binary: "Yes" or "No")</li>
            <li><strong>SmokingStatus</strong>: Smoking status of the respondent</li>
            <li><strong>DiabetesStatus</strong>: Diabetes status of the respondent</li>
            <li><strong>Obesity</strong>: Obesity status of the respondent (measured by BMI)</li>
            <li><strong>PhysicalActivity</strong>: Level of physical activity</li>
            <li><strong>AlcoholConsumption</strong>: Level of alcohol consumption</li>
            <li><strong>OtherMedicalConditions</strong>: Presence of other medical conditions</li>
            <li><strong>FamilyHistory</strong>: Family history of heart disease (binary: "Yes" or "No")</li>
            <li><strong>MedicationUsage</strong>: Usage of medications for heart disease or related conditions</li>
            <li><strong>StressLevel</strong>: Level of stress reported by the respondent</li>
            <li><strong>Diet</strong>: Dietary habits of the respondent</li>
            <li><strong>ExerciseRoutine</strong>: Regularity of exercise routines</li>
            <li><strong>SleepQuality</strong>: Quality of sleep reported by the respondent</li>
            <li><strong>SocioeconomicStatus</strong>: Socioeconomic status of the respondent</li>
            <li><strong>EducationLevel</strong>: Level of education attained by the respondent</li>
            <li><strong>AccessToHealthcare</strong>: Access to healthcare facilities and services</li>
            <li><strong>GeographicLocation</strong>: Geographic location of the respondent</li>
            <li><strong>DateOfSurvey</strong>: Date when the survey was conducted</li>
            <li><strong>HadHeartAttack</strong>: Presence of heart disease (binary: "Yes" or "No")</li>
        </ul>

  <h2>Problem Framing</h2>
        <h3>Task</h3>
        <p>The goal is to predict the likelihood of heart disease based on demographic and health-related variables using the dataset.</p>
        
<h3>Key Questions</h3>
        <ul>
            <li>What are the demographic and health-related variables associated with heart disease risk?</li>
            <li>How do factors such as age, gender, blood pressure, cholesterol levels, smoking status, diabetes status, obesity, physical activity, and alcohol consumption impact the likelihood of heart disease?</li>
            <li>What is the distribution of heart disease cases among different demographic groups?</li>
            <li>Can we identify patterns or correlations between variables and heart disease prevalence?</li>
            <li>Which machine learning algorithm provides the most accurate predictions for heart disease likelihood?</li>
        </ul>
        <h3>Supervised Learning</h3>
        <p>Since the dataset includes labelled data (e.g., presence or absence of heart disease), it is a supervised learning problem.</p>
        <h3>Classification Task</h3>
        <p>The objective is to predict whether an individual is at risk of heart disease (binary classification).</p>
        <h3>Batch Learning</h3>
        <p>The dataset represents a finite set of data collected at a specific time, making batch learning suitable for model training. There is no continuous flow of data coming into the system, and there is no need to adjust to changing data rapidly.</p>
        <h2>Look at the Big Picture</h2>
        <p>The model's output (prediction of an individual's likelihood of heart disease) will be used as one of many signals in a broader healthcare system. This downstream system will aid healthcare professionals in making informed decisions regarding patient care, such as recommending preventive measures, lifestyle modifications, or medical interventions.</p>
        <h2>Key Analyses</h2>
        <ul>
            <li><strong>Distribution of Heart Disease Risk Factors:</strong> Explored the prevalence and distribution of heart disease risk factors including blood pressure, cholesterol levels, smoking status, diabetes status, obesity, physical activity levels, and alcohol consumption to identify common patterns and variations.</li>
            <li><strong>Impact of Demographic Factors on Heart Disease Risk:</strong> Investigated the relationship between demographic factors (age, gender, ethnicity) and heart disease prevalence to identify any significant associations or disparities.</li>
            <li><strong>Correlation between Risk Factors and Heart Disease:</strong> Identified correlations between variables such as blood pressure, cholesterol levels, smoking status, and heart disease to understand their impact on heart disease risk.</li>
            <li><strong>Feature Importance Analysis:</strong> This analysis can provide insights into which demographic and health-related factors have the greatest impact on heart disease risk.</li>
        </ul>
        <h2>Impact</h2>
        <p>By accurately predicting the likelihood of heart disease, the model can contribute to reducing the burden of cardiovascular disease, improving patient outcomes, and reducing healthcare costs associated with preventable heart-related complications.</p>
       
  
</body>
</html>
