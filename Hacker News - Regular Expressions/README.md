# Using Regular Expressions to Clean Hacker News Data
Hacker News is a site started by the startup incubator Y Combinator, where user-submitted stories (known as "stories") are voted and commented upon, similar to reddit. Hacker News is extremely popular in technology and startup circles; stories that make it to the top of Hacker News' listings can get hundreds of thousands of visitors.

The dataset we will be working with is based off this CSV of Hacker News stories from September 2015 to September 2016. The columns in the dataset are explained below:

1. id: The unique identifier from Hacker News for the story
2. title: The title of the story
3. url: The URL that the stories links to, if the story has a URL
4. num_points: The number of points the story acquired, calculated as the total number of upvotes minus the total number of downvotes
5. num_comments: The number of comments that were made on the story
6. author: The username of the person who submitted the story
7. created_at: The date and time at which the story was submitted

## Objectives

1. Understand the type of data collected
2. Extract text using regular expressions techniques
3. Separate the text foundin a website URL and make sure it organized into a new structure for analysis
