# Ad-Click-Prediction

### Motivation
The main motivation behind the project is “Targeted Advertising”. At its most basic, targeted advertising can just mean that ads are chosen for their relevance to site content, in the assumption that they will then be relevant to the site audience as well. Online advertisers can use different methods to target a particular advertisement on the user based on its traits. Most of company do this as part of social media like Facebook, LinkedIn etc. But most of the times the process goes wrong and the advertisement does not reach its target audience because it is sent out without actually understanding the probability of the occurring click.

### Problem statement

Publicizing is a multi-billion-dollar industry that goes about as a scaffold among organizations and their clients. While the vast majority are aware of the promotions around them, they represent the intensity of those advertisements and the impact of publicizing all in all. Research proposes that basically making somebody mindful of items, occasions, and brands expands the chances of that individual really purchasing those items, going to those occasions, or supporting those brands. Further, if an advertisement catches a man's thoughtfulness regarding the degree that he or she has a prompt, positive response to it, those chances of direct item commitment spikes significantly.

In this project, we are going to work on an advertising dataset, indicating whether or not a particular internet user has clicked on an Advertisement.

The goal is to predict if a user would click on an advertisement based on the features of the user.
Few assumptions made as a part of this project is: 

1)	User taken into consideration are between the age group of 19 to 61. 
2)	There is almost equal ratio of male and female internet users. 
3)	The ad topic is limited to what is given in the dataset. 

### Challenges Faced:

We are highly motivated to work on Ad click prediction dataset, few challenges in this area of study is:

1)	There is very less publicly available data set for ad click. 

2)	New online ads that are coming up is not targeted to a particular set of users, using our prediction algorithm study companies will be able to target it to particular set of users.


### Data Set

The dataset consists of below features:

Daily Time Spent on Site: consumer time on site in minutes

Age: Customer age in years

Area Income: Avg. Income of geographical area of consumer

Daily Internet Usage: Avg. minutes a day consumer is on the internet

Ad Topic Line: Headline of the advertisement

City: City of consumer

Male: Whether or not consumer was male

Country: Country of consumer

We have done preliminary EDA(mention below) and we are planning to do more insight as we progress.


### Cleaning and Approaches

Considering the 'Advertisement Topic Line', we decided to drop it. In any case, it if we need to extract any form of interesting data from it, we can use Natural Language Processing. 

As to 'City' and the 'Nation', we can supplant them by dummy variables with numerical features, Nonetheless, along these lines we got such a large number of new highlights. 

Another methodology would be thinking about them as a categorical features and coding them in one numeric element. 
Changing 'Timestamp' into numerical value is more complicated. So, we can change ‘Timestamp’ to numbers or convert them to spaces of time/day and consider it to be categorical and afterwards we converted it into numerical values. And we selected the month and the hour from the timestamp as features. 


### Exploratory Data Analysis 

We came up with some interesting questions on the dataset and we tried to find answers for the same during EDA process.

#### What age group does the dataset majorly consist of? 

We observe that the oldest person in the dataset is 61 years old and the youngest person is 19 years old and the average age as per dataset is 36 years old. 

<img width="615" alt="screen shot 2018-12-06 at 6 08 30 pm" src="https://user-images.githubusercontent.com/22437872/49623323-08975400-f982-11e8-9a6d-f2c6f8af5e8f.png">





