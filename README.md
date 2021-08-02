# Predicting-Salary-of-an-Employee-by-Polynomial-Regression
Let's imagine that we are actually an HR department and that we want to hire someone.We actually found someone that seems to be a great fit for the job.Hence,we would like to offere this person a position in our Company.
At the end of the interview,we would come up with a question of his/her salary expectation.The candidate however expects atleast $160,000,as it was the candidates' previous salary.
Well, the goal of this project is to figure out if the previous salary mentioned by the candidate is true or a bluff.We can do that by using polynomial linear regression.
The dataset has been collected from an online website like Glassdoor,where one can find the salaries of different companies.
For this project,we have collected the dataset of salaries of different positions in the previous company in which the candidate had worked.
Next,we need to know which position had this candidate within the previous company.For this,from LinkedIn,we've found that the candidate had worked as Regional Manager with salary of $160,000.
However,from the dataset for regional manager,it's $150,000.Hence,the position corresponding to his salary should be in between 6 & 7,say 6.5.
So,our test data is only a single independent variable ,position-level of the candidate.In this x_test=6.5.
