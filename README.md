# Exploring-Hacker-News-Posts
In this project, we'll work with a dataset of submissions to popular technology site Hacker News.

This guided project brings the following skills together for some real-world practice:

How to work with strings
Object-oriented programming
Dates and times
Next, we'll use all of these skills to complete a data analysis project.

Working on guided projects will give you hands-on experience with real-world examples, so we encourage you to not only complete them but to also take the time to really understand the concepts.

We've made these projects challenging to prepare you for the real world, so don't feel discouraged if you have to refer to additional lessons. If you haven't worked with Jupyter Notebook before or need a refresher, we recommend completing our Jupyter Notebook Guided Project before continuing.

In this project, we'll work with a dataset of submissions to popular technology site Hacker News.

Hacker News is a site started by the startup incubator Y Combinator, where user-submitted stories (known as "posts") receive votes and comments, similar to reddit. Hacker News is extremely popular in technology and startup circles, and posts that make it to the top of the Hacker News listings can get hundreds of thousands of visitors as a result.

You can find the data set here, but note that we have reduced from almost 300,000 rows to approximately 20,000 rows by removing all submissions that didn't receive any comments and then randomly sampling from the remaining submissions. You can download this downsampled data here or from the jupyter notebook workspace by clicking File -> Open -> hacker_news.csv -> File -> Download.

Below are descriptions of the columns:

id: the unique identifier from Hacker News for the post
title: the title of the post
url: the URL that the posts links to, if the post has a URL
num_points: the number of points the post acquired, calculated as the total number of upvotes minus the total number of downvotes
num_comments: the number of comments on the post
author: the username of the person who submitted the post
created_at: the date and time of the post's submission
We're specifically interested in posts with titles that begin with either Ask HN or Show HN. Users submit Ask HN posts to ask the Hacker News community a specific question. Below are a few examples:

Ask HN: How to improve my personal website?
Ask HN: Am I the only one outraged by Twitter shutting down share counts?
Ask HN: Aby recent changes to CSS that broke mobile?


Likewise, users submit Show HN posts to show the Hacker News community a project, product, or just something interesting. Below are a few examples:

Show HN: Wio Link  ESP8266 Based Web of Things Hardware Development Platform'
Show HN: Something pointless I made
Show HN: Shanhu.io, a programming playground powered by e8vm


We'll compare these two types of posts to determine the following:

Do Ask HN or Show HN receive more comments on average?
Do posts created at a certain time receive more comments on average?
Let's start by importing the libraries we need and reading the dataset into a list of lists.
