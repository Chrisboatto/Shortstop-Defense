**Outs Above Average**

Outs Above Average (OAA) is a key metric used to determine a defender's skill lever compared the average at his position. OAA is defined by Statcast as: a range-based metric of skill that shows how many outs a player has saved. Prior to 2020, OAA was an outfield-only metric. But it has been expanded to include infielders. OAA is calculated differently for outfielders and infielders. Outs Above Average for outfielders starts with Catch Probability, which takes the distance an outfielder must go, the time he has to get there, and the direction he travels to put a percentage of catch likelihood on each individual batted ball. OAA for outfielders is the season-long cumulative expression of each individual Catch Probability play. For example, if an outfielder has a ball hit to him with a 75 percent Catch Probability -- that is, one an average outfielder would make three-quarters of the time -- and he catches it, he'll receive a +.25 credit. If he misses it, he'll receive -.75, reflecting the likelihood of that ball being caught by other outfielders. Outs Above Average for infielders takes the following factors into account.

• How far the fielder has to go to reach the ball ("the intercept point").
• How much time he has to get there.
• How far he then is from the base the runner is heading to.
• On force plays, how fast the batter is, on average. (A runner's average Sprint Speed is used in the calculation, rather than his Sprint Speed on that particular play. For new players with no data, a league-average -- 27 ft/sec -- score is used; once the player qualifies for the leaderboard, all of his previous plays are re-run.)



This assignment uses the shortstop_defense data set to recreate the OAA metric using its attributes. I used a Random Forest predictive modeling scheme to determine what defender was best at fielding his position.  The ROC Graph below shows how well the model worked in predicting the scores.



![Image of ROC Graph](https://raw.githubusercontent.com/Chrisboatto/Shortstop-Defense/main/ROC%20Graph.png?token=AKUDE7BFNXQGH7NW3QRJQBLADKZLI)

