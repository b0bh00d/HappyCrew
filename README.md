<p align="center">
  <img width="70%" alt="Happy Crew" src="https://user-images.githubusercontent.com/4536448/210460382-cf890493-f1be-498f-9e1c-82bf589e2fb7.png">
</p>

# X4 Foundations: Happy Crew
This extension for X4 Foundations will monitor workforce levels in player-owned factories and issue an alert when it drops more than 10% in any given check cycle (default is 5 minutes).  Such a drop is usually indicative of a station losing its workers, and that can severely impact production efficiency if it isn't quickly addressed.

Additionally, the extension will keep an eye on workforce support supplies--food rations, medical supplies, soja husks, etc.--and warn the player if those levels in a station drop below a 20% threshold.  Such low supply levels are often the precursor to the exodus of a station's workforce, so taking action on these alerts can usually avoid more disastrous results.

Unlike [Happy Station](https://github.com/b0bh00d/HappyStation), this mod will not take any actions on the player's behalf.  It will only notify the player, using unique audio cues and notification highlights, that a condition needs their attention.  It is up the player to take action to avert (or correct) disaster.

![notification](https://user-images.githubusercontent.com/4536448/210473740-08739e7c-e4ff-4f18-a2df-1e00420d665e.jpg)

## TODO
As with [Happy Station](https://github.com/b0bh00d/HappyStation), I need to see if there is a way to allow the player to configure the threshold numbers used by the extension.  Right now, they are hard-coded at &gt;10% for drops in workforce numbers between checks, and &lt;20% levels on personnel supplies, before alerts are displayed to the player.  Check intervals are hard coded at 5 minutes.

## Installing
You can do a git clone of this repo into a folder called "HappyCrew" in your game's local `extensions` folder, or you can simply extract the provided release into the same location (it's already bundled in its target folder).

# §
You might also find [Happy Station](https://github.com/b0bh00d/HappyStation) to be a useful X4 mod.  Have a look!