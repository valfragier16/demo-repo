# git-demo-repo
Demo to allow students to get familiar with git commands.

# Git Microlab
The point of this microlab is to get you familiarized with the Git tools.

The slides are located at:
https://docs.google.com/presentation/d/1naeKnJGKVR22UrcNk3jpslysDaSZanp9HinpzaxFkZY/edit?usp=sharing

## Steps
<hr/>

### Step 1
Fork the repository at

https://github.com/Zipcoder/ZCW-Microlabs-Git
<hr/>

### Step 2
Navagate to whatever directory you plan on using for your root development directory.  If you're using a separate directory for microlabs go there.  Essentially, just go to where you would normally want to keep all of your work.  From there, clone your fork.  You should now have `ZCW-Microlabs-Git` in your directory.
<hr/>

### Step 3
Create a new branch called `dev` in that project and check that out.
<hr/>

### Step 4
Create a new file called `newFile.txt`.
<hr/>

### Step 5
Check the status.  Notice that there's a new file.
Add the text "NEW FILE" to the file, save it, and commit it with the message "Added a new file".
<hr/>

### Step 6
Commit your new branch and changes, and merge into master.
<hr/>

### Step 7
From master, list all of the possible branches.  Notice you have HEAD(the pointer to the top of master), remote master, remote dev, local master, and local dev.  Now append "On master" to newFile.txt.  Commit it with the message "Wrote to newFile from master" and push it.
<hr/>

### Step 8
Checkout dev, and append "On dev" to the file.  Commit with the message "Wrote to newFile from dev" and push it.
<hr/>

### Step 9
Checkout master again and merge dev in.

If you did everything right, you should have a merge conflict.  Look at newFile and see what git does with the changes.
<hr/>

### Step 10
Fix the file so it reads:

```
NEW FILE
On dev
On master
```
<hr/>

### Step 11
Commit and push the change with the message of "Fixed the conflict".
<hr/>

### Step 12
Checkout dev and merge master into it.  Notice that everything's cool?  That's because the "On dev" message was where it should be for that branch, so git just added the "On master" to the end.
<hr/>

### Step 13
Finally, submit a pull requst from your master in to Zipcode's master!
