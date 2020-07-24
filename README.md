Open Sprinkler Excel Programmer

Description: This excel file helps easily manage setting sprinkler zone run times. It differs from the Open Sprinkler methodology of setting zone run times because it sets times according to when sprinklers will be finished running instead of starting.

Features:
1) Zones are set up to be finished by a specified time instead of starting at a certain time.
2) Zones can be flagged as "sidewalk zones." Sidewalk zones can have a different finish time (ie earlier in the morning), so you don't get your neighbors who are jogging wet. Be a better neighbor!

Requirements:
Any Office version that can open xlsb files with VBA enabled. No Office 365 online documents.
.NET 4 runtime required for MD5 hash of password
Curl for windows: https://curl.haxx.se/windows/

How to use:
Download Curl for Windows. Save curl.exe to a permanent folder. Set the full path to curl.exe on the Control tab.
Station run times are set on the Programs tab. Enter run times as hours:minutes. Note that the cells must be formatted as text and not as time. Excel stores dates and times differently from text, so this would cause an error.
Go to the Control tab and set the Open Sprinkler controller IP address and password. Set desired sprinkler finish times. If you have a station delay set in Open Sprinkler, set it on this tab in seconds so start times can be correctly calculated. Set the Curl path if you have not already done so. Note: if you don't want to use sidewalk zones, set both to the same end time.
Look to the Zone Options tab where you can flag zones as being sidewalk zones. Just place TRUE next to each zone you want to end early.
The Stored Programs tab is a handy place to copy/paste copies of schedules to easily restore later.

Once everything is set up properly, click the Save to Controller button on the Programs tab. Station run times will be saved to one program for each day of the week: "Auto_Monday," etc. These 7 programs will be updated each time you click the save button.

Support: Note I can only offer very limited support due to time constraints.
