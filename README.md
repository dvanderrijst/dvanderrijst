### Hi there 👋

<table border="0">
 <tr>
    <td><b style="font-size:30px">Title</b></td>
    <td><b style="font-size:30px">Title 2</b></td>
 </tr>
 <tr>
    <td>Lorem ipsum ...</td>
    <td>Lorem ipsum ...</td>
 </tr>
</table>


Donna getting started with github

`ls` show list of directory you are in.   
`mkdir {Name_of_new_directory}` make a new directory.   
`cd {Name_of_Directory}` open a directory.     
`cd ..` go a directory back.    
`open {name_file}` open a file.   
`cat {name_file}` concatenate files and redirect output in terminal. 

`git status` before adding to see what you have changed
`git branch` to see what branch you are in
`git checkout donna-website` to go to the branch donna-website
`git fetch` retrieve information about the branch/repo/etc from github

`git add .` adds a change in the working directory to the staging area. It tells Git that you want to include updates to a particular file in the next commit.   
`git commit -m "{name of what you did}"`give push a name.     
`git push` push it back on github.  
`git clone {url_github}` get a clone of the codes on github.(Password here is found on Github/Settings/Developer settings/Personal Access tokens) This will be downloaded in the current directory.  
`tail -f` displays the last ten lines of the file and monitors the file for any new changes (live).  
`more {name file}` shows txt of the file in terminal output

`{package} install -r requirements.txt` installing a package as pip3.   
`{language} -m spacy download en_core_web_sm` installing a language as python.  
these packages are now locally downloaded in scripts.   

`git config --global user.name "{github username}"` configer in the --global the username.  
`git config --global user.email "{github emailadress}"` configer in the --global the email.  
`git config --global --list` show --global.  


adding `/` in front, it send you through the repo from the beginning `/img/donna.jpg`
not addind `/` lets you stay where you are `img/donna.jpg`
adding `../` let you take a step back : `../../img/donna.jpg`



ctr c - stop code from running.  

### Setting up the macbook

Install VS Code on App Store 

Install homebrew on https://brew.sh/#install in the terminal

Install python
$`brew install python`

Install pip
`sudo easy_install pip`

When matching Github to terminal, create a personal access token on https://github.com/settings/tokens
With clone, you fill in username and this token in stead of password.


