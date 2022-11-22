---
date: 2022-09-01 4:00:00
title: Notes
published: True
tags:
  - neovimconf

---
# Outline

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

