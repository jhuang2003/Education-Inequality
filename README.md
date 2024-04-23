# Education-Inequality
The purpose of this project is to investigate and address the inequality of educational opportunity in U.S. high schools. We will focus on average student performance on the ACT or SAT exams. 

# Data
We will utilize two datasets titled EdGap_data.xlsx and ccd_sch_029_1617_w_1a_11212017.csv. The first dataset was gathered from EdGap.org https://www.edgap.org/#5/37.875/-96.987. It is composed of average ACT or SAT scores for different schools and several socioeconomic characteristics of the school district from 2016. The second dataset is from National Center for Education Statistics https://nces.ed.gov/ccd/pubschuniv.asp.     

# Data Preparation
In order to prepare the data we had to deal with variable names that did not have intuitive names, and one dataset being much larger than the other. We then had to ensure that the data was able to answer the question. This was accomplished by plotting some basic exploratory plots. Then, we renamed columns to be in line with good coding practices, thus, making it intuitive. The next step was to join the two datasets. This was done using a left join with id as the key. Then we eliminated outliers by eliminating any average_act scores below 0 and above 100 percent. We performed a train test split using 20% of the data for the test set. The data was then exported.
