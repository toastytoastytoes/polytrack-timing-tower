POLYTRACK RECORD BOARD
======================

ABOUT
-----
A leaderboard for tracking Polytrack lap times between Ryder, Hunter, Elijah, and Bastian.

The website displays both Legacy Polytrack and Current Polytrack records. It automatically retrieves data from a published Google Sheets spreadsheet.


FEATURES
--------
- Legacy Polytrack and Current Polytrack leaderboards
- Legacy Polytrack opens by default
- Displays each player's times for every track
- Shows the track record and record holder
- Statistics for the fastest record and most records
- Search for tracks, times, and record holders
- Manual refresh button
- Automatic data refresh every 60 seconds
- Responsive layout for different screen sizes


FILES
-----
index.html
    The website. Contains the page layout, styling, and JavaScript.

README.txt
    This file. Explains the project.


DATA SOURCE
-----------
The leaderboard retrieves its data from a published Google Sheets CSV.

To update the leaderboard, edit the spreadsheet. The website will retrieve the updated data automatically


HOSTING
-------
The website is hosted using GitHub Pages.

To publish changes to the website:
1. Edit index.html if you want to change the website.
2. Upload the updated index.html to the repository.
3. Replace the existing index.html.
4. Commit the changes.
5. Wait for GitHub Pages to publish the update.

The homepage file must be named exactly index.html.


IMPORTANT NOTES
---------------
- Keep the Google Sheets spreadsheet published as a CSV.
- Preserve the spreadsheet's column layout unless the website's CSV-reading code is updated.
- The spreadsheet contains separate Legacy and Current Polytrack sections.
- Changes to spreadsheet records do not require rebuilding or re-uploading the website.


PROJECT GOAL
------------
Maintain a simple, convenient, and up-to-date record board for friendly Polytrack competition.

May the fastest driver hold the crown!
