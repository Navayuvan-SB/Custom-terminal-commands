1. First create and open a ".sh" extension (shell script) in any location (~ is prefered)

2. Now open that file.

3. Each custom commands you are creating is a function in shell script

syntax of function:

"""

function <command_name>() {

	<script or commands>

}

"""

4. We can pass the parameter to the command. Those parameter can be accessed by "$i" where i is the index of the argument. Eg : $1 - 1st argument, $2 - 2nd argument and so on.

5. After finished editing the file, we want to load the file into our present terminal.

Syntax:

"""
source <file_name.sh>

"""

6. After this step, the custom commands are only available in the present terminal. To make the available in anytime even after the reboot, we want to load the ".sh" file when system starts. For that edit the "~.bashrc" file and write the load command with the file name at the end of the file and save it.


7. To make the pre written command as your wished variable, write the following line as below in "~.bashrc" file.
	
	alias <new_command>='<old_command>'

