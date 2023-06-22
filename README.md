# Titanic Exploratory Data Analysis (EDA)

<p>This repository contains code and analysis for the exploratory data analysis (EDA) of the Titanic dataset. The purpose of this analysis is to gain insights into the dataset and understand the variables that may influence the survival of passengers on the Titanic.</p>

<h2>Background Knowledge</h2>

<p>Before diving into the analysis, it is important to establish some background knowledge about the Titanic and its passengers. Some key facts include:</p>

<ul>
  <li>Approximately 2,200 people were on board the Titanic, including around 900 crew members.</li>
  <li>The iceberg struck the front of the ship, causing it to break in half.</li>
  <li>There was a "women and children first" order for boarding lifeboats, which was sometimes misunderstood as "women and children only."</li>
  <li>Passengers in different classes had different levels of access to lifeboats.</li>
  <li>Immigration laws at the time restricted third-class passengers from accessing certain areas of the ship.</li>
</ul>

<p>Based on these facts, it is hypothesized that variables such as passenger class (Pclass), age, and gender (Sex) may have had a significant impact on the survival of passengers.</p>

<h2>Distinct Values in Each Variable</h2>

<p>Before proceeding with the analysis, an examination of the distinct values in each variable is performed. The following variables are considered:</p>

<ul>
  <li>PassengerId: A unique identifier for each passenger.</li>
  <li>Survived: Indicates whether the passenger survived (1) or not (0).</li>
  <li>Pclass: The passenger's class (1st, 2nd, or 3rd).</li>
  <li>Name: The passenger's name.</li>
  <li>Sex: The passenger's gender.</li>
  <li>Age: The passenger's age.</li>
  <li>SibSp: The number of siblings/spouses aboard.</li>
  <li>Parch: The number of parents/children aboard.</li>
  <li>Ticket: The ticket number.</li>
  <li>Fare: The fare paid by the passenger.</li>
  <li>Cabin: The cabin number.</li>
  <li>Embarked: The port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).</li>
</ul>

<h2>Spotting Data Inconsistency</h2>

<p>Several inconsistencies are identified in the dataset, which require further investigation and cleaning. These inconsistencies include:</p>

<ul>
  <li>Duplicates in the "Name" variable, indicating duplicate records for the same person.</li>
  <li>Duplicates in the "Ticket" variable, suggesting passengers traveling in groups with one ticket.</li>
  <li>Excessive distinct values in the "Cabin" variable, requiring further processing to focus on the cabin information only.</li>
  <li>Inconsistencies between the "prefix" extracted from the "Name" variable and the "Sex" variable.</li>
  <li>Incorrect values in the "Parch" variable for passengers under the age of 17.</li>
</ul>
  
<p>Each inconsistency is examined in detail and appropriate corrective actions are taken to ensure data consistency.</p>

<h2>Identifying Outliers</h2>

<p>Outliers are identified in the "Age" and "Fare" variables. A thorough examination of these outliers is conducted to understand their significance and determine if any adjustments or exclusions are required.</p>

<h2>Conclusion</h2

>

<p>The EDA of the Titanic dataset provides valuable insights into the variables that may have influenced the survival of passengers. By understanding the background knowledge, identifying inconsistencies, and examining outliers, the dataset can be prepared for further analysis and modeling to predict passenger survival.</p>

<p>Please refer to the code and analysis files in this repository for a detailed exploration of the Titanic dataset.</p>
