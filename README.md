# RemoteCat

Experimental code execution, running Mimikatz without any changes to the orginal code, this code uses syscall to do the work, establish reverse shell, Mimikatz commands must be added in:

ShellProcess.StartInfo.Arguments = "privilege::debug";

Add IP address in string IP = ""; port is default 443.

Compile with csc.exe like this: https://github.com/mobdk/compilecs 

This do not address the issue og become admin and setting SeDebugPrivilege (another time another day)
