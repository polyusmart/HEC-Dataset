# HEC-Dataset
This is Dataset of our paper *Hashtags, Emotions, and Comments: A Large-Scale Dataset to Understand Fine-Grained Social Emotions to Online Topics* [\[pdf\]](https://polyusmart.net/pdf/ding2020hashtags.pdf)

You can download it from [OneDrive](https://1drv.ms/u/s!AhlpLCotyrgNu2N48OKtFf9IBLTt?e=g6gQuH)

# Files
There are two files of our datasets:

1. hashtag&emotion.txt
It contains hashtags and their emotion votes.
2. hashtag&comment.txt
It contains user comments involved in the discussion initialized by a hashtag.

# Data structure
The data structure is described in the following.

1. hashtag&emotion.txt
	Each line consists of six fields: <Hashtag ID>, <Hashtag Text>, <Total # of Voters>, <Rank 1 Emotion>, <Rank 2 Emotion>, <Rank 3 Emotion>. Fields are devided by Tab. The top three emotions shown with the emoji (in []) and # of voters, seperated with a colon.
2. hashtag&comment.txt
	Each line consists of three files: <Comment ID>, <Hashtag ID>, <Comment Text>. Fields are divided by Tab.

# Important Notes:
1. Both hashtag&emotion.txt and hashtag&comment are in Chinese and encoded with UTF-8.
2. The data of our dataset is sorted in alphabetical order.
3. The dataset is released under a Creative Commons Attribution 3.0 Unported License (http://creativecommons.org/licenses/by/3.0/).
