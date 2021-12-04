# <h1 align ="center">Personal DataSet Project</h1>
Hello there! This project is meant to explore the patterns within Google's Pay-Per-Click- or PPC- advertising data. I've worked in the PPC world for a couple of years now, and the patterns of data within this field have never failed to amaze me, so I thought that it might make a good project to combine what I've learned in this class and what I do for work.  

**Prerequisites:**  
R  
RStudio  
Specific R libraries needed include:  
  tidyverse  

**Screenshots:**  
![Ad_Revenue](https://user-images.githubusercontent.com/91223695/142338037-19c19398-8827-46ff-aaf4-d697c376fbdf.JPG)  
This shows Google's advertising revenue in US Billion Dollars by year, from 2001-2020. As you can plainly see, Google's growth in this area is nothing short of staggering, and they have a real motivation for good data and forecasting for who will click- and ultimately spend money- on ads.  

Looking more deeply at some specific PPC marketing data I found on Kaggle (specific source list referenced below), I cleaned the data by first eliminating all Facebook campaigns from the dataset, then cleaned out all 'unknown' age values.  Finally I eliminated some of the columns that weren't needed for my test- such as date, campaign type, product, phase, and subchannel. What I was left with can be found here: https://github.com/jessicavian1/PersonalDataSetProject/blob/main/advertising.campaign.analytics.csv  
From this point I popped the data into R to perform some basic visulazations, like this one, which shows you how PPC ad spending is broken down across age groups.  
![Age vs Ad Spend](https://github.com/jessicavian1/PersonalDataSetProject/blob/main/Age%20vs%20Ad%20Spend.JPG)  
  
  As you can see, there is a clear distinction of spending behavior across age groups. I wanted to look at this moe closely, so I chose to make a boxplot of a specific column. Since many of the lower age groups have a significant amount of outliers, I chose to look at the 65+ group. This is what I found.  
![AdSpends for 65+](https://github.com/jessicavian1/PersonalDataSetProject/blob/main/Ad%20Spends%20for%2065%2B.JPG)  

Obviously there is more to consider when forecasting whether a customer will click on an ad than just their age, but I hope that this basic foundation will help me as I continue to grow my data skillset and apply more complicated tasks to data similar to this.  

**Contributing:**  
Contributions and issues always welcome! If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Thanks!!  
Fork the Project  
Create your Feature Branch (git checkout -b feature/AmazingFeature)  
Commit your Changes (git commit -m 'Add some AmazingFeature')  
Push to the Branch (git push origin feature/AmazingFeature)  
Open a Pull Request  


**Contact:**  
Jessica Vian - jessica.vian@wsu.edu  
Project Link- https://github.com/jessicavian1/PersonalDataSetProject  

**References:**  
 During the process of this project, I gathered original data from the following sources:  
 https://www.statista.com/statistics/266249/advertising-revenue-of-google/  
 https://www.kaggle.com/avinashlalith/merkle-sokrati-advertising-campaign  
