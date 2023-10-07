# wifi
WIFI PASSWORD PYTHON
#! py

#    Import subprocess so we can use system commands.
import subprocess

#    Import the re module so we can make use of regular expressions. 
import re

#    Python allows us to run system commands using the function 
#    provided by the subprocess module; 
#    (subprocess.run(<list of command line arguments go here>, <specify the second argument if you want to capture the output>)).
#
#    This script is a parent process that creates a child process which 
#    runs a system command and will only continue once the child process 
#    is completed. 
#
#    To save the contents that get sent to the standard output stream 
#    (the terminal), we must first specify that we want to capture the output.
#    To do this we specify the second argument as capture_output = True. 
#    This information gets stored in the s
