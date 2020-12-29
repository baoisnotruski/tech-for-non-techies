# Jump to a post:

[What is a web browser?](#what-is-a-browser)

[I won't use an RFID to spy on you](#rfid-is-bad-design)

[Experience the world as a UX designer](#experience-the-world-as-a-ux-designer)

[Spreadsheet as Point of Sales](#how-to-use-a-spreadsheet-as-a-pos)

[Why I use Github](#i-dont-code-in-my-job-but-i-use-github)

[Ubuntu commands I use](#ubuntu-terminal-commands-for-writers)


# What is a browser? 

I used to think I know what a browser was. Until I started running Selenium in a headless state.

![web_diagram_naive](https://user-images.githubusercontent.com/63767647/103252119-5989a300-49b6-11eb-911d-50052725c33a.jpeg)

## Headless state = When your browser does things but you don't see it

Headless state is when a browser accesses a page, comments on posts, and do everything that you could do on Google Chrome (or Safari, or Firefox) without the browser appearing on your screen.

## So TIL:

A browser is not just the thing that you see on your screen: it's the physical manifestation of it.

A browser is the thing that brings stuff to your computer and turns it into something that you can see or hear or both.

Hint: Initiate existential crisis.

There's more to life than meets the eye? No one told me. I have to remodel my world:



This is a simplified diagram. If I were to write everything, it will have to include the network, Javascript interpreter, UI backend, optic receptors, neural transmitters, and, um.. brain? 


Thanks for reading. 


# RFID is bad design

Some people might tell you not to get vaccinated because the government will use that as an opportunity to plant microchips under your skin.

These microchips will be used to track whatever you do. 

I will not debunk or prove this argument. But if I were the government, I here's why I would not do that.

1. **RFID microchips can handle limited input.** 
 
If I want to spy on you, I want you to use a device that will tell me:

- What you look like
- Who your friends are
- Which restaurant you just checked in
- What voice note you just sent to your mom

2. **RFID is intrusive.** 

You are already repulsed by the thought of wearing it; even more so, getting it planted under your skin.
 
I will design a product that you want to hold and put your face in front of. It will be the very last thing you will see before going to sleep and the first thing you will look for when you wake up.

3. **Of course, I'm going to want your express consent.** 
 
When you use my product, I want you to agree to my terms. Otherwise, I won't let you use it. You can't say no. Because you want it. 

Caution: Side effects of the vaccine include you turning into a crocodile.

[Back to index](#jump-to-a-post)

# Experience the world as a UX designer

`Życie jest bez sensu i wszyscy zginiemy` is my favorite Polish sentence.

It's easy to choose because I know only enough to have a good day:

`Cześć. Jak się masz?`

`Piękna pogoda.`

`Jesteś piękną kobietą.`

`Mow wolniej słabo mowie populsko.` (This, I'm not sure how to write.)

`Do widzenia.`

But what's so good about "Life is meaningless and we are all going to die"?

It's an invitation to see that life is a platform. Whatever meaning, intent, or direction you put in it is completely up to you.

[Back to index](#jump-to-a-post)


# How to use a spreadsheet as a POS

**Don't.** 

A spreadsheet should not be used as a POS. 

But no one can stop you if you do. Just anticipate that users will mess it up.

My favorite Reddit quote:

*Anything can be anything of you try hard enough.*

## If you can't help it, there are some duct tape solutions:

#### Use dropdowns
Instead of allowing your sales person to enter a generic `beer`, force them to select `Heineken`, `Carlsberg`, `San Miguel`. 

In Google Sheets:
`Data` --> `Data Validation` --> `Criteria` --> `List of items`

#### Annoy users with conditional formatting
This is not the same cell that you learned in biology class. 

If leaving a cell blank would lead to lost sales, then this cell has to be absolutely filled. 

Try conditional formatting:

First, highlight all the applicable rows and columns. 

`Format` --> `Conditional formatting` --> `Format rules` --> `Format cells if...` --> `Is empty` --> Please choose a pastel color that won't turn me blind --> `Done`

You can also flip this: only fill cells with colors if data is entered. 

#### =NOW()

You can use the `=NOW()` function to automatically enter time and date. Use only if timestamp is relevant to your operations.

While you're at it, dig into functions and scripts.

Word of caution: scripts are your weird neighbor. Things that seem obvious carry lots of unknown unknowns.

#### Learn how to neatly organize data into a table.

I wrote [this PostgreSQL course](https://codestop.io/course/view/postgresql-introduction) a couple of years back. I won't make money from you if you take this course but you will do humanity a service if you learn some form of logic. 

Please note that it's read as `postgres kyu el` because it stands for `Post Ingres Query Language`.  

[Back to index](#jump-to-a-post)

# I don't code [in my job] but I use Github. 

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

[Back to index](#jump-to-a-post)

# Ubuntu terminal commands for writers

There is a place in the universe for non-technical people who use the terminal for whatever reason they please.

### Wait, but why?

- Your thoughts can flow like a river into the computer when your fingers don't leave the keyboard.

- When are already familiar with the commands that are relevant to you, it's just faster.



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

[Back to index](#jump-to-a-post)