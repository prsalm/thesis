<html>

<h1>
ReadMe
</h1>

<body>

<p>This site was setup to share my thesis research that I performed to complete the requirements for my Master of Science degree in Predictive Analytics from Northwestern University.  The focus of my research was on evaluating different modeling processes for predicting early patient readmission.  The Abstract for my thesis is included below.</p>

<p>On this site, you can access my full thesis research paper in the PDF file <a href="Evaluating A Mixed-Ensemble Method for Predicting Hospital Readmissions Across Multiple Disease Types.pdf">Evaluating A Mixed-Ensemble Method for Predicting Hospital Readmissions Across Multiple Disease Types.pdf</a>.  For the data analysis performed as part of this project, I leveraged both Python and IBM SPSS Modeler.  The Python code is all included within the body of my thesis text.  The SPSS Modeler files are included in the folder labeled ÒModeler Streams.Ó  The data I used for this project came from the Nationwide Readmission Database.  Their usage rules prohibit me from sharing the data on this site.  However, if youÕd like to use my code to test these results, you do so through the Healthcare Cost and Utilization Project <a href="https://www.hcup-us.ahrq.gov/nrdoverview.jsp">website</a>.</p>

<br><p><b>Thesis Abstract</b></p>

<p> <i>Objective</i><br>
Hospitals are under significant financial pressure to reduce the rate of readmissions that occur in less than 30-days from discharge.  Traditional predictive models could flag potential patients at-risk for early readmission, but the lack of transparency from these models meant they provided no insight for care teams on where to direct interventions to prevent the readmission.  Turgeman and May demonstrated an alternative approach ensembling highly sensitive SVM models with transparent C5.0 decision tree models on data for patients with Congestive Heart Failure.  This paper evaluates that approach against data from patients with acute myocardial infarction, chronic obstructive pulmonary disease, coronary artery bypass graft, pneumonia and stroke.</p>
<p><i>Materials and Methods</i><br>
Data for this study was acquired from the Nationwide Readmission Database, providing national anonymized data on readmissions that occurred in 2014.  This data was subset by disease type, and Logistic Regression, Random Tree, Neural Network and Ensemble models were built and evaluated for each.</p>
<p><i>Results</i><br>
The results ran contrary to those of Turgeman and May, who found ensembles achieved the highest sensitivity of 0.91 against their training data, and 0.25 against their test data.  The Random Tree models in this study had better sensitivity scores than all ensemble models, ranging from 0.62 to 0.94, and therefore were better able to flag patients at-risk.  Additionally, the Random Tree decision rules provided transparency, but the actual clinical utility of that transparency is suspect and requires further investigation.</p>

</body>
</html>
