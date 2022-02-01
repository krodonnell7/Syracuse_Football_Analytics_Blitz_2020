# Syracuse_Football_Analytics_Blitz_2020

I competed with a team of Villanova Sports Analytics Club students in the Syracuse Football Analytics Blitz Competition. Our goal was to determine the optimal run/pass ratios for an NFL team for the following zones of the field:

  • 1 - 24 Yard Line (Deep in own territory)
  • 25 – opposite 41 Yard Line (Touchback - Common Field Goal range)
  • 40 - 21 Yard Line (Common Field Goal Range, Start of Red Zone)
  • 20 - 11 Yard Line (Start of Red Zone - Middle of Red Zone)
  • 10 - 1 Yard Line (Middle of Red Zone - Goal Line)
  
For each segment of the field and win probability, we modeled the expected points added (EPA) of a pass and a run play. Using the approach of David Schmerfeld: https://davidschmerfeld.github.io/nfl-optimum-pass-run-ratio/, we found the point where the difference between running and passing EPA was a mininum. We determined this to be the point where the defense is least prepared and does not expected a run or a pass more. We cross-referenced the win probability where this point occurred with a graph for passing percentage vs win probability to determine the optimal run/pass ratio for each segment of the field. 

We also looked into optimal play action rates and three-play sequences throughout a drive. Our team compared a very pass heavy team, the Pittsburgh Steelers of 2020, with a very run heavy team, the Tennessee Titans in the same year, for these two categories. We also looked into the Baltimore Ravens three-play sequences. 

All of the graphs and descriptions for this project are available in the attached PowerPoint. 
