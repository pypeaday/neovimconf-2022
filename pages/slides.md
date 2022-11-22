---
date: 2022-09-01 2:00:00
title: Slides
published: True
tags:
  - neovimconf

---

# Vim Conf 2022 Pypeaday

## Description

Switching to Vim opened a whole new world to me for interacting with a computer
and for getting things done. Before I adopted Vim I used GUIs for everything
because I thought that's how it had to be done... Notes in OneNote, code using
a GUI editor, different notes in TiddlyWiki, slides for work in PowerPoint,
slides for church using Logos, etc... Adopting Vim allowed me to disconnect a
specific tool from the problem that tool is solving - because usually I just
need to write text (notes, code, slides, etc.). Now, very nearly everything I
do is from a text-based and git-based workflow... I put all my notes on
basically anything just in my blog, which is all markdown and deployed to GH
with Markata on every push (living dangerously pushing to main) - and that's
all done easily from Vim with nice syntax highlighting, fast response,
integrated git-plugins, etc.. I keep project-specific task lists just in
markdown files and I have Vim/tmux shortcuts to quickly add todos for any
project (todo list is done with markata todoui) and I can get there fast
because my Vim workflow dovetails with Tmux nicely. Also I can pull that list
up right from the terminal, which I'm already in because Vim.... Vim also
pushed me into the cli more - because Vim is so easily extended with cli tools
and I'm already in the terminal... The builtin functionality also made things
make more sense - no more right-click, find "refactor all" or "rename symbol"
(for some stupid reason)... Vim find-replace is so intuitive and if I need it
extended then I learned what sed was because of Vim. Moving quickly in Vim also
enables me to do my job incredibly fast because I hop into several projects a
day in a coaching role - if I was bound by GUIs I'd be waiting forever for
startup, would lose which GUI instance was which project, etc... Being in the
terminal also made Tmux a trivial choice - now I have 90 tmux sessions, all
named appropriately, ready for me to jump back to and all while keeping the
majority of RAM still free for Chrome. Vim as my IDE also forced me to learn
way more about Python (I'm a python developer primarily), how LSP works, how to
configure a development environment, etc... things I took for granted in my GUI
workflows, or never knew, or worse - thought I knew but deeply misunderstood.
Now that I understand them better, I can coach my peers more effectively even
if they are still in a GUI-based ecosystem.

Basically, (Neo)Vim actually did change my life and I'm really thankful for it
(maybe that should be the title?)

## Personal Blurb

I am primarily an amateur Python developer using Neovim and Google to solve
problems in Data Engineering and DevSecOps. When my wife and daughters are
asleep I get to homelab and build computers as a hobby to learn new things and
bring some hardware experience to the analytics space.


## Outline

1. Intro
    * Started as a DS but every team needed a DE
    * I was forced into a DevOps role and I liked it
    * Got started homelabbing a couple years ago
    * I coach and present at work on Python stuff regularly
    * I have taught classes through church
    * Taking theology courses
2. Things I do
    * Church
    * Learning
    * Code
    * Blog/TIL
    * Coach
    * Present
3. How I used to to each of the things
    * For church
        * OneNote for notes (thought Microsoft was the only way)
        * Logos for teaching notes (I liked the integration with my resourced)
        * PPT for presentation material (again thought Microsoft was the only way)
        * Then moved to Logos' native tools (and again Logos had tools like were integrated and similar)
        * Logos tools let me have on GUI for church-stuff that also kept stuff in AWS so I could share links to presentations and things
        * Moved to TiddlyWiki when I moved to Linux
            * Different syntax than Markdown
            * One big HTML file
            * Powerful but still clunky especially with my other needs
    * For learning
        * OneNote
        * Logos notes
            * But I'd never remember if I kept a certain note in Logos or OneNote
        * TiddlyWiki to drop Microsoft
            * Same issue.... now where did I keep _that_ note
    * Code
        * MATLAB origins
            * As someone who knew nothing about code I took away from grad school that each language had its own GUI... There was no separation between the IDE and the language
        * R and Rstudio
            * Reinforced that GUIs and languages were married
        * Python & Anaconda
            * Thought once again that Spyder _was the Python IDE_
            * Anaconda and "distributions of Python" also confused me
        * PyCharm
            * Sold on flashy tools like a nice debugger
            * I was learning git at the same time, and had to wade through questions about where to keep files, what is the scope of a git repo, and what tools do I use? I didn't understand that the same git was behind gitk, gitExtensions, and the git integration in PyCharm
            * LSP? never heard of it but thanks for the code completion JetBrains
        * VS Code
            * Moved groups at work - lost my PyCharm pro so switched to VS Code
            * Why was there a Python extension and Pylance? I still didn't get _anything_ about LSP and I knew very little about how Python actually worked (virtual environment management)
            * Saw Waylon move way faster in Vim...
        * Swithed to VIM summer 2021 for code
            * Once I swithced to Linux as well I started using Tmux and other builtins and this is where things started changing
    * Blogging
        * I didn't start blogging until after the Vim switch
        * I learned a lot about git before blogging - so I started off in a text file and git-based workflow rather than on a blogging platform
    * Coaching/Presenting
        * PPT is the corporate America way
        * Found it was easier to write Markdown and play with lookatme or Markata to give terminal based presentations since I'm already in Vim
4. How I do the things now
    * recap
        * several tools for several problems over the years
        * resulted in scattered materials and a lack of fluency in any tool
    * present
        * Vim and tmux give me encapsulated terminal sessions for any given thing 
        * Everything is in a git repo, with text files, and lightweight orchestration tools on top like Markata + plugins
            * Python project 
            * My blog
            * Notes for an online class
            * Presentation material for church or something at work
5. Results
    * I am way faster at any one of these tasks because I don't spend any time thinking about how I wil track progress or material, where I will store it, or how I will distribute it - a common workflow driven by git frees my mind to only focus on the task
    * My material is safer - it's all backed up in git (or is getting there) either on GitHub or in my homelab
    * Distribution, if requried - say for sharing small group notes, is automatic with GH pages now
##

...
