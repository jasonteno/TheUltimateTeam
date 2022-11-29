# TheUltimateTeam
Jason Teno and Scott Hungerford's 1.125 Final Project Deliverables

Our Tableau Dashboard is published within this Github repo.  We received Google Cloud/Big Query datasets from the team at the American Ultimate Disc League (AUDL).  The data received was league ultimate frisbee games for the AUDL.  Specifically, we looked into spatial data on the playing field to understand what parts of the field resulted in good/poor performance.

Field Layout:
X-Coordinates = 53.33 yards across; -26.67 is the leftmost sideline's X-coordinate; 26.67 is the rightmost sideline's X-coordinate; 0.00 splits the X-coordinate down the middle.
Y-Coordinates = 120 yards down; 0 is the back of the defending team's endzone; 20 is the front of the defending team's endzone; 100 is the front of the offensive team's endzone; 120 is the back of the offensive team's endzone.

Tableau Dashboard 1: Shows the results of all throws relative to field position for games we studied.  Throws that resulted in goals naturally were thrown closer to the offensive team's sidelines.  Throws that resulted in turnovers (Drops or Throwaways) occurred all over the field.  All other completed passes were densely populated in the middle of the field.

Tableau Dashboard 2: Shows the expected value of a possession (1 = Goal, 0 = Turnover) per throws occuring in each unique part of the field's grid.  The expected value calculation is the expected score on that possession per area of the grid.  For instance, the bottom left 0.4037 value means that 40.37% of throws that occur is that zone resulted in a goal on that possession, not necessarily that throw.  Inherently, the teams have a better chance to score if they are closer to the goal.

Tableau Dashboard 3: Shows the expected value of a possession (1 = Goal, 0 = Turnover) per throws per players throwing the frisbee.  Elite players like 'jkerr' and 'rosgar' have expanded green zones that significantly help their teams score.

Tableau Dashboard 4: Shows the expected value of a possession (1 = Goal, 0 = Turnover) per throws per team.  Plus, this dashboard shows the breakdown of all throws per these teams.  When comparing an elite team ('NY') to a lowly team ('DET'), the elite team has the entire top half of the field as a positive scoring zone while the lowly team shows some poor stats like a 0.588 expected value in an area where the rest of the league is 0.7858.
