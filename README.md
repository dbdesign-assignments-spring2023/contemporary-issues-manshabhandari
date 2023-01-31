# SQL and Data Science VS Statistics

Find any two articles in relatively recent newspapers or journals with different viewpoints on a particular database or data-related issue. Write a response of at least a two paragraphs to each article.

## ARTICLE 1
["Some opinionated thoughts on SQL Databases"](https://blog.nelhage.com/post/some-opinionated-sql-takes/) - 30 March 2021

The author of this article focuses mostly on expressing their opinions on SQL engines, but also looks at the use of open-source SQL engine. They talk about the role SQL plays in the transactional functionality of databases, how it manages complexity and mediates isolation and consistency properties.
<br>
<br>
The first thing they bring up is how they believe that "String concatenation is a bad API". They talk about how pasting strings to construct query strings is highly prone to error and inefficient. I agree with what they say completely, string concatenation is generally known to be a form of bad practice. As the author of the article talks about, it leads to issues with its performance, and in addition to this, it leads to concerns with security. Applying string concatenation to user-provided data is prone to SQL-injection attacks (results in unauthorised access to private data). 
<br>
<br>
They also talk about their aversion to "query planners" because of how they feel it is "the antithesis of predictability" (quoted from the article). I agree with what they say to an extent, that an increase in complication leads to the system getting more and more inefficient. However, at the same time I also feel that the benefits outweigh the losses, and the way that the query planners use techniques and algorithms in different ways helps determine highly efficient ways to execute the queries, and also performs some optimisations that compilers perform.

## ARTICLE 2
["Is data science just a rebranding of statistics?"](https://www.topcoder.com/thrive/articles/is-data-science-just-a-rebranding-of-statistics)

This article looks at whether data science is just statistics, just in a fresher, revamped way. The author looks at the similarities, disimilarities and how data science is often confused with statistics.
<br>
<br>
Their main point here is that if one looks at visualisation, algorithms and mathematical modelling as forms of statistics, then yes, data scientists are almost the same as statisticians, essentially leaving the actual conclusion to the reader. I agree with the points that they bring up, but I also believe that there is the potential to go deeper into the topic and really look at why so many people think that data science is just statistics and reach a more rounded conclusion. 
<br>
<br>
Data science and statistics both look at the analytical side of things - they focus on the interpretation of data. But this is also where they start to differ, the field of statistics is more mathematically based, it looks at quantitative data and the field of data science is more multidisciplinary as it looks to extract knowledge in various forms through scientific processes, methods and systems. Due to this, I think a better conclusion to the topic would be that data science and statistics are very similar at their roots, but oncce they start to branch out they tend to take on extremely different roles.  