Create Users Script
What This Program Does
This script automates the process of creating users, setting their passwords, and assigning them to groups. Instead of manually running multiple commands for each user, the script reads data from an input file and executes everything automatically.
Normally, adding a user manually requires multiple steps, but this script runs the same commands for you, saving time and reducing mistakes.

How to Use It

1. Prepare Your Input File
Each line in the input file should include:
Username
Password
Last name
First name
Groups (use - if no groups are needed)
If you need to skip a line, start it with #.


2. Run the Script
Before running, make sure the script has the right permissions. Then, execute it with the input file to create users, set passwords, and assign groups.


3. Do a "Dry Run" First
A dry run lets you test the script without making changes. It will show what commands would run, so you can verify everything before executing them.
