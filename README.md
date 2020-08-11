# J124 Data Journalism - final project by Rene Cheng
## Drug Use By Age (From 12 to 65+ years old) 
### Children as young as 12 has been exposed to drugs and alcohol 


##### Introdction: 
In this project, I investigated the data set of drug use by age from [Fivethirtyeight Github Respository](https://github.com/fivethirtyeight/data/tree/master/drug-use-by-age). The data was used to investigate the story behind "How Baby Boomers Get High". It contains 13 drug uses from across 17 ages, range from as young as 12 years old up to 65+ years old. All the data and sources can be found from: [National Survey on Drug Use and Health from the Substance Abuse and Mental Health Data Archive](https://www.icpsr.umich.edu/icpsrweb/content/SAMHDA/index.html)


##### Converting data set 
In order to get this data and convert into a usable format, I will have to download the raw dataset from the Fivethirtyeight Github Respository, and ensure I download a Comma Separated Values (.csv) file. This way, I will be able to look at the data in details in Google Sheets to create pivot tables and graphs. In terms of cleaning the data set, I did not have to do much as the data set was already cleaned before I downloaded it. 

Here is the following steps I used to convert & clean the data set: 
1. Download .csv file from Github 
2. Upload data set onto Google Sheets 
3. Look at what was interesting about the data set 
4. Separate "Percentage of drug-use" and "Drug-use Frequency" columns for a more visual view
5. Choose the certain drugs I found interesting and delete the rest 
6. Ask my data set questions 

In this data set, there are 13 drugs reported, however, I am only choosing two of the drugs from all ages. I will be focusing on the drugs: cocaine and marijuana. Also, each age group has a sample size at around 2000+, I multipled the number of people who are sampled by the percentage to see what is the number of people who has in contact to this drug. _The total sample size for all ages is 55,268 individuals_. 

Here is the formula I used: 
```equation: 
=Sample Size*(Percentage/100) 
```
Example: 
In age 12, there are 2798 individuals in the sample size. There are 1.1% of this age group have contact with marijuana. In order to find the number of people who has contact with marijuana. I used this formula: 
```equation: 
 =2798*(1.1/100)
```
The answer: 30.778. There are around 31 people at the age of 12 years old have contact with marijuana. 

##### Interrogating the Data 
Questions I asked my data: 
1. What is the total number of people that use cocaine versus marijuana?

 Pivot Table for Question 1: 

 <img src="https://media.journalism.berkeley.edu/upload/2020/08/1597112882a0d6661.png" width="400" height="300">

 
 Data visualization for Question 1: 

  <img src="https://media.journalism.berkeley.edu/upload/2020/08/1597114495ac996ff.png" width="600" height="600">

I thought it was an interesting data set to see how people in different ages already have contact with drugs. Especially when it comes to cocaine, it might sound dangerous, but it is very accessible for the public. When it comes to the age range 22 to 23, I thought it was not as surprising, because at around 22 to 23, it is when people graduate from college. However, it was extremely surprising to see how people in the age group of 12 years old already have access to drugs like cocaine and marijuana. The number of people who use marijuana was not as surprising as I thought, because around 13 states in the U.S. have legalized marijuana other than medical purposes (Source: https://disa.com/map-of-marijuana-legality-by-state). I predict that as more states legalize the marijuana, and more consumers have access to them, the number of total people that use marijuana will rise. 

2. How often do these individuals use cocaine versus marijuana in a year?

Pivot Table for Question 2: 

<img src="https://media.journalism.berkeley.edu/upload/2020/08/1597113160df7bc5d.png" width="400" height="300">


Data Visualization for Question 2: 

 <img src="https://media.journalism.berkeley.edu/upload/2020/08/1597115290ac62f71.png" width="600" height="600">
  
 In this data visualization, it shows the median frequency of the individuals use cocaine vs. marijuana in a year. It was fasincating to see that there was a big jump of cocaine usage from ages 35 to 49 and 50 to 64. On the other hand, the usage of marijuana is extremely different compare to the cocaine usage. The highest number of marijuana usage is in the age range of 30 to 34. I can also see the slight increase from the age 17 to 18, because it is when many individuals are going into the college. I also predict that if this data set has a time frame filter, the numbers will increase during summer vacation, because that is when most of the parties happen. 

##### Conclusion 
Overall, it was fun to see how many people have contact with drugs and how frequently they use them. While I only focused solely on cocaine and marijuana usage. It was still interesting to see which age group has the most contact with drugs like alcohol, heroin, crack, and more. I believe drugs have become very accessible in so many ways in the U.S. I was surprised to see minors in this data set, as I did not expect children as young as 12 years old would have access to drugs. Even though marijuana has been legalized in many states, it should also be kept away from minors. 
