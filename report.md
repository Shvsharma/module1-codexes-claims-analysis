I imported the inpatient Medicare fee-for-service- claims data from the CMS Synthetic Data Collection as a .csv file into google Colab.
I then ran a python script loading this data set into a Pandas DataFrame. 
Next I identified columns related to the medical codexes, such as ICD codes and HCPCS codes. 
Then I identified 8 unique medical codexes and calculated the frequency of each unique value
I determined if there were any missing or null values in the columns filling the empty values with a placeholder called 'Missing'
A summary was then created of the top 5 most common codes found in each data set. 
A pattern that was noted in my data set was that compared to any other diagnostic code there were significantly more people diagnosed with stress compared to any other diagnostic code.
The implication I've gathered from this data set is that healthcare providers and policy makers should put more focus and apply policies and practices that will help minimize the high instances of stress among the inpatient population.
