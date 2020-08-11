# J124 Data Journalism - final project by Rene Cheng
## Drug Use By Age (From 12 to 65+ years old) 
### Children as young as 12 has been exposed to drugs like cocaine and marijuana.



#### Introduction: 
In this project, I investigated the data set of drug use by age from [Fivethirtyeight Github Respository](https://github.com/fivethirtyeight/data/tree/master/drug-use-by-age). The data was used to investigate the story behind "How Baby Boomers Get High". It contains 13 drug uses from across 17 ages, range from as young as 12 years old up to 65+ years old. All data and sources can be found from: [National Survey on Drug Use and Health from the Substance Abuse and Mental Health Data Archive](https://www.icpsr.umich.edu/icpsrweb/content/SAMHDA/index.html)


#### Converting data set 
In order to get this data and convert into a usable format, I downloaded the raw dataset from the Fivethirtyeight Github Respository, and ensure I downloaded a Comma Separated Values (.csv) file. This way, I was able to look at the data in detail in Google Sheets to create pivot tables and graphs in Datawrapper. In terms of cleaning the data set, I did not have to do much as the data set was already cleaned before I downloaded it. 

##### Here is the following steps I used to convert & clean the data set: 
1. Download .csv file from Github 
2. Upload data set onto Google Sheets 
3. Look at what was interesting about the data set 
4. Ask my data set questions 
5. Separate "Percentage of drug-use" and "Drug-use Frequency" columns for a more visual view
6. Choose the drugs I found interesting and delete the rest 

In this data set, there were 13 drugs reported, however, I only chose two of the drugs from all ages: cocaine and marijuana. Also, each age group had a sample size at around 2000+, I multipled the number of people who were sampled by the percentage to find out the number of people who used this drug. _The total sample size for all ages was 55,268 individuals_. 

##### Here was the formula I used: 
To find the total sample size of all age group in Google Sheets,

```equation: 
=SUM(B2:B18)
``` 
I used this formula. The total sample size for all ages was 55,268 individuals. 

To find the number of people who used this drug,

```equation: 
=Sample Size*(Percentage/100) 
```
I used this formula. The total number of people who used this drug varies with age. 

Example: 
In age 12, there were 2798 individuals in the sample size. There were 1.1% of this age group used marijuana. In order to find the number of people who used this drug. I used this formula: 
```equation: 
 =2798*(1.1/100)
```
The answer: 30.778. There are around 31 people at the age of 12 years old have used marijuana.

To find the number of people who used this drug for ALL age group,

```equation: 
=B2*(C2/100) 
```
I used the same formula for each age group and sample size.  After I have entered this formula, I dragged the same formula for the rest of the column. This way, I was able to quickly find out the number of people who used this drug with the same formula. 

#### Interrogating the Data 
Questions I asked my data: 
1. What is the total number of people that use cocaine versus marijuana?

 Pivot Table for Question 1: 

 <img src="https://media.journalism.berkeley.edu/upload/2020/08/1597112882a0d6661.png" width="400" height="300">

 
 Data visualization for Question 1: 

  <img src="https://media.journalism.berkeley.edu/upload/2020/08/1597114495ac996ff.png" width="600" height="600">

I thought it was an interesting data set to see how people in different ages were already using drugs. Especially when it comes to cocaine, it might sound dangerous, but it is very accessible for the public. In the age range of 22 to 23, I thought it was not as surprising, because it is when people graduate from college. However, it was extremely surprising to see how people in the age group of 12 years old already have access to drugs like cocaine and marijuana. The number of people who used marijuana was not as surprising as I thought, because around 13 states in the U.S. have legalized marijuana other than medical purposes (Source: https://disa.com/map-of-marijuana-legality-by-state). I predicted that as more states continue to legalize the marijuana, and more consumers have access to them, the number of total people who use marijuana will rise. 

2. How often do these individuals use cocaine versus marijuana in a year?

Pivot Table for Question 2: 

<img src="https://media.journalism.berkeley.edu/upload/2020/08/1597113160df7bc5d.png" width="400" height="300">


Data Visualization for Question 2: 

 <img src="https://media.journalism.berkeley.edu/upload/2020/08/1597115290ac62f71.png" width="600" height="600">
  
 In this data visualization, it presented the median frequency of the individuals who used cocaine vs. marijuana in a year. It was fasincating to see that there was a big jump of cocaine usage from ages 35 to 49 and 50 to 64. On the other hand, the usage of marijuana was extremely different compare to the cocaine usage. The highest number of marijuana usage wa the age group range from 30 to 34. I can also see there was a slight increase from the age group 17 to 18, because it was when many individuals attend college. I also predicted that if this data set had a time frame filter, there would be more detailed data to see what time of the year drug were used more often. 
 
#### Conclusion 
Overall, it was fun to see how many people have used drugs and how frequently they used them. While I solely focused on cocaine and marijuana usage. It was still interesting to see which age group had the most contact with drugs like alcohol, heroin, crack, and more. I believed drugs have become very accessible in so many ways in the U.S. I was surprised to see minors in this data, as I did not expect children as young as 12 years old would have access to drugs. Even though marijuana had been legalized in many states, it should also be kept away from minors. 
