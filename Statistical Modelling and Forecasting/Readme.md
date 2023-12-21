The coursework involves statistical analysis of real data sets in R and a report to describe the results. 

The emphasis is on writing the report, so producing just computer output it is not enough. 

Also, any general comments about the models used (i.e. GAMLSS) not related to the data analysis itself it will be at best ignored or at worst penalised. 

The output should be complimented with intelligent comments and explanations. The coursework consists of the following: 
•	Each student is given two data sets. 
•	Each group of students is required to find a third data set, related to their own interest. 
•	Each student is expected to analyse the first two data sets following the instructions given below. 
•	For the third data set each student is required to show their own initiative in analysing their subsample of the data following the instructions given below. The analysis should include a preliminary data analysis using graphics, a statistical analysis using GAMLSS, and intelligent comments on the results. 
•	Each student should write a small report (less than 5000 words) describing how they have done the three analyses and describing their results. Section 2 gives instructions on writing the report. 

1 The data
1.1 Instructions on how to analyse the first data set:
The first data set is a subset of Body Mass Index (BMI) data obtained from the Fourth Dutch Growth Study, Fredriks et al. 2000 [1]. The data contains BMI for different ages in years for Dutch boys. Each student will be given a different age, for example, 10 to 11 years old. The aim here is to find a suitable distribution of the BMI at this age. 
1.	(a)  The original data, which contains all ages from zero to twenty-two, exists in thegamlss.data package under the name of dbbmi. Each student should analyse a different age. Here we give an example of how to analyse age 10. We first bring the data set in R and then create a subset data.frame containing only a specific age (here from 10-11). 

1.2 Instructions on how to analyse the second data set:
2.	Cohen et al. (2010) [3] analysed the handgrip (HG) strength in relation to gender and age in English schoolchildren. Here each student is required to analyse a different sample of 1000 from the original 3766 English boys. The data are stored in the packages gamlss.data under the name grip and contain the variables grip and age. The aim here is to create centile curves for grip given age. 

