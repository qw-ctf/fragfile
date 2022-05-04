Based on ezquake upstream `fragfile.dat` with the following changes:

* Removes all TeamFortress related messages.
* Adds KTX CTF related messages.

This is required for the following new ezquake features:

* `scr_scoreboard_showflagstats 1` for showing flag pickups and captures in the scoreboard.
* `%c` in `hud_teaminfo_layout` for showing flag carrier(s).
