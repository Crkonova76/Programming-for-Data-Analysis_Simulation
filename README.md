## Programming-for-Data-Analysis

### Simulation of data

Name:Martina Crkonova <br/>
Date: December 2019

The main purpose of this document is to create a data set by simulating a real-world phenomenom of my choice. The data need to be modeled and synthesise by using Python.<br/>

The selected topic is the gross income on population of 100 inhabitants in Ireland. The variables age/work experience, gender and education are examined and the relationship with the income is investigated.<br/>

#### _Requirements:_

* Jupyter Notebook
The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. Uses include: data cleaning and transformation, numerical simulation, statistical modeling, data visualization, machine learning, and much more.<br/>

* Pandas
Is the software library  written for the Python programming language for data manipulation and analysis. In particular, it offers data structures and operations for manipulating numerical tables and time series.<br/>

* NumPy
is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.<br/>

#### _Approach taken to the project_

The variables and their relationships are investigated. Based on the research different aspects of varaibles and their influences on the income is established. The dataframes are created just for the sample of 10 outcomes to visualise and check the correctness of the approach.<br/>
In the last part "Simulation of data" all dataframes are created for the size of 100.<br/>


#### _Variable Age/Experience_

* The Range of the age for the simulation of data is established to age 16 to 70 years.
* The distibution of population based on the  age groups in Ireland has normal distribution (bell shaped).For the purpose of this project this project discrete uniform distribution is selected, as I wanted to have the same chance of all age groups of population to be represented.<br/>
* The research completed to evaluate if there is any relationship between the age and income. <br/>

#### _Variable Gender_

* Gender gap defined and 14% as difference between males and females is established
* Distribution of work force is looking into the % representation of males vs females out of the working population. This is used as probability in creating the randomn representation of males vs females in the population .<br/>

#### _Education_

* Education as the direct influencer on the income was established by research and the relationship was confirmed.
* The % representation of population completed primary education, secondary education and degree and higher education was established
* For the purpose of this project the the primary and lower educated people are 0.9 of income of the seconday educated people. The third level and higher educated people are expected earn 1.5 of earnings of the secondary educated people.<br/>

#### _Income_

* Income is represnted in '000 as annual income
* Minimum wage is calculated based on the minimum hourly rate for under 18 years old. The assumption of 37 working hours per week is used. 
* The restriction on the Income based on the age 25 years old and younger is placed (maximum income is €25,000).
* Special variable "Adjusted Salary" introduced, which is used to reflect the impact of gender and education on the income  

#### _Simulation of Data_

* The sample size adjusted to 100 and the dataframe completed with all parameters as set up above.
