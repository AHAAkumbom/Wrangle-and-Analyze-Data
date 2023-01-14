# WeRateDogs-Data_Wrangeling
![dog-rates-social](https://user-images.githubusercontent.com/44718084/197365439-01607dc3-f1f5-4c2d-a429-69661fab1281.png)
## Udacity-Data-Anayltic-Project-2
### by (Achumbom Haggai Akumbom)

This projects  consisted of a data set from https://www.kaggle.com/datasets/nurudeenabdulsalaam/weratedogs-twitter-archive
## Gather
Gathering data wasn't complicated and we succeded to gether all the date from the diffrent sources which where:
1. The twitter-archive-enhanced.csv using the = pd.read_csv() command
2. The image-predictions.tsv using the response = requests.get(url) command
3. We could use the twitter API so we used the tweet-json.txt file for the tweet-api data

## Assesing
This was a pretty essay step too since we learned and already know some commands to use to asses the data like the

1. Visual assesment
- We check for duplicates
- Spelling errors
- Null data
- And more. 
2. Programatic assesment
where ze use functions like (.info() .sample() sum(.duplicated()) .shape) to get more insight about the data

## Clean
This was the most difficult path of my work as I had to try and fix the errors I spoted and make the data usable I succefully noted eight (8) quality issues and thre (3) tidiness issue
Problems encountered Trying to solve:

Issue#8 : twitter_archive Some numerators are greater than the denominators and viceversa

Issue#10.twitter_archivetable: Unclear data the source column is not clear because this refrences the source of the twitte and we need the device name and not a refrence.

Issue#11.Useless Data Retweets RT and replies@' Solving these problems took me long and gave me alot of headache i finally moved to Insight and Visualization

## Insight and Visualization


In this process i tried to understand check on what to visualize the data i assessed so to plot so;e insight on ou data we had to ask our self questions like:
![image](https://user-images.githubusercontent.com/44718084/197365691-f26d46ac-625d-453f-ae76-6522e52c39d4.png)
- Where did the most tweets come from this was from the iPhone.
- Let's check to see what is the Most popular dog name which was Charlie from our plots.
- We also ploted the dog stage on a dount plot to see the most common dog stage.
- We also try to print out a relationship between favourite counts and retweets counts which was a positive corolation indicating that as retweets counts increase the favorite counts increase too we also ploted a bar chart showing the top five dog names with the highest Average Retweets countwith Abby being the dog name with the most Average retweet count.

In All this help us undersatnd the Data Wrangling and Analysing process and this was really difficults but also alot fun in the end.
![image](https://user-images.githubusercontent.com/44718084/197365703-9ef2d586-be3b-408a-b5d8-dac8d3fa7bbc.png)
