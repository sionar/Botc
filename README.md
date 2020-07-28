# Botc

Blood on the Clocktower script for Tabletop Simulator. This is a social deduction game that can be played between 5 and 20 players.
Since Tabletop Simulator only supports 10 seated players, extra fake seats are added into the game to fully support 20 players.

![Preview 1](https://steamuserimages-a.akamaihd.net/ugc/1030707316751255910/975C4EF83A792F7ADA96B41D0093BF8C7F36ACC2/)
![Preview 2](https://steamuserimages-a.akamaihd.net/ugc/779613613824548496/EB8A944F4688C2DEFC01897BF1F06B6280463F8E/)

**Features:**
* The characters are dealt out to the storyteller zone and are auto-tinted to the players' colors. The reminder tokens are also automatically dealt out on top of the character tokens.
* Table size can be adjusted to the number of players, between 5 and 20.
* Character setup tool.
* Night helper tool.
* Scripted player distribution chart.
* Timer tool.
* Town Square tool.
* Waitlist tool.
* Blood on the Clocktower bingo board.
* And many other quality of life features.

Here is a [youtube video](https://www.youtube.com/watch?v=cg0O1oq5VXk) explaining how to install this mod and run the game as a storyteller.

[Link to the workshop mod](https://steamcommunity.com/sharedfiles/filedetails/?id=1749093601)



*Instructions for accessing the code, modify it and push it into the game:*

Requires Atom Editor and the Tabletop Simulator package. See http://berserk-games.com/knowledgebase/atom-editor-plugin/ for full details.


In the Settings for Packages->tabletopsimulator-lua, make sure the 'Insert other files specified in source code' box is checked.


Set the 'Base path for files you wish to #include' to the local parent folder of this repository.


For example, if you have this repository saved in 'D:\Documents\My Games\Tabletop Simulator\Scripts\Botc', set the base path to 'D:\Documents\My Games\Tabletop Simulator\Scripts'


If you want to edit the scripts directly from the temp folder, uncheck the 'Insert other files specified in source code' box and reload the scripts in Atom.
