CIS 191 Project 3
-----------------

This is a demo site that is a simplified version of the CIS 191 website. It is
used as a testbed/training ground for Git usage and merge conflict resolution.
Git hooks are a collection of scripts that handle specific git events. This git hook copies the files in the deploy branch to the public facing www server, then restarts the server to reflect changes pushed to the repo. 

The python server creates a pid file and writes to it. It publishes the www directory online

A bare repository is similar to the repositories set up on the github server: it is ready to be pushed to. By using remote add, we can push our local repository to this bare repository just like we push to the github website. 
