# Interview: NBA Data Analyst Report for the Utah Jazz


<img src="images/jazzbear.gif?raw=true"/>

## LET'S GO JAZZ!
Growing up in Southern Utah, the closest professional sports team was the Utah Jazz. Back when legends John Stockton and Karl Malone were at the peak of their performance. I loved going to games, cheering with the Jazz Bear and reppin' the beautiful unique purple mountain jersey that was ahead of their time. It's still a hard pill to swallow the game 6 Jordan push-off from the 98 finals. If anybody else knows what I'm talking about, you are a true Jazz fan. I've followed them throughout my life and I have a great camaraderie with fellow Jazz fans around the globe.

## Why?
For this project I am “interviewing” with the Utah Jazz for a Data Analyst role. I will be using Tableau public to provide insights on several players with the hopes of finding an impactful free-agent.

## Questions I'm Looking to Solve
_What position is most efficient at shooting 3-pointers for each team?
How did individual players perform last season in terms of points, assists, and total rebounds?
What were the total points for each team and how much did each player contribute?
What players had the most assists in every position?_

## Major Takeaways
SG position is the most efficient at shooting 3-pointers for every team
Power Forwards are now the lowest assist to points position
The Lowest scoring Team made it to the NBA finals
Nicola Jokić is on a whole other level

## The Data
The dataset used for this project can be found [here](https://www.basketball-reference.com/leagues/NBA_2023_totals.html) and covers the 2022-2023 NBA season. There are 31 columns and 813 rows of data. Some players have more than one row of data if they were traded during the middle of the season.

## Analysis

### _What position is most efficient at shooting 3-pointers for each team?_

<img src="images/heatmap.png?raw=true"/>

Typically when thinking of 3-point shooting, the Shooting Guard (SG) position comes to mind as it states within their name. They are meant to shoot, and you'd hope they would be good at their role. Some of the greatest NBA shooting guards of all time come to mind like Ray Allen, Kobe Bryant and Michael Jordan. This is because of their shooting efficiency and ability to create open chances. When the game was on the line, you knew who was going to shoot. However, the 3-point game has changed a lot in the NBA in recent years. More and more centers and power forwards (usually seen as in the post players) are increasing their shooting range into 3-point land. Some centers shoot 1 time during the season and make it (100%) where others shoot a lot but don't make it that much (Brooke Lopez had 364 attempts and made 37.4%). But the most efficient center from last year was Al Horford (325 attempts and 44.6%).

Even though the Center position has the lowest overall 3-point shooting percentage from Figure 1 (see the row that says TOT), it's not by much. **All 5 positions are within a 6% range**. No one can be overlooked. Every position on the court can have a very capable three-point prowess.

### _How did individual players perform last season in terms of points, assists, and total rebounds?_  

<img src="images/bubble.png?raw=true"/>

Figure 2 shows the comparison between point and assist totals by the use of a scatter plot. Adding total rebounds allows us to measure a third variable, and these are weighted by the size of the dot. It makes sense that Centers are leading the way with rebounds(seen with the heavier dot), as they are the tallest ones on the court. And it's not too surprising that point guards have the most assists, as seen by the green trend line. One of the main duties for the point guard is to facilitate the offense and distribute the ball. **What is surprising to me is that Centers have a greater assist percentage than Small Forwards**. 2 Centers in particular have greatly influenced that trend line, namely Nikola Jokić and Damontas Sabonis.

The NBA league averages for assists and points scored are noted with dotted grey lines with values of 102 and 461 respectively. The players located at the top right of the figure are outliers or the All-Star caliber players. Players like Trae Young have a high point to assist ratio, but a rather low assist measure. Whereas you have a player like Joel Embiid, the leage MVP, who has a high point and rebound ratio but low assist measure. Then there are players like Nikola Jokić and Luka Dončić that are hitting heavy in all three categories (Triple Doubles) in the upper-right corner: truly amazing outlier players as they have such unique skill set. It's no wonder Jokić won the league MVP last year and the Finals MVP this year. His statistics for this year were 24.5 points per game, 11.8 rebounds per game and 9.8 assists per game. The points and rebounds were lowered but the assists went up from last year.

My recommendation for the Utah Jazz would be to look at the different outliers based on this figure and see if they can sign someone who is performing really well in the triple-double figure like Scottie Barnes SF.

### _What were the total points for each team and how much did each player contribute?_

<img src="images/stacked.png?raw=true"/>

The stacked bar chart in figure 3 shows total season points scored by every team in descending order and is broken up into color blocks weighted by the number of total points scored per player. The top scoring team in the league was the Sacramento Kings (9,898 pts) and the lowest scoring team was the Miami Heat (8,977 pts). Almost 1000 pt difference! What's interesting to me is that the Miami Heat went to the NBA finals even though they were the least scoring team. 

It goes to show that the games aren't just won by points, but defense plays a vital role in winning. Generally, the top scoring teams had the most consistency from their top players. Although, it is worth mentioning that the Miami Heat had more points from their big man Bam Adebayo then their All-star captain Jimmy Butler. **Scoring is not always the most important thing**.

### _What players had the most assists in every position?_

The team general manager is looking to improve the team's assist numbers for this upcoming season. They'd like to know what players had the most assists in every position.

<img src="images/treemap.png?raw=true"/>

Figure 4 is a tree map graph that easily shows who the top assisters are for each position. The larger the box, the higher number of total assists. As expected, the Point Guard position has the most assists. Russell Westbrook, shown top left, is by far the best assister (1102) in the league getting almost 2 times more than the second highest assister by position, Nikola Jokić (678). It's really interesting to note that the next top assist position after the Point Guard is the Center position. But this is in part because of the unique skillset of Jokić, as mentioned earlier. Shooting guards, I understand, because they are focused on shooting, so I would expect them at the bottom position for assists. The top assister for shooting guards is Dejounte Murray (448).

Now, keep in mind this is not an average. So not every center is more assist heavy than shooting guards. **This is showing the top assisters in each position**. Rounding off the top assisters per each position: there is Josh Hart (580) for Small Forward and Draymond Green (500) for Power Forward.

## Conclusion
To review the key findings found throughout this interview and project, I found that the SG position is the most efficient at shooting 3-pointers for every team in the league, which makes sense. What was interesting about our findings is that Power Forwards are the lowest to assist to point position. This might become the next position of change as we have greatly seen improvement in the center position.

The Miami Heat were the lowest scoring team in the league but made it to the NBA Finals which proves scoring isn't everything. And lastly, I just want to point out how incredible Nikola Jokić is at 6' 11". He was leading or close to leading just about every category out there. His hard work has paid off and it's clear to see why he is an MVP and Champion.

After completing my analysis of possible free agents to sign, I have learned that you need to have more than just shooting and assists to be a top player of a team or the league in general. Every position has the capability of being an elite player in today’s NBA, so you really need to scout according to your needs.

### Recommendations
As far as the Utah Jazz is concerned, I would look into getting the following free-agents: Fred VanVleet for PG, Max Strus as SG, Cameron Johnson as SF, Draymond Green as PF, and/or Brook Lopez as C.

Thank you for reading all of this. If you have any questions feel free to comment below or connect with me [Brock Johnson](https://www.linkedin.com/in/n-brock-johnson/) on LinkedIn.

I am looking for new opportunities and roles in the data world, so if you hear of any or are in the market please reach out, thanks!
