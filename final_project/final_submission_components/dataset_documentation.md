# Dataset Documentation - Kohta

## Batting Dataset (`batting_combined_fill_na.csv`)

### Overview: 
- Contains batting statistics for teams across various leagues and years.
  
### Key Columns:
- Year: Year of the statistics.
- League: League abbreviation.
- Tm: Team name.
- #Bat: Number of batters.
- BatAge: Average age of batters.
- R/G: Runs scored per game.
- PA, AB, R, H, HR: Plate appearances, at-bats, runs, hits, and home runs.
- BA, OBP, SLG, OPS: Batting average, on-base percentage, slugging percentage, and on-base plus slugging.
- GDP, HBP, SH, SF, IBB: Grounded into double plays, hit by pitch, sacrifice hits, sacrifice flies, and intentional walks.
- LOB: Left on base.
  
### Missing Data:
- Some columns like GDP, SH, SF, IBB, and LOB have missing values.

### Summary:
- Total entries: 685

## Standings Dataset (`detailed_standings_combined.csv`)

### Overview: 
- Tracks detailed standings and performance metrics for teams.

### Key Columns:
- Year: Year of the standings.
- League: League abbreviation.
- Rk: Rank in the league.
- Tm: Team name.
- W, L, W-L%: Wins, losses, and winning percentage.
- GB: Games behind the leader.
- R, RA, Rdiff: Runs scored, runs allowed, and run differential.
- Home, Road: Home and away records.
- vRHP, vLHP: Performance against right- and left-handed pitchers.

### Missing Data:
- Columns like GB, GBsum, and vEast/West have missing or partial data.

### Summary:
- Total entries: 673

## Pitching Dataset (`pitching_combined.csv`)

### Overview: 
- Captures pitching statistics and metrics for teams across leagues and years.

### Key Columns:
- Year: Year of the statistics.
- League: League abbreviation.
- Tm: Team name.
- #P: Number of pitchers.
- PAge: Average age of pitchers.
- RA/G: Runs allowed per game.
- ERA, FIP, WHIP: Earned run average, fielding-independent pitching, and walks plus hits per inning pitched.
- SO/W: Strikeout-to-walk ratio.
- LOB: Left on base.

### Missing Data:
- Columns like HR, IBB, and LOB have missing values.

### Summary:
- Total entries: 684

