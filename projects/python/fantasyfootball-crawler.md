# fantasyfootball-crawler

Fantasy football is a game played by many Americans, however most are uneducated when it comes to the various in-depth statistics that are needed to "level up" your team, and potentially win big. Most websites gloss over important statistics, or don't include all of the information needed (think FantasyPros), or perhaps include too much information (think pro-football-reference). I want to build a one-stop-shop for these important statistics.

The Fantasy-Football Crawler library can now accept specified user inputs for the top players, and sort through specific players based on specific data. Before, the library would use getQBData(), getRBData(), and getWRData() to simply return DataFrames ranked and sorted based on factors that I personally thought were the most relevant. 

However, now, users can use getQBData(metrics), getRushData(metrics), and getRecMetrics(metrics) to sort QBs, receivers, and runners based on specified parameters (ex. Yds, Att), and receiving and rushing are both not limited to one position, but include all rushers and receivers across the league (ex. Rushing Data can include QBs, RBs, and WRs even), which finally allows us to incorporate players like Travis Kelce into the receiving data.

Further, an aggregate scoring method was also implemented, where users can specify a position to get a DataFrame that holds the top positional players in terms of Rushing Touchdowns, Receiving Touchdowns, and Total Touchdowns, which can be very helpful in terms of fantasy.

[fantasyfootball-crawler](https://github.com/cocobird1/fantasyfootball-crawler/tree/main)
