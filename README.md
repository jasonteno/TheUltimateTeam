# TheUltimateTeam
Jason Teno and Scott Hungerford's 1.125 Final Project Deliverables

Our Tableau Dashboard is published within this Github repo.  We received Google Cloud/Big Query datasets from the team at the American Ultimate Disc League (AUDL).  The data received was league ultimate frisbee games for the AUDL.  Specifically, we looked into spatial data on the playing field to understand what parts of the field resulted in good/poor performance.

Field Layout:
X-Coordinates = 53.33 yards across; -26.67 is the leftmost sideline's X-coordinate; 26.67 is the rightmost sideline's X-coordinate; 0.00 splits the X-coordinate down the middle.
Y-Coordinates = 120 yards down; 0 is the back of the defending team's endzone; 20 is the front of the defending team's endzone; 100 is the front of the offensive team's endzone; 120 is the back of the offensive team's endzone.

Tableau Dashboard 1: Shows the results of all throws relative to field position for games we studied.  Throws that resulted in goals naturally were thrown closer to the offensive team's sidelines.  Throws that resulted in turnovers (Drops or Throwaways) occurred all over the field.  All other completed passes were densely populated in the middle of the field.

Tableau Dashboard 2: Shows the expected value of a possession (1 = Goal, 0 = Turnover) per throws occuring in each unique part of the field's grid.
