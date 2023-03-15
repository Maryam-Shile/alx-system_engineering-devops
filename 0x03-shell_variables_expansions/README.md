alias ls='rm*' Created a script that creates an alias.
Create a script that prints hello user, where user is the current Linux user. - echo Hello $(whoami)
Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program. - PATH=$PATH:/action
If the path be beautiful, let us not ask where it leads. - echo $PATH | tr ":" "\n" | wc -l
