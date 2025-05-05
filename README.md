User Account Automation Script

What This Program Does

Setting up user accounts manually can take a lot of time. It reads an input file with user details and creates the accounts, sets passwords, and assigns groups—all without having to type commands for each person.
Normally, system admins do this one by one, but this script handles everything in one go.

How It Works

Input File Format
The script reads user information from a file, with each line containing:
Username
Password
Last name
First name
Groups 
Skipping Lines: If a line starts with a special character, the script ignores it.
Skipping Group Assignments: If a user doesn’t need to be added to any groups, a placeholder is used instead.

Running the Script
Before running, make sure the script is allowed to execute and has the right permissions. Since it makes system changes, administrator access is required.
Once ready, the script reads the file and creates users, sets their passwords, and adds them to groups automatically.

Testing with a "Dry Run"
Before making actual changes, you can run the script in test mode. It will show what commands would run without actually executing them, so you can check for errors or mistakes first.
