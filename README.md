# PIG_Demo

### Importing Project:
* Open “eclipse”, right click on “Package Explorer” window, click import.
* Select “Git”-> “Projects from Git” and click “next”.
* Select “clone url” and click “next”.
* Paste “https://github.com/shudipdatta/PIG_Demo.git” in the “url” textbox, Change protocol to “git”, and click “next”. 
* Choose “Import existing project” and click “finish”.
  
### General Information (Cloudera):

* Operating System:         Mac -> Microsoft Remote Desktop, Windows -> Default Remote Desktop, Ubuntu -> Remmina
* Machine:                  cqs-cs6304-xxx.ats.mst.edu
* User:                     cloudera
* Default Password:         stu-pass
* Change Password Command:  sudo passwd cloudera

* "Firefox already running" error solve by command:     killall -SIGTERM firefox
* "Eclipse workspace in use" error solve by command:
* cd ~/yourWorkspaceDirectory/.metadata
* rm .lock
