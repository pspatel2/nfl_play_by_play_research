## A description of each of the columns is as follows

*	game_date: simply the date of the game corresponding to the given data row
*	yardline_100: This field was generated to improve interpretability of field position for a machine/computer. The value is set to where a team is on the field between 0 – 100.  For example, a value of 80 would mean you are on the opponent’s 20 yard-line or 20 yards away from the goal-line the team is trying to score at
*	half_seconds_remaining: number of seconds remaining in the half 
*	game_seconds_remaning: number of seconds remaining in the full game
*	down: the down number (1-4). See previous section for explanation of what a down is
*	play_type: indicates if the play that was called was either a run or a pass
*	yards_gained: states how many yards were gained as a result of the play
*	posteam: Name of the team who ran the given play
*	shotgun: a binary flag to represent if the play that run was in the shotgun formation
*	score_differential: the difference in score between the two teams at the time when the given play was ran
*	desc: a text description of the play that was run
