**Title:** Predicting patient hospital experience in US hospitals

**Problem:**  The Centers for Medicare and Medicaid Services (CMS) has developed summary star ratings based on patient hospital experience  survey results to make it easier for consumers to use the information on the Hospital compare website (https://www.medicare.gov/hospitalcompare/search.html?) and to spotlight excellence in healthcare quality. To get these start ratings, hospitals must have at least 100 completed surveys over a given four-quarter period. In addition, hospitals must be eligible for public reporting of survey measures. Hospitals with fewer than 100 completed surveys don't get star ratings. Our goal in this project is therefore, to build a machine learning model to predict the summary star ratings (i.e. patient experience) of the hospitals based on the multitude of measures reported in the hospital compare data for around 4000 hospitals in the US in the abcense of the survey results. These  measures constitute around 100 different hospital characteristics including among others information on the number of readmissions, hospital type, safety of care, timliness of care, treatment outcome, and spending per patient. 

**Client:** The result of such a model can be utilized by CMS to provide a more comprehensive serivce to the consumers when they query the website for such ratings. Additionally, CMS can benefir from such predictive modeling when determining payment to health-care organizations for taking care of patients. On the other hand, private hospital owners and local county governments are potential customers as they can use the result to inverstigate whether or not they meet the criteria for Medicare reimbursements. Moreover, hospital owners can exploit the model to improve the quality of care they provide. 


**Data:** They main data for this work will be downloaded from https://data.medicare.gov/data/hospital-compare. This includes 67 comma seperated value files (.csv). The ones of specific interest are per hospital information where varietery of measure are reported for each hospital row. We will mainly focs on the data collected between 2015-2017. Additional helpful census data, such as patient demographics and average incoe per houshold will be collected seprately through US cencus Bureau.

**Modelling approach:**

**Deliverables:**



