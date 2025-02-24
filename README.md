# Python-TX-Workers-Comp-Data-Analysis

## Data Visualization & Comparative Analysis
>In our study, we created a chart to see which drugs had the largest price difference per pill/unit. After conducting our analysis, we noticed that Maci has the largest difference in costs.
![image](https://github.com/user-attachments/assets/18e41b39-fcde-4b18-a716-c9dff47558a3)




> _Figure 1 This visualization demonstrates the 10 largest price differences per pill/unit excluding prescriptions over a 90 day supply._  
>After doing research on MACI and MACI MIS, we understood that the reason for the large difference in costs is that each patient requires a different amount of Maci depending on how much damaged tissue the patient needs. According to the U.S. Food and Drug Administration, Maci is the first FDA product that applies the process of tissue engineering to grow cells on scaffolds using the healthy cartilage tissue from the patient’s own knee. This implant is administered by a surgeon and uses the patient’s own cells that are expanded and placed onto the bio-resorbable porcine-derived collagen membrane that is implanted over the area where the defective or damaged tissue was removed. Each Maci implant contains a small cellular sheet of 500,000 to 1,000,000 cells per cm2 depending on the size of the cartilage that is defected in the patient. Because each Maci implant requires surgery and a different amount of cellular sheets, the cost difference per patient is significant. 
![image](https://github.com/user-attachments/assets/da787a4e-a76e-4ae7-b72b-c80d54034bfa)
> _Figure 2 This visualization demonstrates the variation in drug prices for the top ten largest price differences excluding prescriptions over a 90 day supply._
> The next drug with the largest price difference was Acetaminophen/Codeine. After more investigation we saw three instances where Acetaminophen/Codeine were costing $47,241.45 for 7 pills, $44,948.24 for 15 pills, and $3,579.28 for 20 pills. These outliers were thousands of dollars more than the other cost of pills. Because we wanted to have accuracy in our analysis, we decided to use mode to investigate the cost of drugs. Once we did that our list for the top ten most expensive drugs changed. However, we still wanted to see the range for the cost of Acetaminophen/Codeine, so we calculated the range. To do this we took out the outliers by removing anything billed more than $600, we then saw that the price per pill for Acetaminophen/Codeine ranged from $0.49 to $1.49 per pill.

![image](https://github.com/user-attachments/assets/6b7cf4db-d93d-40a5-a06f-b278cc61bb4a)

> _Figure 3 This chart shows the range of the price per pill cost of Acetaminophen/Codeine._
 
Due to outliers that we noticed in our data, we wanted to still see which drugs were the most expensive per pill/unit. To do our calculations, we decided to use mode to see which drugs were costing the most. We also decided to remove MACI and MACI MIS because these implants require surgery and Acetaminophen/Codeine due to the outliers it had. After calculating the mode for each drug, we received the following results. 

![image](https://github.com/user-attachments/assets/ffbd52d9-5fae-4f75-bdb7-c0711763e866)

> _Figure 4 This chart shows the mode of the cost per pill for drugs excluding MACI, MACI MIS, and Acetaminophen/Codeine._ 
 
From the chart, we can see that Botox Injections at 200 Units were the most expensive costing $1257.89. Monovisc was the next most expensive at $491.50 and then Bydureon Pen at $244.24. After these three dugs, most medicine’s mode was under $35 per pill/unit. 

Trends over Time
As mentioned earlier, we decided to combine all the drugs that contained Oxycodone, Hydrocodone or Codeine in their names into three categories; Oxycodone, Hydrocodone, and Codeine. Had we not done this we would have ended up with more than double digit categories for the same opioids. After filtering the drugs into the three categories, we decided to graph the three categories of opioids to see which opioid was prescribed for more than five days, which according to the Mayo Clinic is the number of days that increases your chances of becoming addicted to opioids. 



![image](https://github.com/user-attachments/assets/7ee9f5b6-7737-404c-af44-00f3582fd6d9)



>_Figure 5 This visualization shows the number of prescriptions that were given more than a 5 day supply for Oxycodone, Hydrocodone, and Codeine._
 

From our results, we see that Hydrocodone was prescribed more than 5 days over 6,000 times. Codeine was prescribed for more than five days at least 3,000 times and Oxycodone was prescribed for more than five days over 1,000 times. These results were surprising because this means that thousands of Texans are at high risk of becoming addicted to an opioid. 
We next wanted to create a graph that demonstrated the number of prescriptions for these opioids that were more than the five days it takes a person to become addicted and less than 90 days because those prescriptions were more than likely outliers. It is not common for a pharmacist to prescribe more than a 90-day supply of drugs. 


![image](https://github.com/user-attachments/assets/d7f4f882-8076-494c-8198-3e0f77104d6c)



>_Figure 6 This visualization shows the number of times our three most researched drug types have been prescribed for a period of over five days over time through the use of a line graph._
 

After creating our graph, we can see that Codeine was the most prescribed opioid in early 2020 but throughout the year Hydrocodone outpaced all the other drugs reaching its peak in prescriptions in 2021. In 2021 all drugs peaked in prescriptions, however Hydrocodone was prescribed more than 2,000 times in that period which is more than double what Oxycodone and Codeine were being prescribed.  It is also important to point out that most of the high prescriptions took place during the Covid-19 pandemic.  The covid pandemic disrupted many industries in the world, including access to healthcare. It also affected the jobs for many people, but by late 2020 and 2021, people were gradually entering the workforce yet again.  According to our research into the National Library of Medicine, this disruption also affected opioid prescriptions. Opioid prescriptions decreased in the early phase of the pandemic but by May 2020, prescriptions returned back to their pre-pandemic levels. These disruptions also affected the supply chain of many medicines and as a result, many work injury related procedures were suspended as hospitals pivoted their attention towards the care of COVID-19 patients. While this shift resulted in the postponement of some procedures to later dates, it is important to note that there were many other factors, such as a gradual increase in workforce participation, higher workplace injuries, may have all contributed to changes in prescription patterns or workers' compensation claims during this period. 

According to the Bureau of Labor Statistics, 2021 saw roughly around an 8.9 percent increase in fatal work injuries compared to the previous year. Additionally, the rate of work injuries was higher in 2021, with 3.6 injuries per 100,000 workers compared to 3.4 in 2020. This demonstrates a distinct change in operations as the pandemic neared its end. But while this could have led to an increase in opioid prescriptions in 2021, many changes from the pandemic such as the way healthcare is operated, limited work force or lack of training could have contributed as well.





![image](https://github.com/user-attachments/assets/16bcff61-da29-4cab-98dc-f143ed1b60a6)







>_Figure 7 This visualization highlighted the top ten most expensive drugs as well as the most prescribed._


When we compared the most expensive drugs with the most prescribed drugs we did see some overlap. Hydrocodone Bitartrate-Acetaminophen 325 MG –10 MG, Ibuprofen, and Gabapentin appeared on both lists. 


![image](https://github.com/user-attachments/assets/c66723be-2243-4cc0-88b1-a15df4913ba8)


>_Figure 8 Shows the range cost of Gabapentin, Hydrocodone Bitartrate-Acetaminophen 325 MG-10, and Ibuprofen._
 
After seeing that these drugs costs were in the thousands, we next decided to see the range in what these drugs were costing. The max for Gabapentin was $8,915.09, the max for Hydrocodone Bitartrate-Acetaminophen 325 MG was $1,253.70, and the max for Ibuprofen was $3,409.

![image](https://github.com/user-attachments/assets/9f33dba5-bc07-4d47-be5b-e420772728d0)

>_Figure 9 show the times Gabapentin, Hydrocodone Bitartrate-Acetaminophen 325 MG-10, and Ibuprofen costs was over $1,000._
  
The cost for Ibuprofen (a common pain/inflammatory medicine) alerted us to possible errors in the input of data in our dataset. To see if they were outliers, we decided to see how many times these drugs costs were over $1,000. After running our data, we see that Hydrocodone Bitartrate-Acetaminophen 325 MG-10, and Ibuprofen were only charged over $1,000 one time each, leading us to believe that these were outliers. Gabapentin however costs was over $1,000 161 times. This led us to conclude that Gabapentin is an expensive drug that is prescribed commonly.

![image](https://github.com/user-attachments/assets/1d4b57e4-a06a-4cac-91eb-eaa7588019ca)

>_Figure 10 shows the mode costs of Gabapentin, Hydrocodone Bitartrate-Acetaminophen 325 MG-10, and Ibuprofen_
 
We finally decided to see the mode of these three drugs to see how much these drugs were charged the most. Gabapentin was charged $153.70 the most, next Hydrocodone Bitartrate-Acetaminophen 325 MG-10 was charged $114.04 the most, and Ibuprofen was charged $29.69 the most.


![image](https://github.com/user-attachments/assets/f10ddcbb-d1a5-4073-ab0a-5f8cf6dfa04f)

>_Figure 11 Shows how much Texas Workers Compensation Insurance paid and the estimated out-of-pocket cost for individuals._ 
 

For our study, it was also important to see how much Texas Workers Compensation Insurance paid for patients' treatment vs the out-of-pocket costs that patients had to pay. From our analysis we found that during the past five years, Texas Workers Compensation Insurance paid $105,681,689.23 and individuals had to pay out-of-pocket costs of $77,574,486.99. 

![image](https://github.com/user-attachments/assets/f5233690-fab5-4f14-af65-57b70eb47907)

>_Figure 12 Shows the yearly cost that is paid by Workers Compensation and the estimated out-of-pocket  costs for individuals by year._

We then decided to graph the results by year. According to the graph above, 2021 was the most that Texas Workers Compensation paid for patients' treatments. This is consistent with our data that shows that 2021 was the year that most people were getting prescription pills. It was also after the initial start of the pandemic where access to healthcare was stopped to make room for Covid patients in hospitals. 2021marked the opportunity for many individuals waiting for surgeries to finally have an opportunity to do so. Interestingly enough, 2020 was the year that patients had to pay the most for out-of-pocket costs. 

 ![image](https://github.com/user-attachments/assets/7bb76987-e9d6-40d2-b78b-41f296888c99)
>_Figure 13 Shows the average out-of-pocket costs for patients._


When patients did have to pay out-of-pocket, we found that the average out-of-pocket cost was $73.98. 

![image](https://github.com/user-attachments/assets/eededafe-a993-456d-98d8-44a8de9788ae)

>_Figure 14 Shows the instances of out-of-pocket costs vs Texas Workers Compensation covering the bill._
  
When we graphed to see how many times Workers Compensation paid vs when patients had to pay out-of-pocket, we discovered that patients had to pay out-of-pocket costs 672,729 times vs Texas Workers Compensation Insurance completely covering the cost 375,846 times.  This shows that people had to pay for their medication almost twice as much as Texas Workers Comp covering the bill. 
