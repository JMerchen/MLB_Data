# Decision-Plus
Metric for MLB batter decision making.

### Definitions
***Correct Percent:*** The percent of pitches where the batter correctly identified to swing or watch.
\
***Swing Percent:*** The percent of pitches identified for the hitter to swing at that they did swing at.
\
***Hold Percent:*** The percent of pitches identified for the hitter to watch that they did watch.
\
***Precision:*** The percent of pitches that were swung at that were identified to be swung at.
\
***Decision:*** The sum of the player's Correct Plus, Swing Plus, Hold Plus, and Precision Plus.
\
***Plus:*** Each of the metrics compared to the MLB average for the metric (A plus metric of 100 denotes the average MLB player for the metric).

### Notes
1. Identifying pitches to be swung at was accomplished by comparing the player's yearly OPS based on the pitch type, location, and pitcher handedness to the player's OPS over their previous 100 at-bats.
2. Total Score was calculated by adding the player's Decision Plus to the average of their OPS Plus and BABIP Plus over their previous 100 at-bats.
