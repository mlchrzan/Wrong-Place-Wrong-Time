## Wrong Place, Wrong Time - A EDUC 423A Group Project Studying the Relationship Between Gentrification and School Outcomes

NOTE: Original Project One-Pager (final project code may reflect changes to plans laid out in this document)

Research Question | What relationship, if any, exists between gentrification, as operationalized by the Pearman and Greene (2022) model, and educational outcomes in San Francisco and Detroit between 2010 and 2020?

Background | The urban fabric of American cities is in constant flux, influenced by various socio-economic and demographic factors. A significant agent of change in this context is gentrification. While the socio-economic implications of gentrification have been extensively studied, there remains a research gap concerning its relation to educational outcomes. This proposed research aims to address this lacuna by analyzing the correlations of gentrification with academic metrics in two emblematic American cities: San Francisco and Detroit. In the annals of urban transformation, San Francisco and Detroit provide contrasting trajectories. Historically a bastion of American manufacturing, Detroit has experienced a marked population decline over the last decade (Smith, J., 2021). In contrast, San Francisco, spurred by its status as a nexus of technological innovation, has been a harbinger of pronounced gentrification.

Data Source | This research will utilize the data available through Opportunity Insight’s Opportunity Atlas and Social Capital Atlas. These datasets offer a multifaceted lens to study demographic trends, economic patterns, housing developments, and educational outcomes across the two cities in focus. This dataset does, however, aggregate data from the American Community Survey over a four year time period.

Variables:
Gentrification: Operationalized using the Pearman and Greene 2022 model, this will serve as the primary independent variable.
Cities: San Francisco, CA and Detroit, MI.
Income: Median household income will indicate the economic vitality of the areas under study.
Housing: The number of new housing units constructed annually, measuring population growth and decline.
Educational Attainment: The percentage increase in residents holding college degrees.
High School Graduation Rate: Proportional representation of public high school students graduating within the standard timeframe.
College Matriculation Rate: The percentage of those graduates progressing to tertiary education.
Test Scores: These represent the academic performance of students in standardized tests. Test scores are but one metric for assessing educational quality and student achievement. We obtained this data from the National Center for Education Statistics (NCES).
Enrollment Figures: This variable indicates the number of students enrolled at schools within the analyzed cities. It helps us understand the size and composition of the student population in the study areas. Enrollment data is sourced from the National Center for Education Statistics (NCES).
Per Pupil Expenditure: This metric reflects the amount of money spent per student by the educational system. It is an essential indicator for evaluating the financial resources allocated to education. We also obtained per-pupil expenditure data from the National Center for Education Statistics (NCES).
College Attainment Rates: This variable provides insights into the percentage of residents who have attained a college degree. It serves as a measure of educational achievement and the availability of higher education opportunities. College attainment rates are sourced from the American Community Survey (ACS).
Homeowner Status: Homeowner status indicates whether individuals or households own or rent their homes. This variable offers information about housing stability and wealth accumulation among residents. We gather homeowner status data from the American Community Survey (ACS).

Methodology & Analysis
We will be using R to run our analysis. Utilizing the tidyverse package, we will eliminate inconsistencies and handle missing values. Following this, a descriptive analysis will be undertaken. We aim to capture a comprehensive overview of the data distribution across our variables through functions such as ‘summary' and 'description.'  Our goal is also to conduct correlation analysis using the 'cor' function to pinpoint the strength and directionality of relationships, particularly emphasizing the linear associations between gentrification, income, new housing developments, and educational outcomes.

Our data sources include school-related data, such as test scores, enrollment figures, and per-pupil expenditure, obtained from the National Center for Education Statistics (NCES). Additionally, we will incorporate household-related data, including college attainment rates, homeowner status, and income, sourced from the American Community Survey (ACS). However, it is essential to acknowledge that ACS data, while informative, may involve projections and estimates rather than direct observations.

References
Pearman, F. A., & Marie Greene, D. (2022). School Closures and the Gentrification of the Black Metropolis. Sociology of Education, 95(3), 233-253. 

Smith, J. (2021). The Changing Demographics of American Cities: Insights from Detroit's Population Dynamics. Journal of Urban Studies, 59(2), 312-327.
