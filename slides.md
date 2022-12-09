---
article_html: "<h2 id=\"_1\"></h2>\n<div class=\"admonition vim-credit\">\n<p class=\"admonition-title\">Philosophy
  of Vim</p>\n<p>A: Nicholas Payne</p>\n<p>d: December 2022</p>\n<p>C: Neovimconf
  2022</p>\n</div>\n<h2 id=\"intro-0-personal\">Intro 0 - Personal</h2>\n<div class=\"admonition
  note\">\n<p class=\"admonition-title\">Personal</p>\n<ul>\n<li>Husband and father</li>\n<li>Hobbies/Life/Interests<ul>\n<li>Biblical
  theology</li>\n<li>Privacy-advocate conspiracy-theorist</li>\n<li>Homelabbing</li>\n</ul>\n</li>\n<li>Learning/Education<ul>\n<li>FEM
  courses</li>\n<li>BibleProject and other theology outlets</li>\n<li>Blogging/TILs</li>\n</ul>\n</li>\n</ul>\n</div>\n<h2
  id=\"intro-1-professional\">Intro 1 - Professional</h2>\n<div class=\"admonition
  note\">\n<p class=\"admonition-title\">Professional</p>\n<ul>\n<li>Hired as a Data
  Scientist (2017)</li>\n<li>Data Engineering or DevOps was always lacking (2017-2020)</li>\n<li>Homelabbing
  (2019)</li>\n<li>Amateur Python dev (~5 years)</li>\n<li><em>Coach</em> team members
  on basic-intermediate Python coding</li>\n<li>Teach outside work through church
  and small groups</li>\n</ul>\n</div>\n<h2 id=\"_2\"></h2>\n<div class=\"admonition
  vim-credit\">\n<p class=\"admonition-title\">Agenda</p>\n<div class=\"admonition
  centered-list\">\n<ul>\n<li>My set of \"problems\"</li>\n<li>Philosophy behind those
  problems</li>\n<li>Vim to the rescue</li>\n<li>Credits</li>\n</ul>\n</div>\n</div>\n<h2
  id=\"problem-0-notes\">Problem 0 - Notes</h2>\n<!-- * Notes (church, courses, teaching,
  etc.) -->\n<div class=\"admonition note\">\n<p class=\"admonition-title\">Notes
  (church, courses, teaching, etc.)</p>\n<ul>\n<li>OneNote</li>\n<li>Logos Notes</li>\n<li>Logos
  Sermon Editor</li>\n<li>Notepad</li>\n<li>Evernote</li>\n<li>TiddlyWiki</li>\n<li>LaTex</li>\n</ul>\n</div>\n<h2
  id=\"problem-1-distribution\">Problem 1 - Distribution</h2>\n<!-- * Distribution
  -->\n<div class=\"admonition warning\">\n<p class=\"admonition-title\">Distribution</p>\n<ul>\n<li>Never
  understood how to share via Microsoft tooling</li>\n<li>Logos Sermon Editor publishes
  to a URL, but the notes don't</li>\n<li>Notepad?</li>\n<li>TiddlyWiki kind of works
  in a git repo... kind of...</li>\n<li>Manually making PPTs when necessary - c-c
  c-v from whichever source</li>\n</ul>\n</div>\n<h2 id=\"problem-2-coding\">Problem
  2 - Coding</h2>\n<!-- * Code -->\n<div class=\"admonition danger\">\n<p class=\"admonition-title\">Code</p>\n<ul>\n<li>MATLAB
  GUI</li>\n<li>R + RStudio</li>\n<li>Anaconda + Spyder</li>\n<li>PyCharm (CE and
  Professional)</li>\n<li>VS C***</li>\n</ul>\n</div>\n<div class=\"admonition danger\">\n<p
  class=\"admonition-title\">LaTex</p>\n<ul>\n<li>TexWorks</li>\n</ul>\n</div>\n<h2
  id=\"problem-5-todos\">Problem 5 - Todos</h2>\n<!-- * Code -->\n<div class=\"admonition
  danger\">\n<p class=\"admonition-title\">TODOs</p>\n<ul>\n<li>Notebooks</li>\n<li>AZDO
  boards</li>\n<li>No, that other notebook</li>\n<li>Texts to myself </li>\n<li>Found
  the right notebook...</li>\n</ul>\n</div>\n<h2 id=\"problems-summary\">Problems
  - Summary</h2>\n<div class=\"admonition note\">\n<p class=\"admonition-title\">My
  Woes</p>\n<ul>\n<li>Same computer (or software required on any machine)</li>\n<li>Different
  backup strategies/mechanisms</li>\n<li>Vendor lock-in from several angles</li>\n<li>Disorganization</li>\n<li>Windows
  \U0001F922</li>\n</ul>\n</div>\n<h2 id=\"philosophy\">Philosophy</h2>\n<blockquote>\n<p>Problems
  are solved by tools</p>\n<p>Tools are GUIs</p>\n<p>Problems are solved with GUIs</p>\n<p>Click
  button = run code</p>\n</blockquote>\n<h2 id=\"_3\"></h2>\n<div class=\"admonition
  success\">\n<p class=\"admonition-title\">Enter Neovim</p>\n<ul>\n<li>Human-computer
  interaction</li>\n<li>Extremely fast</li>\n<li>Opens doors for CLI tools</li>\n<li>Forced
  education<ul>\n<li>python setup</li>\n<li>tex setup</li>\n</ul>\n</li>\n</ul>\n</div>\n<!--
  Notes: -->\n<!-- 0. A computer no longer was just Windows or Mac... I moved into
  Linux around -->\n<!--    the same time and began to conceptually understand what
  Windows offered, and -->\n<!--    how I could get a more tailored experience of
  the only things I actually -->\n<!--    want, out of a Linux environment -->\n<!--
  1. Moving around in Vim is incredibly fast - using the mouse hurts my shoulder now
  -->\n<!-- 2. Being in the terminal makes CLI tools natural (Waylon's talk) -->\n<!--
  3. NOT using canned solutions, like VS C***, forced me to learn more about my -->\n<!--
  \   development workflow, understand the tools I use, configure them how I want,
  -->\n<!--    and because I've done that I can now better coach others around me
  whether -->\n<!--    they use vim or not -->\n\n<h2 id=\"breakdown\">Breakdown</h2>\n<div
  class=\"admonition vim-credit\">\n<p><center></p>\n<table>\n<thead>\n<tr>\n<th>Problem</th>\n<th>Solution</th>\n</tr>\n</thead>\n<tbody>\n<tr>\n<td>Notes</td>\n<td>Everything
  is git + Markdown</td>\n</tr>\n<tr>\n<td>Distribution</td>\n<td>Markata sites/slides
  <br/> (GH/Cloudflare or Self-host)</td>\n</tr>\n<tr>\n<td>Code</td>\n<td>Vim customization
  <br /> Tmux usage <br /> CLI tools <em>right flipping there</em></td>\n</tr>\n<tr>\n<td>Todos</td>\n<td>Markata-todoui
  <br /> Kanboard (collaboration)</td>\n</tr>\n</tbody>\n</table>\n<p></center></p>\n</div>\n<h2
  id=\"tldr\">TL;DR</h2>\n<blockquote>\n<p>I'm on a journey to get faster, be more
  competent, and to say better organized</p>\n<p><em>&amp;</em></p>\n<p><strong>(Neo)vim
  actually changed my life - Thanks</strong></p>\n</blockquote>\n<h2 id=\"credit\">Credit</h2>\n<!--
  !!! note \"Game Recognize Game\" -->\n<div class=\"admonition vim-credit\">\n<p
  class=\"admonition-title\">Game Recognize Game</p>\n<div class=\"admonition centered-list\">\n<ul>\n<li><a
  href=\"https://twitter.com/ThePrimeagen\">ThePrimeagean</a>  (Excitement)</li>\n<li><a
  href=\"https://twitter.com/teej_dv/\">Teej</a>  (Provision)</li>\n<li><a href=\"https://twitter.com/jessarchercodes\">Jess
  Archer</a>  (Organization)</li>\n<li><a href=\"https://twitter.com/_waylonwalker\">Waylon
  Walker</a>  (Comrade)</li>\n</ul>\n</div>\n</div>\n<h2 id=\"_4\"></h2>\n<blockquote>\n<p>END</p>\n</blockquote>\n<h2
  id=\"dummy-end\">Dummy end</h2>\n<p>...</p>\n<div class='prevnext'>\n\n    <style
  type='text/css'>\n\n    :root {\n      --prevnext-color-text: #d8ebe6;\n      --prevnext-color-angle:
  #83dcc8cc;\n      --prevnext-subtitle-brightness: 3;\n    }\n    [data-theme=\"light\"]
  {\n      --prevnext-color-text: #1f2022;\n      --prevnext-color-angle: #ffeb00;\n
  \     --prevnext-subtitle-brightness: 3;\n    }\n    [data-theme=\"dark\"] {\n      --prevnext-color-text:
  #d8ebe6;\n      --prevnext-color-angle: #83dcc8cc;\n      --prevnext-subtitle-brightness:
  3;\n    }\n    .prevnext {\n      display: flex;\n      flex-direction: row;\n      justify-content:
  space-around;\n      align-items: flex-start;\n    }\n    .prevnext a {\n      display:
  flex;\n      align-items: center;\n      width: 100%;\n      text-decoration: none;\n
  \   }\n    a.next {\n      justify-content: flex-end;\n    }\n    .prevnext a:hover
  {\n      background: #00000006;\n    }\n    .prevnext-subtitle {\n      color: var(--prevnext-color-text);\n
  \     filter: brightness(var(--prevnext-subtitle-brightness));\n      font-size:
  .8rem;\n    }\n    .prevnext-title {\n      color: var(--prevnext-color-text);\n
  \     font-size: 1rem;\n    }\n    .prevnext-text {\n      max-width: 30vw;\n    }\n
  \   </style>\n\n    <a class='prev' href='/neovimconf-2022/slides/slide-0'>\n\n\n
  \       <svg width=\"50px\" height=\"50px\" viewbox=\"0 0 24 24\" fill=\"none\"
  xmlns=\"http://www.w3.org/2000/svg\">\n            <path d=\"M13.5 8.25L9.75 12L13.5
  15.75\" stroke=\"var(--prevnext-color-angle)\" stroke-width=\"1.5\" stroke-linecap=\"round\"
  stroke-linejoin=\"round\"> </path>\n        </svg>\n        <div class='prevnext-text'>\n
  \           <p class='prevnext-subtitle'>prev</p>\n            <p class='prevnext-title'>Slides
  | 0</p>\n        </div>\n    </a>\n\n    <a class='next' href='/neovimconf-2022/03-talk-notes'>\n\n
  \       <div class='prevnext-text'>\n            <p class='prevnext-subtitle'>next</p>\n
  \           <p class='prevnext-title'>Notes</p>\n        </div>\n        <svg width=\"50px\"
  height=\"50px\" viewbox=\"0 0 24 24\" fill=\"none\" xmlns=\"http://www.w3.org/2000/svg\">\n
  \           <path d=\"M10.5 15.75L14.25 12L10.5 8.25\" stroke=\"var(--prevnext-color-angle)\"
  stroke-width=\"1.5\" stroke-linecap=\"round\" stroke-linejoin=\"round\"></path>\n
  \       </svg>\n    </a>\n  </div>"
cover: ''
date: 2022-09-01
datetime: 2022-09-01 00:00:00+00:00
description: '! ! ! ! ! ! ! ! ! ! Problems are solved by tools Tools are GUIs Problems
  are solved with GUIs Click button = run code ! ! I ! END ...'
edit_link: https://github.com/edit/main/pages/slides.md
html: "<h2 id=\"_1\"></h2>\n<div class=\"admonition vim-credit\">\n<p class=\"admonition-title\">Philosophy
  of Vim</p>\n<p>A: Nicholas Payne</p>\n<p>d: December 2022</p>\n<p>C: Neovimconf
  2022</p>\n</div>\n<h2 id=\"intro-0-personal\">Intro 0 - Personal</h2>\n<div class=\"admonition
  note\">\n<p class=\"admonition-title\">Personal</p>\n<ul>\n<li>Husband and father</li>\n<li>Hobbies/Life/Interests<ul>\n<li>Biblical
  theology</li>\n<li>Privacy-advocate conspiracy-theorist</li>\n<li>Homelabbing</li>\n</ul>\n</li>\n<li>Learning/Education<ul>\n<li>FEM
  courses</li>\n<li>BibleProject and other theology outlets</li>\n<li>Blogging/TILs</li>\n</ul>\n</li>\n</ul>\n</div>\n<h2
  id=\"intro-1-professional\">Intro 1 - Professional</h2>\n<div class=\"admonition
  note\">\n<p class=\"admonition-title\">Professional</p>\n<ul>\n<li>Hired as a Data
  Scientist (2017)</li>\n<li>Data Engineering or DevOps was always lacking (2017-2020)</li>\n<li>Homelabbing
  (2019)</li>\n<li>Amateur Python dev (~5 years)</li>\n<li><em>Coach</em> team members
  on basic-intermediate Python coding</li>\n<li>Teach outside work through church
  and small groups</li>\n</ul>\n</div>\n<h2 id=\"_2\"></h2>\n<div class=\"admonition
  vim-credit\">\n<p class=\"admonition-title\">Agenda</p>\n<div class=\"admonition
  centered-list\">\n<ul>\n<li>My set of \"problems\"</li>\n<li>Philosophy behind those
  problems</li>\n<li>Vim to the rescue</li>\n<li>Credits</li>\n</ul>\n</div>\n</div>\n<h2
  id=\"problem-0-notes\">Problem 0 - Notes</h2>\n<!-- * Notes (church, courses, teaching,
  etc.) -->\n<div class=\"admonition note\">\n<p class=\"admonition-title\">Notes
  (church, courses, teaching, etc.)</p>\n<ul>\n<li>OneNote</li>\n<li>Logos Notes</li>\n<li>Logos
  Sermon Editor</li>\n<li>Notepad</li>\n<li>Evernote</li>\n<li>TiddlyWiki</li>\n<li>LaTex</li>\n</ul>\n</div>\n<h2
  id=\"problem-1-distribution\">Problem 1 - Distribution</h2>\n<!-- * Distribution
  -->\n<div class=\"admonition warning\">\n<p class=\"admonition-title\">Distribution</p>\n<ul>\n<li>Never
  understood how to share via Microsoft tooling</li>\n<li>Logos Sermon Editor publishes
  to a URL, but the notes don't</li>\n<li>Notepad?</li>\n<li>TiddlyWiki kind of works
  in a git repo... kind of...</li>\n<li>Manually making PPTs when necessary - c-c
  c-v from whichever source</li>\n</ul>\n</div>\n<h2 id=\"problem-2-coding\">Problem
  2 - Coding</h2>\n<!-- * Code -->\n<div class=\"admonition danger\">\n<p class=\"admonition-title\">Code</p>\n<ul>\n<li>MATLAB
  GUI</li>\n<li>R + RStudio</li>\n<li>Anaconda + Spyder</li>\n<li>PyCharm (CE and
  Professional)</li>\n<li>VS C***</li>\n</ul>\n</div>\n<div class=\"admonition danger\">\n<p
  class=\"admonition-title\">LaTex</p>\n<ul>\n<li>TexWorks</li>\n</ul>\n</div>\n<h2
  id=\"problem-5-todos\">Problem 5 - Todos</h2>\n<!-- * Code -->\n<div class=\"admonition
  danger\">\n<p class=\"admonition-title\">TODOs</p>\n<ul>\n<li>Notebooks</li>\n<li>AZDO
  boards</li>\n<li>No, that other notebook</li>\n<li>Texts to myself </li>\n<li>Found
  the right notebook...</li>\n</ul>\n</div>\n<h2 id=\"problems-summary\">Problems
  - Summary</h2>\n<div class=\"admonition note\">\n<p class=\"admonition-title\">My
  Woes</p>\n<ul>\n<li>Same computer (or software required on any machine)</li>\n<li>Different
  backup strategies/mechanisms</li>\n<li>Vendor lock-in from several angles</li>\n<li>Disorganization</li>\n<li>Windows
  \U0001F922</li>\n</ul>\n</div>\n<h2 id=\"philosophy\">Philosophy</h2>\n<blockquote>\n<p>Problems
  are solved by tools</p>\n<p>Tools are GUIs</p>\n<p>Problems are solved with GUIs</p>\n<p>Click
  button = run code</p>\n</blockquote>\n<h2 id=\"_3\"></h2>\n<div class=\"admonition
  success\">\n<p class=\"admonition-title\">Enter Neovim</p>\n<ul>\n<li>Human-computer
  interaction</li>\n<li>Extremely fast</li>\n<li>Opens doors for CLI tools</li>\n<li>Forced
  education<ul>\n<li>python setup</li>\n<li>tex setup</li>\n</ul>\n</li>\n</ul>\n</div>\n<!--
  Notes: -->\n<!-- 0. A computer no longer was just Windows or Mac... I moved into
  Linux around -->\n<!--    the same time and began to conceptually understand what
  Windows offered, and -->\n<!--    how I could get a more tailored experience of
  the only things I actually -->\n<!--    want, out of a Linux environment -->\n<!--
  1. Moving around in Vim is incredibly fast - using the mouse hurts my shoulder now
  -->\n<!-- 2. Being in the terminal makes CLI tools natural (Waylon's talk) -->\n<!--
  3. NOT using canned solutions, like VS C***, forced me to learn more about my -->\n<!--
  \   development workflow, understand the tools I use, configure them how I want,
  -->\n<!--    and because I've done that I can now better coach others around me
  whether -->\n<!--    they use vim or not -->\n\n<h2 id=\"breakdown\">Breakdown</h2>\n<div
  class=\"admonition vim-credit\">\n<p><center></p>\n<table>\n<thead>\n<tr>\n<th>Problem</th>\n<th>Solution</th>\n</tr>\n</thead>\n<tbody>\n<tr>\n<td>Notes</td>\n<td>Everything
  is git + Markdown</td>\n</tr>\n<tr>\n<td>Distribution</td>\n<td>Markata sites/slides
  <br/> (GH/Cloudflare or Self-host)</td>\n</tr>\n<tr>\n<td>Code</td>\n<td>Vim customization
  <br /> Tmux usage <br /> CLI tools <em>right flipping there</em></td>\n</tr>\n<tr>\n<td>Todos</td>\n<td>Markata-todoui
  <br /> Kanboard (collaboration)</td>\n</tr>\n</tbody>\n</table>\n<p></center></p>\n</div>\n<h2
  id=\"tldr\">TL;DR</h2>\n<blockquote>\n<p>I'm on a journey to get faster, be more
  competent, and to say better organized</p>\n<p><em>&amp;</em></p>\n<p><strong>(Neo)vim
  actually changed my life - Thanks</strong></p>\n</blockquote>\n<h2 id=\"credit\">Credit</h2>\n<!--
  !!! note \"Game Recognize Game\" -->\n<div class=\"admonition vim-credit\">\n<p
  class=\"admonition-title\">Game Recognize Game</p>\n<div class=\"admonition centered-list\">\n<ul>\n<li><a
  href=\"https://twitter.com/ThePrimeagen\">ThePrimeagean</a>  (Excitement)</li>\n<li><a
  href=\"https://twitter.com/teej_dv/\">Teej</a>  (Provision)</li>\n<li><a href=\"https://twitter.com/jessarchercodes\">Jess
  Archer</a>  (Organization)</li>\n<li><a href=\"https://twitter.com/_waylonwalker\">Waylon
  Walker</a>  (Comrade)</li>\n</ul>\n</div>\n</div>\n<h2 id=\"_4\"></h2>\n<blockquote>\n<p>END</p>\n</blockquote>\n<h2
  id=\"dummy-end\">Dummy end</h2>\n<p>...</p>\n<div class='prevnext'>\n\n    <style
  type='text/css'>\n\n    :root {\n      --prevnext-color-text: #d8ebe6;\n      --prevnext-color-angle:
  #83dcc8cc;\n      --prevnext-subtitle-brightness: 3;\n    }\n    [data-theme=\"light\"]
  {\n      --prevnext-color-text: #1f2022;\n      --prevnext-color-angle: #ffeb00;\n
  \     --prevnext-subtitle-brightness: 3;\n    }\n    [data-theme=\"dark\"] {\n      --prevnext-color-text:
  #d8ebe6;\n      --prevnext-color-angle: #83dcc8cc;\n      --prevnext-subtitle-brightness:
  3;\n    }\n    .prevnext {\n      display: flex;\n      flex-direction: row;\n      justify-content:
  space-around;\n      align-items: flex-start;\n    }\n    .prevnext a {\n      display:
  flex;\n      align-items: center;\n      width: 100%;\n      text-decoration: none;\n
  \   }\n    a.next {\n      justify-content: flex-end;\n    }\n    .prevnext a:hover
  {\n      background: #00000006;\n    }\n    .prevnext-subtitle {\n      color: var(--prevnext-color-text);\n
  \     filter: brightness(var(--prevnext-subtitle-brightness));\n      font-size:
  .8rem;\n    }\n    .prevnext-title {\n      color: var(--prevnext-color-text);\n
  \     font-size: 1rem;\n    }\n    .prevnext-text {\n      max-width: 30vw;\n    }\n
  \   </style>\n\n    <a class='prev' href='/neovimconf-2022/slides/slide-0'>\n\n\n
  \       <svg width=\"50px\" height=\"50px\" viewbox=\"0 0 24 24\" fill=\"none\"
  xmlns=\"http://www.w3.org/2000/svg\">\n            <path d=\"M13.5 8.25L9.75 12L13.5
  15.75\" stroke=\"var(--prevnext-color-angle)\" stroke-width=\"1.5\" stroke-linecap=\"round\"
  stroke-linejoin=\"round\"> </path>\n        </svg>\n        <div class='prevnext-text'>\n
  \           <p class='prevnext-subtitle'>prev</p>\n            <p class='prevnext-title'>Slides
  | 0</p>\n        </div>\n    </a>\n\n    <a class='next' href='/neovimconf-2022/03-talk-notes'>\n\n
  \       <div class='prevnext-text'>\n            <p class='prevnext-subtitle'>next</p>\n
  \           <p class='prevnext-title'>Notes</p>\n        </div>\n        <svg width=\"50px\"
  height=\"50px\" viewbox=\"0 0 24 24\" fill=\"none\" xmlns=\"http://www.w3.org/2000/svg\">\n
  \           <path d=\"M10.5 15.75L14.25 12L10.5 8.25\" stroke=\"var(--prevnext-color-angle)\"
  stroke-width=\"1.5\" stroke-linecap=\"round\" stroke-linejoin=\"round\"></path>\n
  \       </svg>\n    </a>\n  </div>"
jinja: false
long_description: '! ! ! ! ! ! ! ! ! ! Problems are solved by tools Tools are GUIs
  Problems are solved with GUIs Click button = run code ! ! I ! END ...'
now: 2022-12-09 22:22:58.450938
path: pages/slides.md
published: true
slug: slides
super_description: '! ! ! ! ! ! ! ! ! ! Problems are solved by tools Tools are GUIs
  Problems are solved with GUIs Click button = run code ! ! I ! END ...'
tags:
- neovimconf
templateKey: ''
title: Slides
today: 2022-12-09
---

## 

!!! vim-credit "Philosophy of Vim"

    A: Nicholas Payne

    d: December 2022

    C: Neovimconf 2022

## Intro 0 - Personal

!!! note "Personal"

    * Husband and father
    * Hobbies/Life/Interests
        * Biblical theology
        * Privacy-advocate conspiracy-theorist
        * Homelabbing
    * Learning/Education
        * FEM courses
        * BibleProject and other theology outlets
        * Blogging/TILs

## Intro 1 - Professional

!!! note "Professional"

    * Hired as a Data Scientist (2017)
    * Data Engineering or DevOps was always lacking (2017-2020)
    * Homelabbing (2019)
    * Amateur Python dev (~5 years)
    * _Coach_ team members on basic-intermediate Python coding
    * Teach outside work through church and small groups

## 

!!! vim-credit "Agenda"

    !!! centered-list ""

        * My set of "problems"
        * Philosophy behind those problems
        * Vim to the rescue
        * Credits

## Problem 0 - Notes

<!-- * Notes (church, courses, teaching, etc.) -->
!!! note "Notes (church, courses, teaching, etc.)"

    * OneNote
    * Logos Notes
    * Logos Sermon Editor
    * Notepad
    * Evernote
    * TiddlyWiki
    * LaTex

## Problem 1 - Distribution
<!-- * Distribution -->
!!! warning "Distribution"

    * Never understood how to share via Microsoft tooling
    * Logos Sermon Editor publishes to a URL, but the notes don't
    * Notepad?
    * TiddlyWiki kind of works in a git repo... kind of...
    * Manually making PPTs when necessary - c-c c-v from whichever source

## Problem 2 - Coding
<!-- * Code -->
!!! danger "Code"

    * MATLAB GUI
    * R + RStudio
    * Anaconda + Spyder
    * PyCharm (CE and Professional)
    * VS C*\*\*

!!! danger "LaTex"

    * TexWorks

## Problem 5 - Todos
<!-- * Code -->
!!! danger "TODOs"

    * Notebooks
    * AZDO boards
    * No, that other notebook
    * Texts to myself 
    * Found the right notebook...


## Problems - Summary

!!! note "My Woes"

    * Same computer (or software required on any machine)
    * Different backup strategies/mechanisms
    * Vendor lock-in from several angles
    * Disorganization
    * Windows 🤢

## Philosophy

> Problems are solved by tools

> Tools are GUIs

> Problems are solved with GUIs

> Click button = run code

## 

!!! success "Enter Neovim"

    * Human-computer interaction
    * Extremely fast
    * Opens doors for CLI tools
    * Forced education
        * python setup
        * tex setup


<!-- Notes: -->
<!-- 0. A computer no longer was just Windows or Mac... I moved into Linux around -->
<!--    the same time and began to conceptually understand what Windows offered, and -->
<!--    how I could get a more tailored experience of the only things I actually -->
<!--    want, out of a Linux environment -->
<!-- 1. Moving around in Vim is incredibly fast - using the mouse hurts my shoulder now -->
<!-- 2. Being in the terminal makes CLI tools natural (Waylon's talk) -->
<!-- 3. NOT using canned solutions, like VS C***, forced me to learn more about my -->
<!--    development workflow, understand the tools I use, configure them how I want, -->
<!--    and because I've done that I can now better coach others around me whether -->
<!--    they use vim or not -->



## Breakdown

!!! vim-credit ""

    <center>

    | Problem | Solution |
    | --- | --- |
    | Notes | Everything is git + Markdown | 
    | Distribution | Markata sites/slides <br/> (GH/Cloudflare or Self-host) |
    | Code | Vim customization <br /> Tmux usage <br /> CLI tools _right flipping there_ |
    | Todos | Markata-todoui <br /> Kanboard (collaboration) |

    </center>


## TL;DR

>I'm on a journey to get faster, be more competent, and to say better organized
>
>*&*
>
>__(Neo)vim actually changed my life - Thanks__


## Credit

<!-- !!! note "Game Recognize Game" -->
!!! vim-credit "Game Recognize Game"

    !!! centered-list ""

        * [ThePrimeagean](https://twitter.com/ThePrimeagen)  (Excitement)
        * [Teej](https://twitter.com/teej_dv/)  (Provision)
        * [Jess Archer](https://twitter.com/jessarchercodes)  (Organization)
        * [Waylon Walker](https://twitter.com/_waylonwalker)  (Comrade)


## 

>END

## Dummy end
...
<div class='prevnext'>

    <style type='text/css'>

    :root {
      --prevnext-color-text: #d8ebe6;
      --prevnext-color-angle: #83dcc8cc;
      --prevnext-subtitle-brightness: 3;
    }
    [data-theme="light"] {
      --prevnext-color-text: #1f2022;
      --prevnext-color-angle: #ffeb00;
      --prevnext-subtitle-brightness: 3;
    }
    [data-theme="dark"] {
      --prevnext-color-text: #d8ebe6;
      --prevnext-color-angle: #83dcc8cc;
      --prevnext-subtitle-brightness: 3;
    }
    .prevnext {
      display: flex;
      flex-direction: row;
      justify-content: space-around;
      align-items: flex-start;
    }
    .prevnext a {
      display: flex;
      align-items: center;
      width: 100%;
      text-decoration: none;
    }
    a.next {
      justify-content: flex-end;
    }
    .prevnext a:hover {
      background: #00000006;
    }
    .prevnext-subtitle {
      color: var(--prevnext-color-text);
      filter: brightness(var(--prevnext-subtitle-brightness));
      font-size: .8rem;
    }
    .prevnext-title {
      color: var(--prevnext-color-text);
      font-size: 1rem;
    }
    .prevnext-text {
      max-width: 30vw;
    }
    </style>
    
    <a class='prev' href='/neovimconf-2022/slides/slide-0'>
    

        <svg width="50px" height="50px" viewbox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M13.5 8.25L9.75 12L13.5 15.75" stroke="var(--prevnext-color-angle)" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"> </path>
        </svg>
        <div class='prevnext-text'>
            <p class='prevnext-subtitle'>prev</p>
            <p class='prevnext-title'>Slides | 0</p>
        </div>
    </a>
    
    <a class='next' href='/neovimconf-2022/03-talk-notes'>
    
        <div class='prevnext-text'>
            <p class='prevnext-subtitle'>next</p>
            <p class='prevnext-title'>Notes</p>
        </div>
        <svg width="50px" height="50px" viewbox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M10.5 15.75L14.25 12L10.5 8.25" stroke="var(--prevnext-color-angle)" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"></path>
        </svg>
    </a>
  </div>