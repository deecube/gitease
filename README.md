# gitease
A simple shell script for simplifying the git commit process from the command line

`gitease` has the following options:

* `-s` : show status
* `-a` : add all to the staging area
* `-m` : commit with message provided as a parameter
* `-p` : push with the desired branch provided as a parameter

The `gitease -sam "Message" -p master` command would show the current status of the repository, add all files, commit the files with the message "Message" and finally push to the master branch of the repository.