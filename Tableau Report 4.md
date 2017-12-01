## Documentation-For-Tableau-Report 4

### Group Members:
Yue Cheng
Shuwei Deng
Yinian Lyu
Erya Ouyang
Shuwen Wang

### Project Description
Nowadays, there is an increasing trend that people share their reviews towards different movies on social media. By focusing on multiple variables through social media channel, we are able to generate a more accurate visualization model to best show directors messages from consumers and predict the box office. 
Our domain contains tremendous data from both social media users and movie itself from IMDB, including number of likes and 
followers of the posts from directors, actors and movie homepage, the reviews of movie critics, movie title, genres, plot 
keywords and the casting members of the movie. The reason why we choose this dataset is that it can helps us to achieve deeper 
insights by combining ratings from registered users on IMDB with social media users on Facebook, Instagram and Twitter. 
When analyzing data, one of the primary challenges is how to screen variables, deal with null and extreme values, 
and make the dataset clean and reasonable. The color variable which includes two values: black-and-white and color is to some 
extent not useful since the distribution of color is extremely unbalanced with over 98% color movies. Therefore, it is 
meaningless to take color variable into account. The Movie IMDB link and movie title can be put outside of the dataset as an 
external reference to provide more detailed explanations about the movie. The model we build is targeted to predict the movie 
rating based on the released movie data. Thus, we are able to build a fitted model and using it to evaluate the results.

### Tableau Workbook Online
The online Tableau Workbook is in this site [Tableau Workbook Online](https://public.tableau.com/profile/shuwen.wang#!/vizhome/MovieAnalysisforIMDB5000/MovieAnalysis)

### Description of Tableau "Story"
![myimage-alt-tag](https://user-images.githubusercontent.com/34119368/33503813-28859990-d6b3-11e7-8a93-c4db1c5aeb75.png)
From score tab, We compared IMDB Score for each movie in chronological order. As we can see from the graph, we plotted a curve according to the relationship between IMDB score and Title Year. We have the peak point in 1930, which means that movies from 1930 achieved the highest average IMDB Score. As the number of movie increases every year, the IMDB score decreases gradually till 2005 and becomes stable after that. However it does not mean the movie quality is actually decreasing every year. We have more movies produced and more data sets compared with a decade ago. Some bad-quality movies dragged down the average score of IMDB, which gives us the curve we see now.

![myimage-alt-tag](https://user-images.githubusercontent.com/34119368/33503837-40820ad8-d6b3-11e7-80b9-72ff987b931a.png)
Directors are one of the reasons that one film will sell well. Highly rated movies usually have highly rated directors. The market share of the high-gross directors is shown in the following graph. As we can see, there are 27 famous directors in the graph. Steven Spielberg has the biggest part of the earnings of $4,114,233,101, following by Peter Jackson, Michal Bay and etc. The ones that have higher gross are marked with darker blue in this mosaic graph from 1 billion to 4 billion dollars gross earnings.


