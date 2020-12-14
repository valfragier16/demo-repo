# Git Demo 
Demo to allow students to get familiar with git commands.


The slides are located at:
https://docs.google.com/presentation/d/1naeKnJGKVR22UrcNk3jpslysDaSZanp9HinpzaxFkZY/edit?usp=sharing

## Steps
<hr/>

### Step 1
Fork the repository at

https://github.com/`your_username`/git-demo-repo

*** if working with a team add collaborators via Repository Settings -> Manage Access -> Invite Collaborators. Once they have accepted the invitiation they can edit and commit changes to your repo.

<img src="https://i.stack.imgur.com/QRVQI.gif" alt="Add Collaborators GIF">
<hr/>

### Step 2
Navagate to whatever directory you plan on using for your root development directory.  If you're using a separate directory for microlabs go there.  Essentially, just go to where you would normally want to keep all of your work.  From there, clone your fork.

```
git clone https://github.com/valfragier16/git-demo-repo.git
```

You should now have `git-demo-repo` in your directory.
<hr/>

### Step 3
Create a new branch in that project and check that out. 
Run the following command:

```
git checkout -b <Your Branch Name>
```
The comments in the terminal should inform you that the branch has been switched to your branch
<hr/>

### Step 4
Since the class is working on this repository run a `git pull`to ensure you have the most updated code changes.

```
git pull origin main
```

### Step 5
Edit the `sharingCircle.txt.`file by adding something you learned or proud of in relation to the program, followed by your name at the end. Follow the syntax of what is already in the file.
<hr/>

### Step 6
Check the status.  Notice that the `sharingCircle.txt` file has been modified.
Make sure you save your changes, and commit it with the message "<Your Name> edited the File".
Run the following:

Stage your changes
```
git add .
```

Commit your changes with a message
```
git commit -m "<Your Name> edited the File"
```

Push your code to your remote branch in Github
```
git push
```
<hr/>

### Step 7
Now go to your github repository for this project , or follow the link that is presented in the comments of your terminal after the git push command. 
<hr/>

### Step 8
Create a pull request to merge your code changes into main branch.
<br>
<img src="https://soshace.com/wp-content/uploads/2020/01/create-pull-request.gif" alt="Create Pull Request GIF">

<br>
Successful merge into main would look something like this:

<img src="https://alexwlchan.net/images/2019/github_actions_merge.png" alt="Successful GitHub Merge">
<hr/>

### Step 9
Once your branch has been merged into main, view the branches and see the code changes.
<br>
<img src="https://github.blog/wp-content/uploads/2018/05/40565028-01ec5f98-6039-11e8-8bbf-8d1e2fe144d8.gif?fit=854%2C480" alt="Review code changes/branches">

<hr/>

### Step 10
If you run into issues checkout <a href="https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/resolving-a-merge-conflict-using-the-command-line">Resolving Merge Conflicts</a>

