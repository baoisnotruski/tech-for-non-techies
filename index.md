Poison menu:

[Why I use Github](#I-don't-code-but-I-use-Github.)
[Ubuntu commands I use](#Ubuntu-terminal-commands-for-writers)

## I don't code but I use Github. 

### Wait, but why?

- Back in college, I used to save my file as `second semester term paper final revised(4).docx`. I'm still traumatized.

- I use the `nano` command when I need to write/edit something quick. I prefer low-memory program because I use an Acer travelmate. 

- Branches are easier to manage than layers upon laters of nested folders that eventually resemble a matrjoschka doll with Richard Nixon's face.

- I love Markdown-- the lean, athletic, albeit less capable brother of HTML.

- `git log` helps me get right back where I left off.

### Some words of warning

- There is a learning curve.

- I still don't know when a task is big enough to warrant its own branch.

- When do I pull? Which branch do I have to be when I do `git pull origin [branch name]`?

- Sometimes when I switch branches, the files carry over. I have no idea what I'm doing with my life.

- `git log` is not a magic potion. You need to learn how to write a meaningful commit message.

XOFF ignored, mumble mumble. Don't use `ctrl + S`, use `ctrl + O` instead or you're dead. I'm done writing.


## There is a place in the universe for non-technical people who use the terminal for whatever reason they please.

### Wait, but why?

- There is a special kind of flow that you achieve when your fingers don't leave the keyboard.

- When are already familiar with the commands that are relevant to you, it's just faster.

### Ubuntu terminal commands for writers

- `cd`: change directory. Type `cd /Desktop` to go to the `Desktop` folder. You can also just hit the tab key instead of typing `Desktop` in full.

- `pwd`: present working directory. If you have no idea which folder the terminal is working on. It is also useful in case you need to get the full directory you are in, whatever reason you might have. 

- `mv` is useful for moving files. Type `mv filename.md /home/user/directory/subdirectory/` to move a file to a folder. Type `mv oldfilename.md newfilename.md` to rename a file.

- `l` lists all the files and directors within a folder.

- `ll` if you want people who see your screen to think that you're doing something important.

- `rm` to remove a  file. The terminal won't ask you if you are sure. If you went through the trouble of deleting a file this way, you should have been sure in the first place.

- `rm -r` comes with an `-r` flag to mean `recursive`. It tells your computer to go inside a folder, delete all the files there, get out of the folder, and remove the folder itself.  

- `vlc` + `filename` if you are use that VLC is the best app to open the file you want to open.

- `xdg-open` + `filename` if you have no idea which app to use or what the app command is.

- `sudo service network-manager restart` if you want to restart your network driver for whatever reason. I tend to do this when the connection is spotty, although I'm not really sure how much it does.

- `shutdown -h now` if you want to turn off your computer right away so you can go to lunch right away.

- `ctrl` + `z` if you have no idea what your terminal is doing and you just want to wake up from that terrible dream. 

- `nano` + `filename.md` creates a markdown file that you can edit in the terminal. `ctrl` + `o` then `Enter` to save. Add `ctrl` + `x` to get out of the markdown file. 

- `shutdown -h +44` in case you want to give your compouter 44 more minutes to download a movie before it shuts down.

- `git diff` if you want to see the changes you made to a file. The previous version will be in red, the modification will be in green. 

- `git add .` to prep all the files you modified for commit. `git add filename` if you only want to choose a specific file.

- `git commit -m (write your message inside parentheses)`. The `-m` flag lets you type a commit message without having to switch terminal interface. 

### A word of hope

This post will be updated continuously.
