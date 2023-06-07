
# LESSONS AFTER MARKDOWN AND COMMAND LINE 
To was an insightful day. I got to learn about how to write **_Markdown_** and some important commands in the **_UBUNTU_** terminal
## Below is a table of some Markdown 
*SYNTAX* | *FUNCTION*
---- | ----- 
'#' | This help create headers. The number of '#' determines the size of the header  
'[]()' | This synthax creates a hyperlink  
'![]()' | This help add an image  
'** **' | This help create a bold text  
'* *' | This help create an italic text  

I learned this and many other important synthaxes  
## COMMAND LINE AND GIT FLOW
- ```pwd``` - prints the directory(folder) the user is currently at or has opened    
- ```ls``` - shows the list of files or folder in a directory(folder)  
- ```cd``` - helps to change directory(folder)  
- ```mkdir``` - use to create a new directory(folder) 
- ```touch``` - use to create a file in any format  
### Examples
- ```cd projects``` - changes diretory to the projects directory(folder)  
- ```mkdir new-project``` - creates a new directory called _new-projects_  
- ```touch new-project/newfile.md``` - creates a new markdown file called _newfile_  
- ```cd ..``` - move back to the previous directory(folder)  
- ```ls projects/new-project``` - shows the list of files in the new-projects 
#### GIT FLOW STEPS FROM REPO TO PUSH 
- Create Repo on Github  
- Copy the SSH key  
- OPen UBUNTU and create the directory to save the project using ```mkdir```  
- Use the ```git clone + SSH Key``` to clone the Repo locally  
- Use ```Code ..``` to open the VSC and edit as you please  
- ```git status``` helps to check the status of the whole process
- ```git add .``` adds all the changes, you can add specific changes as well by replacing the '.' with  the file name  
- ```git commit -m 'comments'``` commits the changes with the message flag to add a reason for the update  
- ```git push``` push all the changes onto the cloud  