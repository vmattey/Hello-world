# Hello-world
Trial
Ls – for list of shorts
/etc – for listing contents of the directories
-l is an option used in ‘ls’ command for long or detailed listing
pwd – present working directory
echo $[something] – to know about the something
ls -- help is used for listing out all the options available for the command
hit Tab Key for listing out all the possibilities for a particular command


The first character in the very first column (of ls -l) indicates the entity type.

-         	regular file
b	block special device
c	character special device
d	folder
l	symbolic link
p	pipeline
s	socket

VAR:-SOMETHING declaration temporarily sets value of VAR to SOMETHING if and only
if the value of VAR is empty. If VAR is not empty to begin with, VAR:-SOMETHING
declaration retains VAR's original value.

VAR:=SOMETHING declaration permanently sets value of VAR to SOMETHING if and only
if the value of VAR is empty. If VAR is not empty to begin with, VAR:=SOMETHING
declaration retains VAR's original value.

Repeating the previous command
Suppose that one has already executed a rather long command (e.g., cd /usr/local/share). Further suppose that one needs to re-execute the same command once more. The Linux OS provides the following ways to accomplish this task.

Use the UP Arrow key once and then press the Enter key
Type !! and press the Enter key
Type !-1 and press the Enter key
Press CTRL + p (i.e., press the p key while holding down the control key), and press the Enter key

In the above example, for instance, #182 refers to running ls -latrh ${HOME}/.ssh command on 2017-06-19 at 11:17:47 am. Suppose that one needs to re-run this very specific command. Instead of typing it all over again, one can simply type the following and press the Enter key.

!182
