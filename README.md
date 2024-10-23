# Lending Club Case Study - Analyzing Loan Default Risk
To use Exploratory Data Analysis (EDA) to discover important characteristics impacting loan default risk and create credit loss mitigation measures for a consumer finance organization. Through a comprehensive EDA analysis, this project seeks to offer insightful information on loan default risk, empowering the business to make better decisions and minimize losses..


## Table of Contents

### General Info

  Project Title      : Lending Club Case Study - Analyzing Loan Default Risk
  Objective          : To identify key factors influencing loan default and develop strategies to mitigate credit loss.
  Dataset            : Historical data on loan applicants, including their profiles and loan outcomes.
  
### Technologies Used

      Python:       Programming language for data analysis and manipulation.
      Pandas:       Library for data structures and analysis.
      NumPy:        Library for numerical operations.
      Matplotlib:   Library for data visualization.
      Seaborn:      Library for statistical data visualization.
      
### Conclusions
####    Key Findings:
    
         Borrower Profile:
            Grade and Sub-grade:   		Higher grades (A, B) and sub-grades are associated with lower default risk.
            Income:                		Higher income levels generally correlate with lower default rates.
            DTI:                   		Lower debt-to-income ratios are indicative of lower default risk.
            Owning House:	     		Those who don't own a house are more likely to default than the one having a mortgage
            Public record:	     		Those who are having public derogatory records/bankruptcies are more likely to default
    		Revolving Line Utilization:	Lower the revolving line utilization indicates lower default risk factor
    		State:				        Borrower from the State Florida is more likely to default and from is the state DC is less likely to default
    
         Loan Attributes:
    	      Loan Amount	     		    Higher the loan amount correlates with higher default risk
    	      Installment	     		    Higher the Installment correlates with higher default risk
              Loan Term:             		Shorter loan terms (36 months) are associated with lower default rates.
              Interest Rate:         		While there's no strong correlation, higher interest rates might suggest higher risk.
              Loan Purpose:          		Some loan purposes (e.g. Small Business) might have higher default rates.
	      
####  Recommendations:
    
     Underwriting Criteria:
             Consider stricter criteria for lower grades and sub-grades.
             Prioritize applicants with lower DTIs and higher incomes.
     Loan Terms:
             Offer shorter loan terms to mitigate risk, especially for higher-risk applicants.

     Interest Rates:
             Implement more targeted pricing strategies based on borrower risk factors.

     Verification:
             Strengthen income verification processes to reduce information asymmetry.
             
### Acknowledgements
    Data:             Loan Data Set and Loan Data Definitions
    Tools:            Jupyter Notebook, GitHub 
    Collaborators :   K Lalithabai Sobha & Ashwani Singh
