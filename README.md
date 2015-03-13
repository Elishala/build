-open terminal

-enter 'ls' for a list of your directory

-change directory into the folder you want to create an app into, like this, 'cd src'

-make directory, then the name of the folder to create, 'mkdir build'

-'cd' into that new folder name, like so, 'cd build'

-then open atom, 'build atom' (or open whatever text editor you're using)

-next create a 'README.md', put your notes for others to read in here

-then make an html file, a css file, & a js file

-once in the html file, type HTML5, then hit tab, for auto tags (if you have these packages set up.)

-go to GitHub.com, open your profile page, go to the upper right hand corner, next to your GitHub name & pic, you'll find a '+' followed by a downward arrow, for 'create new', click & choose 'new repository'

-in the input field, under the words 'repository name', put the name you just named your new folder in atom

-(i saw the option to add a .gitignore, but still wasn't sure when or why to use it)

-then click the green button @ the bottom of the page 'create repository'

----------------note this next step gave me a bash:no such file-----------------------------

-GitHub takes you to another window, make sure the SSH button is chosen. from there copy paste what's in the input area into your terminal.

-----------------so i tried this with success------------------------------------------------

-since that didn't work, go back to terminal & type 'git init' which initializes an empty git repo

-then type 'git add -A'

-next type 'git commit -m "first commit(or whatever you want in quotes)"'

-type git 'remote add origin (& whatever was in that last input field)'

-then type 'git push -u origin master'

---------------------------------------------------------------------------------------------
-files we need next: .gitignore, gulp, package.json, node ... i think. and are there others?

-eventually you might want a css folder, where all of your css/scss files belong. you could have a file for colors & fonts, those can go in the css file too. you might also want a folder for all js files.

-what am i forgetting? and what order do the above items go in?
