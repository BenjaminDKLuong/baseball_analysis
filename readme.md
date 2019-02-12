# Baseball Analysis Visualization with Tableau

## Link to Tableau
[https://public.tableau.com/profile/benjamin.dk.luong#!/vizhome/ProjectDataVisualization2/ProjectDataVisualization](https://public.tableau.com/profile/benjamin.dk.luong#!/vizhome/ProjectDataVisualization2/ProjectDataVisualization)

## Design
- Story point 1: I want to see the height and weight of all players. A scatter plot is a best fit for this purpose.
- Story point 2 and Story point 3: I want to see the range of height (weight) of players and how many players in certain height (weight). A bar chart is best fit for this purpose. I can see the range and the distribution of height (weight).
- Story point 4: I want to see homeruns distribution. I want to see most players make how many homeruns. Because I have one variable, I think bar chart is best fit to show the data.
- Story point 5: I want to see relationship between Avg and homeruns. Because I have 2 variables, a scatter plot is a good choice for me. I also want to see if there are any different in both-handed, left-handed, right-handed, short, tall, light_weight, medium_weight, and heavy_weight. I can color them to see the differences.
- Story point 6 and Story point 7: I want to plot avg against homerun, but I want to divide the data using median. The data is skewed, so the mean will not tell the true story. The median line will divide the data in halves, so I can easily see which players are better than others. Moreover, I want to divide the data using 80% percentiles to see where the top 20% players.


## Summary
A data set containing 1,157 baseball players including their handedness (right or left handed), height (in inches), weight (in pounds), batting average(Avg), and home runs (HR).

There are some duplicated data in the dataset, so I deleted rows that have the same name.

### Visualization
All the graphs are for finding relationship between height, weight, HR, and Avg.
Looking at the Tableau link:

- Story point 1: There are no different in weight or height between both-handed, lefthanded, and righthanded players. All data overlap each others.
![alt pic1](https://github.com/BenjaminDKLuong/baseball_analysis/blob/master/story1.png)
- Story point 2: Majority of players' height are from 70-75 inches.
![alt pic2](https://github.com/BenjaminDKLuong/baseball_analysis/blob/master/story2.png)
- Story point 3: Majority of players' weight are from 170-195 lbs.
![alt pic3](https://github.com/BenjaminDKLuong/baseball_analysis/blob/master/story3.png)
- Story point 4: This graph shows the HR data is skewed. There are a lot of players have HR under 50.
![alt pic4](https://github.com/BenjaminDKLuong/baseball_analysis/blob/master/story4.png)
- Story point 5: When plot Avg against HR, there are no different in short , tall, light_weight, medium_weight, or heavy_weight players. All the data is overlap each others.
![alt pic5](https://github.com/BenjaminDKLuong/baseball_analysis/blob/master/story5.png)
- Story point 6: Because of skewed data, it's best to analyze using median. 50% of sample is on the left side of median, 50% of sample is on the other side.
![alt pic6](https://github.com/BenjaminDKLuong/baseball_analysis/blob/master/story6.png)
- Story point 7: Here is my players' rating: Top 20% of Avg and top 20% of HR are the Best players. The Good or Great players play significant role in a game also. The Good players have higher Avg rate, and the Great players can make more HR even though their avg lower than the Best and the Good.
![alt pic7](https://github.com/BenjaminDKLuong/baseball_analysis/blob/master/story7.png)


### Conclusion
There are no different between both-handed, left-handed, and right-handed players. The graphs show the data overlap each other. We can not predict performance of a player based on height, weight, or handedness. Each player has equal chance to be successed.

