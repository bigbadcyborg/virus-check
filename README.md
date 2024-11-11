# simple virus-check for windows


View Established Connections in Terminal:
	
 	netstat -nbf
	
View specific port:
	
 	netstat -nbf | find "4080"
	
Kill a process:
	
 	taskkill /im fileName.exe /f
	
	
Process Hacker:
This is a handy multipurpose tool for monitoring system resources, debugging software,
and detecting malware:
	https://github.com/PKRoma/ProcessHacker

To view active network connections go to Network tab. To view .dll files, right click
 on a connection and click properties. Then, you can right click on the .dlls for further
 inspection.


To check Startup Malware:
	
 	press Windows Key+R and type shell:startup

Another directory to check for startup programs:

    -go to regedit
    -go to Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Run
    -inspect for suspicous activity

