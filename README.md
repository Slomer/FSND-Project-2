# Swiss Tournament schema and python api
## Description
This is a project submission for the Udacity full stack web dev nanodegree.  Project 2: Swiss Tournament database schema and python api.

##Steps to run
1. This requires the Udacity support repo found [here](http://github.com/udacity/fullstack-nanodegree-vm) as well as vagrant and virtualization software such as virtualbox.  Honestly, if you aren't from Udacity this repo is unlikely to prove very useful to you.
2. copy tournament.py, tournament.sql, and tournament_test.py into the folder vagrant/tournament folder
3. SSH into the virtual machine using Vagrant SSH
4. From the vagrant/tournament folder in the shell, run *psql -f tournament.sql* to build the tables and view
5. From that some folder, run *python tournament_test.py* to test the schema and api