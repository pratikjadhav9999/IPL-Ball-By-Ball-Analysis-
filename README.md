IPL Ball-by-Ball Analysis

Ball-by-ball IPL data analysis using Python — batting, bowling, team, and venue performance insights across seasons (2008–2024).

Project Overview

This project analyzes ball-by-ball delivery data alongside match-level results to answer questions like:

Which batters have the best strike rate and average, and how do they perform in powerplay vs. death overs?
Which bowlers have the best economy rate and highest dot-ball percentage?
Does winning the toss actually improve a team's chances of winning the match?
Which venues are the highest and lowest scoring?
How has scoring evolved across IPL seasons?
Dataset

Two datasets are used:

matches.csv — one row per match (season, teams, toss, result, venue, player of the match, etc.)
deliveries.csv — one row per ball bowled (batter, bowler, runs, wicket details, etc.)

Data source:(https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020/data)]

Analysis Covered
Batting Analysis — batting average & strike rate, most fours/sixes, powerplay vs. death-over strike rate, 50s/100s count, boundary percentage
Bowling Analysis — economy rate, best bowling figures, batter-vs-bowler head-to-head, dot-ball percentage, powerplay vs. death-over wicket-takers
Team-Level Analysis — win percentage, toss impact on match outcome, season-wise team performance, highest totals & win margins, head-to-head records
Match-Context Analysis — most frequent Player of the Match winners, super over matches, venue scoring patterns, season-wise scoring trends
Cross-Dataset Analysis — merged views combining ball-by-ball data with match context (season, venue, toss/result)
Visualizations — season-wise run trends, over-by-over scoring heatmap, team win % chart, toss-decision vs. outcome chart
Tech Stack
Python
pandas
matplotlib / seaborn
Jupyter Notebook

Key Insights
Batting and bowling efficiency metrics (strike rate, average, economy rate, dot-ball %) computed across all seasons, with phase-wise splits (powerplay vs. death overs)
Toss decision analysis showing whether winning the toss correlates with match outcomes
Venue-wise scoring trends identifying high-scoring and low-scoring grounds
Season-over-season run trends showing how scoring has evolved through IPL history
Notes
Team names have been standardized across seasons (e.g., Delhi Daredevils → Delhi Capitals) to keep franchise-level analysis consistent despite team renames/relocations over the years.
Some analyses (e.g., head-to-head functions) are written as reusable functions — pass in different player or team names to explore further.
Author

Pratik Jadhav
