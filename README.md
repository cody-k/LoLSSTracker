# LoLSSTracker

> **_NOTE:_**  There is currently a DEV OPTION for updating the API Key as I work towards obtaining a permanent API key through Riot's application process. This feature will be going away once a permanent key is obtained. If you do not have a development API Key to insert this program will not currently work.

This is a simple non-overlay tool built in C# designed to pull summoner spell data from the API and make it easier to track when a summoner spell was used.

This program uses Riot's Spectator, and Summoner APIs along with Data Dragon to process the summoner spells that are in use on the enemy team and which champion is using them. Included is a checkbox for Ionian Boots of Lucidity in order to recalculate the cooldown changes associated with that item. As well as an option to convert the cooldown time from seconds to MIN:SEC
<p align="center">
  <img src="https://user-images.githubusercontent.com/13126350/170892393-7b2c0a08-09c7-481e-b4bd-015295ce8d63.gif" alt="animated" />
</p>

# Known Issues:
• There does appear to be about a one second delay between the time you click on a spell to the time it is updated, this is due to how the tick system works, I will be looking for a way to resolve this to make it feel more immediate.
