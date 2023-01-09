#### Birth-Prediction

##### Introduction:

Giving birth is important to each country. In Taiwan, people are less and less willing to give birth every year, and the Taiwanese government would like to solve this issue. By analyzing and visualizing the data, we can find several interesting findings about birth, which may help the government to design its birth policies. Moreover, the birth prediction model can help them to check whether their policies work (A/B testing).

##### Dataset:

Daily birth data from 1994 to 2014.

##### Goal:

Predict the birth of the next 100 days.

##### Method:

Train a Bi-LSTM model to predict the birth from the historic data.

##### Findings:

![image](https://user-images.githubusercontent.com/90480106/211233968-68d4b609-87c1-4768-be2b-2496c8d24c8e.png)

1. The first chart (year) shows that 2007 was a peak, meaning that before 2007, more and more people were born every year. However, after 2007, fewer people were born every year.

2. The second chart (month) shows that most people are born in July, August, and September. If the government wants to increase the birth rate by giving out a new policy, September to November will be a great period to release (10 month before July to September).

3. In the third chart (date of month), there is no big difference between each day except for the thirteenth. The reason may be that some consider the number 13 as an unlucky number.

4. The last chart (day of week) shows most people were born on weekdays. The reason may be that there are fewer doctors at the hospital during the weekend, as a result, they prefer to arrange the caesarean section on weekdays.

##### Models:

![Screenshot 2023-01-08 at 8 54 01 PM](https://user-images.githubusercontent.com/90480106/211234173-423ec1b9-6552-41e3-9b63-568245730683.png)

##### Results:

![image](https://user-images.githubusercontent.com/90480106/211234071-2c842539-f508-48e2-89ed-aa97e1b17969.png)
