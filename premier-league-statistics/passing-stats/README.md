# Premier League Statistics

This folder contains Premier League Passing Statistics scraped from FBREF.

Header | Definition
---|---------
`Rk` | Count of the rows
`Player` | Name of the player
`Nation` | Nationality of the player
`Pos` | Position most commonly played by the player
`Squad` | Team player plays for
`Age` | Age of the player
`Born` | Year the player was born
`90s` | Minutes played divided by 90
`total_Cmp` | Total passes completed
`total_Att` | Total passes attempted
`total_Cmp%` | Total pass completion percentage
`TotDist` | Total passing distance in yards
`PrgDist` | Total distance in yards that passes have traveled towards the opponent's goal
`short_Cmp` | Short passes completed (between 5 and 15 yards)
`short_Att` | Short passes attempted (between 5 and 15 yards)
`short_Cmp%` | Short pass completion percentage (between 5 and 15 yards)
`medium_Cmp` | Medium passes completed (between 15 and 30 yards)
`medium_Att` | Medium passes attempted (between 15 and 30 yards)
`medium_Cmp%` | Medium pass completion percentage (between 15 and 30 yards)
`long_Cmp` | Long passes completed (more than 30 yards)
`long_Att` | Long passes attempted (more than 30 yards)
`long_Cmp%` | Long pass completion percentage (more than 30 yards)
`Ast` | Assists
`xAG` | Expected assisted goals (xG that follows a pass assists a shot)
`xA` | Expected assists (likelihood each completed pass becomes a goal assist given the pass type, phase of play, location, and distance)
`A-xAG` | Assists minus expected goals assisted
`KP` | Key passes (Passes that directly lead to a shot)
`1/3` | Passes into the final third (Completed passes that enter the 1/3 of the pitch closest to the goal)
`PPA` | Passes into the penalty area
`CrsPA` | Crosses into the penalty area
`PrgP` | Progressive passes (Passes that move towards the opponent's goal line at least 10 yards from its furthest point in the last 6 passes, or any completed pass into the penalty area. Excludes passes from the defending 40% of the pitch.)
`Season` | Season the statistic was taken from

Source: [FBREF](https://fbref.com/en/comps/9/Premier-League-Stats)
