# The Story

This is *The Story*, written by the Middleton High School Computer Science Club.

### Start
If you want to contribute to *The Story*, you need to get the files in this repository onto your computer.

 To do so,
 * **click the green button above** that says "Clone or download" and copy the link in the input box.
 * Paste the following command into your terminal: `git clone "https://github.com/MHS-CS-Club/The-Story.git"`. This will create a new folder called `The-Story` in your current directory. Reminder: to see which directory you are in, use the `pwd` command to print your working directory, or look at the path in your terminal prompt.
 * Change directories into The Story with `cd The-Story`. If you look at the files in this folder with `ls` or `dir`, you will see all of the files in this repository. Pretty cool!

### Work
Now that you have this repository on your computer, you can make changes to the files and whatever you want to *The Story*. By the way: the file for The Story is `the_story.txt`.
The Story is structured with an introduction, three paragraphs, and a conclusion. Your team will only add stuff to one section.

### Share
You've added some creative plot points to The Story, now it's time to share your writing with everyone else! To do this, go back to your terminal.
Once you're there, **make sure the directory you are in *is* this repo**.
### Git 
The first thing you need to do is tell Git that you have made changes to some files in your copy of the repo, and that you would like to add them to a staging area to be ready for the next step.
To do this, paste the following command in your terminal: `git add .`. This is telling "*git*" to "*add*" ".". The "." here means "everything in this folder", and is the easiest way to quickly add everything.

Next, we need to take the changes we have staged in Git and *commit* them to... somewhere (more on that soon).
Paste `git commit -m "add some message here"` into your terminal. Once again, this is telling *git* to *commit* the changes we have added before. The  "-m 'add some message here'" is an **argument** that is being passed to `git commit`. The "m" specifies that the following argument is a "message", and is equal to "'add some message here'". Of course, you can change the stuff inside of the double quotes to whatever you want to say. This message is useful, so it is never a bad idea to say a little something descriptive about what you are commiting. Don't make it too long however, that's just too many words :blush:.

Unlike `git add .`, commiting will display some output in your terminal, but don't freak out! Unless something is horribly wrong, this is OK.

The next step after *commiting* changes to **Git** is *pushing* them to **Github**.
Still in our terminal, paste the following command: `git push origin master`. Similar to the conventions of the previous commands, this command is telling *git* to *push* the changes we have committed to the remote called *origin* --but more specifically-- the branch named *master*. When you `git clone` a repository from Github, Git automatically creates a *remote* called "origin", which tells Git where you are going to push your code to.
`git push` will give you a whole bunch of output again, which is pretty interesting to read. If all goes well, the changes you've committed will be updated on the repository you cloned the link from! Go and check it out!
