# Soto-Feliciano Lab Website

## Overview
 Github repository containing Soto-Feliciano lab frontend content, built with bootstrap, powered by scripts.mit.edu, and maintained by git

 Modifying styling/animations and scripts of this repo requires understanding of html, js, css, and bootstrap projects

 Any modifications of the backend, Django, requires understanding of Django in Python 3.7, Athena architecture, the scripts service, and sql (see [scripts web app frameworks](https://scripts.mit.edu/start/) & [django docs](https://docs.djangoproject.com/en/4.0/))

 Example cases:
 1. DB use on the frontend; tokens, logins, softcoding content delivery, serving downloadable  content properly, etc
 2. Backend/Middle activity; logging site usage, API integrations with entrez(NCBI), serving models built in python/R, etc

## Accessing where this repo is hosted on Athena, from terminal
1. `ssh [kerberos id]@athena.dialup.mit.edu` (will be prompted for password and duo authentication, see [Getting Started with Athena](http://kb.mit.edu/confluence/display/istcontrib/Getting+Started+with+Athena))
2. `cd /mit/superfancylab` (SF [locker](http://kb.mit.edu/confluence/display/istcontrib/AFS+Locker+Maintenance+Guide) directory, alias for /afs/athena.mit.edu/org/s/superfancylab, see [Andrew File System](http://kb.mit.edu/confluence/display/istcontrib/AFS+at+MIT+-+An+Introduction))
3. `cd /web_scripts/` (true directory of frontend materials), all git commands should take place from this wd

## Modifying automated git pull schedule and other tasks
1. Follow steps 1 & 2 from directly above
2. `cd /cron_scripts/`
3. `nano crontab` (modify this cron to match task needs, see [scripts cron](https://scripts.mit.edu/cron/) and `man cron` [cron manual](https://man7.org/linux/man-pages/man8/cron.8.html))

## Working on this repo
My IDE recommendation is [vscode](https://code.visualstudio.com/) or [dreamweaver](https://www.adobe.com/products/dreamweaver.html), either work very well for any frontend modifications of this project

Backend modifications to django, i.e. editing python scripts, are best done in [atom](https://atom.io/) or [jupyter](https://jupyter.org/)

Any issues related ***specifically and only to scripts services***, should be reported to scripts@mit.edu, and should include proper context

For any other ***highly critical issues***, contact [j4yr0u93](https://github.com/j4yr0u93)

Lastly, good git maintenance is essential to debugging (see [about git](https://docs.github.com/en/get-started/using-git/about-git) & [git cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf))

### *Happy Coding!*