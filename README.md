This repository contains a script that when executed will create different files and directories,configure some settings,do a health check for python, and finally handle system signals.

*The name of the script is setup_project.sh*
To execute the commands in setup_project.sh 
use: bash setup_project.sh or ./ setup_project.sh

It will immediately give a pop up message to enter a directory name.For me, I named it Cohort2 
The script will create a parent directory called attendance_tracker_Cohort2
In the parent directory, there will be two directories, Helpers and reports, and one python file called attendance_checker.py.
In the Helpers directory, there will be two files. One called assets.csv annd another called config.json,
In the reports directory, there will be one file called reports.log.
After the creation of all these files and directories, it will immediately state that they've been created.

Next, it will immediately ask if you'd what to update the attendance thresholds.
You can either choose yes or no. If you select yes, it will allow you to update and the new values will reflect inside the config.json file.
If no, then there won't be any changes.

After all that, it will run a health check to make sure python is installed.

Lastly it will slow down for ten seconds and if you press CTRL + C bundle the current state of the project directory into an archive and named attendance_tracker_Cohort2_archive.

To conclude, this repository consists of a script that help you modify a student attendance tracker with ease and without error.
