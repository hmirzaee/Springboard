**Title:** Predicting patient hospital experience in US hospitals

**Problem:**  The Centers for Medicare and Medicaid Services (CMS) has developed summary star ratings based on patient hospital experience  survey results to make it easier for consumers to use the information on the [hospital compare website](https://www.medicare.gov/hospitalcompare/search.html?) and to spotlight excellence in healthcare quality. To get these star ratings, hospitals must have at least 100 completed surveys over a given four-quarter period. In addition, hospitals must be eligible for public reporting of survey measures. Hospitals with fewer than 100 completed surveys don't get star ratings. Our goal in this project is therefore, to build a machine learning model to predict the summary star ratings (i.e. patient experience) of the hospitals based on the multitude of measures reported in the hospital compare data, rather than based on the patient survey results. This will potentially cover around 4000 hospitals in the US. These measures constitute around 100 different hospital characteristics including among others information on the number of readmissions, hospital type, safety of care, timeliness of care, treatment outcome, and spending per patient. 

**Client:** In the absence of the survey results, the outcome of such a model can be utilized by CMS to provide a more comprehensive service to the consumers when they query the website for such ratings. Additionally, CMS can benefit from such predictive modeling when determining payment to health-care organizations for taking care of patients. On the other hand, private hospital owners and local county governments are potential customers as they can use the result to investigate whether or not they meet the criteria for CMS reimbursements. Moreover, hospital owners can exploit the model to improve the quality of care they provide. 

**Data:** The main data for this work will be downloaded from [the official US government site for Medicare](https://data.medicare.gov/data/hospital-compare). This includes 67 comma separated value files (.csv). The ones of particular interest are hospital level information where variety of measures are reported for each hospital in a row. We will mainly focus on the data collected between 2015-2017. Additional helpful census data, such as patient demographics and average income per household, that could influence the outcome of the predictive modeling, will be collected separately through [US Census Bureau](https://factfinder.census.gov/faces/nav/jsf/pages/index.xhtml).

**Modeling approach:** The summary star ratings follow a  5-star rating system that are representative of the amount of patient satisfaction at each hospital. Our predictive model, therefore, should classify the different hospital measures into 5 different classes and additionally predict the probability for each class. In this regard a supervised machine learning algorithm would be suitable. It is possible that there will not be enough training data for each of the 5 classes and care should be taken to address the imbalanced training data. We will moreover investigate different classification algorithms and compare their performances.

**Deliverables:** 
1. Python codes for: Data cleaning and wrangling, Exploratory data analysis, and Predictive Modeling
2. Capstone project report
3. Capstone project presentation
                   




