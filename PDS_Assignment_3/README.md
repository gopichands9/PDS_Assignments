# PDS_Assignment_3
<h3> Name: Gopichand Seethi </h3>
<h3> Id: 16322445 </h3>
<h3> Email: gsp5b@umsystem.edu </h3>

<h1> Twitter Data Analysis </h1> 

<h3> Libraries required </h3>

pandas </br>
nltk </br>
wordcloud </br>
matplotlib </br>

<p> This project analyzes text data from tweets pulled from Twitter. The goal is to preprocess the text data by performing tokenization, stop word removal, and word frequency counting. We will then create word clouds using the most frequent words in the dataset. </br>

<h3> Dataset </h3>

<p> The dataset we are using contains tweets pulled from Twitter. The data file is named tweets.csv and is located in the same directory as the Python script. The dataset has the following columns </p> </br> 

UserName: The Twitter handle of the user who posted the tweet </br>
ScreenName: The display name of the user who posted the tweet </br>
Location: The location of the user who posted the tweet </br>
TweetAt: The date when the tweet was posted </br>
OriginalTweet: The text of the tweet </br> 

<h3> Code </h3>

Loads the dataset using pandas. </br> 
Performs tokenization by splitting the text corpus into individual words. </br>
Removes stop words using the nltk library. </br>
Counts the frequency of each word using the Counter class. </br>
Creates a word cloud visualization using the wordcloud library. </br>
Displays the word cloud using matplotlib. </br>

