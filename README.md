# Exploring-Hacker-News-Posts

In this project, we will be working with a dataset of submissions to the popular technology site, Hacker News. The goal of this project is to explore the data and answer a few questions:

- Do Ask HN or Show HN posts receive more comments on average?
- Is there a certain time of day when posts receive more comments on average?

To accomplish this, we will be utilizing skills such as working with strings, object-oriented programming, dates and times, and data analysis.

Hacker News is a site where users can submit stories (known as "posts") and receive votes and comments. It was started by the startup incubator Y Combinator and is extremely popular in technology and startup circles. Posts that make it to the top of the Hacker News listings can get hundreds of thousands of visitors as a result.

The dataset we will be working with can be found here: https://www.kaggle.com/hacker-news/hacker-news-posts. We have reduced the dataset to approximately 20,000 rows by removing all submissions that didn't receive any comments and then randomly sampling from the remaining submissions. You can download this downsampled data from the jupyter notebook workspace or from the link provided.

The columns in the dataset include:
- id: the unique identifier from Hacker News for the post
- title: the title of the post
- url: the URL that the post links to, if the post has a URL
- num_points: the number of points the post acquired, calculated as the total number of upvotes minus the total number of downvotes
- num_comments: the number of comments on the post
- author: the username of the person who submitted the post
- created_at: the date and time of the post's submission

We will be focusing on posts with titles that begin with either "Ask HN" or "Show HN". Ask HN posts are submitted to ask the Hacker News community a specific question, while Show HN posts are submitted to show the community a project, product, or something interesting.

To start, we will import the necessary libraries and read the dataset into a list of lists. We hope this project will provide you with valuable real-world experience and help you understand these concepts more deeply. If you haven't worked with Jupyter Notebook before or need a refresher, we recommend completing our Jupyter Notebook Guided Project before continuing.
