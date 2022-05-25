# tmnt_multiplayer_ai_rl
Using single agent RL to beat tmnt on multiplayer setting

Instead of having one agent interact with one character, this instance will be one agent controlling two characters at the same time.

Additional data such as two player state, screen movement, player 1 and 2 HP, monster HP (1 to 8) has been added using .json file

Since the agent will be controlling two characters instead of one, MultiBinary of 24 will be used instead of 12. The buttons that are used are defined as boolean. 

