<h1>Big Data Analytics Programs</h1>

<h2> OBJECTIVE </h2>

Amazon is conducting an experiment on potential target users and want to know if customers list which they have are ACTIVE users or not. 
All of the customers Amazon related tweets is stored in a CSV file. Using this file create a dataframe which contains all the potential customers who are ONLY ACTIVE users. This will help Amazon is focusing more on these customers.

<h2>TASK 1 :</h2>

Create a dataframe “daily_active_users”. Find out the users who are active in at least five listed days.
i.e. created posts in at least 5 days) in Amazon_Responded_Oct05.csv.
Save their “user_screen_name” and “user_id_str” in the dataframe.

![GitHub Logo](/output1.JPG)

<h2>TASK 2 :</h2>

A company would like to conduct an A/B test on Twitter. The experiment.txt file includes the user_id_str they selected as potential experiment targets.

Please create a dataframe “experiment_user” to document the select user id and whether they are active users (join the dataframe from step 1).

![GitHub Logo](/output2.JPG)

Then Calculate the percentage of active user and print out the result.

![GitHub Logo](/output2b.JPG)

<h2>TASK 3 :</h2>

To help the company prepare the data, please select the records (all columns) in Amazon_Responded_Oct05.csv when a user_id_str is included in all the 2 dataframes.

For example, if the user_id_str from Amazon_Responded_Oct05.csv cannot be found in daily_active_user and experiment_user, you should skip. 

![GitHub Logo](/output3.JPG)

Save the result in a dataframe and then export it as Amazon_new.csv

<h2> Final File </h2>

![GitHub Logo](/final.JPG)


