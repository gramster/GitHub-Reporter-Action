# github-reporter

A GitHub action for generating useful reports from GutHub issues using [ghreport](https://github.com/gramster/ghreport).
The reports are by default markdown files that are committed to the repo the action is run in, in a folder called
reports. The files are named with the day of the week, so ideally this would run once per day and you would have a 
rolling window of seven reports for the past seven days. The folder, file name template, and number of days for
which to consider changes 'new' are all configureable. 
