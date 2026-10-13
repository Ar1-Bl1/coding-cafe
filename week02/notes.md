1. The pwd command printed out the current working directory/folder which was my root folder. It displayed this: /home/arushi_18  
2. ls printed all my files and directories. ls -a also printed out all the folders and files that were hidden (files beginning with a dot) (like .bashrc, .profile, ., ..).  
3. The first column on a detailed list displays file permissions (drwxr-xr-x).
4. It works because the folder 'coding-cafe' is already in the root folder. It is a relative path since we are specifying the path from a specific folder rather than explicitly specifying the path starting from the root folder. 
5. First, mv moved a file into a different directory (week01/). Second, mv renamed the file from README-backup.md to old-readme.md. 
6. There are 20 folders on my path.  
7. /usr/bin/python3
8. They are different, because we have different operating systems. 
9. Command 'pyton3' not found, did you mean:
  command 'python3' from deb python3 (3.14.3-0ubuntu2)
Try: sudo apt install <deb name> 
This means the shell could not find pyton in any of the folders listed in the path.
10. The virtual environment directory is named .venv, and any file or directory starting with a dot is hidden from plain ls since it is a hidden folder.  
11. I can see (.venv) added at the beginning of my command prompt. It is easy to see that i'm running commands from my virtual environment.
12. No, it points to /home/arushi_18/coding-cafe/.venv/bin/python3 instead of /usr/bin/python3. Activating prepends .venv/bin to my PATH variable. This tells me that activating changed my PATH so that python is found inside .venv
13. When we ran pip list again, this time it showed the pip installation of requests and all of its dependencies as a list as compared to the first time we ran the command (in which it had listed nothing because pip hadn't installed anything).  
14. It points back to my system path (/usr/bin/python3).  
15. It stands for "human-readable," displaying file sizes in easy-to-read units like KB, MB, or GB instead of bytes.
16. The main difference is that Ctrl+C stops or interrupts a running program, while Ctrl+D tells the program that input has finished or closes the shell.