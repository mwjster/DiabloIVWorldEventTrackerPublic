# DiabloIVWorldEventTrackerPublic
World Event Tracker for Diablo IV by: Emjay Jenkins

This app can be run as a personal world even tracker overlay for Diablo IV with the ability to change the opacity all the way down to 0.1 with different size modes so it does not interfier with the game. This can also be setup on a virtual machine with a discord webhook for world event reporting to your Discord channel. 

Future plans:
I have also created a simple Discord bot that will help keep your channel clean from the channel reports. Basically once the app posts to the channel the Discord bot will detect the message then delete it after 15 minutes. The bot is still in testing and will be included in future releases.

Changelog:
0.1.0 - Alpha ends, Closed beta begins 
0.1.1 - Added tracking for upcoming events
0.1.2 - Added tracking for what boss is coming in future events
0.2.0 - Mini mode
0.2.1 - General code fixes/cleanup
0.2.2 - General code fixes/cleanup
0.2.3 - General code fixes/cleanup
0.2.4 - Fixed Helltide reporting incorrectly while the 5 min alert was in progress and a color glitch in the alerts.
0.2.5 - Blood Harvest Tracker added
	 -- Streamlined various code
	 -- UI choices are now saved and reloaded when app is started
0.2.6 
	  - Added saved settings for info windows font size. Clicking the windows will cycle the font sizes.
     a- Adjusted boss and helltide reporting in mini mode.
	 b- Corrected code that would enable alert settings automatically in mini mode on startup.
0.3.0 
	  - Added discord alerting support via webhook.
0.3.1
	  - Improved sanity checks for Discord webhook info.
	  - Improved visual alert for World Boss, Text will now present yellow 15-5 min before then alert as normal
0.3.2
	 a- Updated boss tracking clocks
	 b- Improved Developers Tools to help with Boss clock calibration when Blizzard changes the timers in the future.
	 c- Added d4planner.io to Helltide maps.
	 d- Fixed bug the would load the incorrect font size from settings
	 e- Created first run detection to install program font
0.3.3
	  - Fixed Discord not saving and loading properly on next app start.
0.3.4
	  - Added Tool Tips.
	  - Improved some transition code to make things a little more smooth when transitioning between the different modes.
0.3.5
	  - Recalibrated World Boss clock, again. (There is to much mixed information about the boss rotation out there)
	  - Sanity checks for config file. App will now detect bad config settings and rewrite the config to default if validation fails. (this will most likely happen only if someone manually edits the config file incorrectly.)
	 a- Fixed a sanity conflict in config file verification that caused a never ending loop of config reset in certian conditions.
	 b- Added delay to discord reporting timer to prevent double posting.
1.0.0	 
	  - Fixed a logic error in which boss was being reported as spawning next to discord.
	  - Beta test complete. Cleaned up unused code and prepared app for public release.
