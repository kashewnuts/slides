# PyCharm Practical Guide starting with Django

2018 Sep 17 / PyConJP 2018

Kashun Yoshida(@kashew_nuts)

---

## Who am I？

- [@kashew_nuts](https://twitter.com/kashew_nuts)
- Web Application Developer
- BeProud Inc.
- Like: Python, PyCharm, Vim, Climing

![kashew_nuts](assets/images/kashewnuts.png)

---

### What's BeProud？

* A programmer-focused company.
* Web services:
  * [Connpass](https://connpass.com/): IT meetup platform
  * [PyQ](https://pyq.jp/): Online Python learning

<table border="0">
<tr valign="middle">
<td>
![BeProud](assets/images/beproud-logo.png)
</td>
<td>
![connpass](assets/images/connpass-logo.png)
</td>
<td>
![PyQ](assets/images/pyq-logo.png)
</td>
</tr>
</table>


+++

### PyPro3 is published!

![PyPro3](20180917pyconjp/assets/images/pypro3-cover50per.png)


---

## Motivation

- "What about PyCharm?" Asked.
- There were various topics such as how to use PyCharm.
  - library, surrounding environment and so on.
- I thought that using PyCharm would like to summarize useful points.

+++

## Target
- "Want to try PyCharm but do not know how to use it."
- "Though I use PyCharm, I want to use it more"
- "There are other tools you are used to, but those who want to keep PyCharm also."

+++

## Goal
- PyCharm "Kanzen ni master".

---

## Prerequisites
- Sample is written by Python3.7 & Django2.1
- Used version: PyCharm Professional 2018.2
- Theme: [Django Girls Tutorial](https://tutorial.djangogirls.org/ja/)
- Repository: https://github.com/kashewnuts/djangogirlstutorial

---

## Contents
- PyCharm Overview
- What PyCharm can do
- Impression actually using PyCharm
- What PyCharm does not face
- DEMO
- Python Basic Feature
- Django, Front-end, Database supports
- Remote Development, Testing
- Things to keep in mind when using PyCharm

---

![pycharm-overview](20180917pyconjp/assets/images/pycharm-overview.png)

Source: https://www.jetbrains.com/pycharm/

+++

## What's PyCharm ?
- https://www.jetbrains.com/pycharm/
- Python IDE created by JetBrains Inc. of Czech Republic.
  - ~Python IDE for Professional Developers~
-  Available in some editions:
  - Professional: Full-Support
  - Community: Basic funstions for Python
- Summarized [PyCharm Editions Comparison](https://www.jetbrains.com/pycharm/features/editions_comparison_matrix.html)

+++

## Requirements, Installation & Launching
- Hardware:
  - RAM: 4GB minimum, 8GB recommended.
  - 1.5GB hard disk space + at least 1GB for caches.
  - 1024x768 minimum screen resolution.
- Software:
  - OS: Windows, macOS, Linux are suppoted
  - Python 2.4 or higher, Jython, PyPy, IronPython

+++

##  What PyCharm can do
- Intelligent Python Assistance
- Web Application Development
  * Django, Flask, Pyramid, JavaScript, ...
- Scientific tools (Jupyter, Numpy, matplotlib, ...)
- Debug, Testing, Profiling
- VCS support (Git, Mercurial, SVN)
- Deploy, Remote Development (Vagrant, Docker, SSH)
- Database & SQL (MySQL, PostgreSQL, Oracle, AWS, ...)

+++

## Impressions

+++

### Impressions (1)
- No longer need to find other tools.
- Both Python and Django know well.
  - Python itself, Django's urls, views, models, templates, etc ...
- Code completion, analysis, incremental search is clever.
- Python Fast tracking of circumstances is fast: Python 3.7, Django 2.1

+++

### Impressions (2)
- Debugger is excellent.
  - Asynchronous processing, Testing, JavaScript, Core Python
- Git's branch operation moves crisply & Easy to resolve conflicts.
- Troubleshooting is usually done by searching with SearchEverywhere or Find in Action.

+++

## What PyCharm does not face
- Creating a plugin (Need to write in Java/Kotlin)
- Instead of editor to edit single file.
- How to open and close some project many times.

---

# DEMO

---

## PyCharm Basic Feature
- Python syntax highlight, code completion, definition jump supported.
- Python 2 & 3 compatible.
- virtualenv support (also pipenv)
- GUI package manager
- Refactoring, Debugger, Code Inspection
- VCS support
- Terminal Support

+++

## Django support

- Specialized project type
- Run manage.py utility
- Enhanced code completion for Django, definition jump, debugging cooperation
  - UrlConf, View, Model, Templates, Forms, ORM
- Dependency diagram creation for Model

+++

## Front-end support
- The company's WebStrom (IDE for Front-end) is included.
- HTML, CSS, JavaScript code completion, definition jump, code analysis
- JavaScript Framework support
  - Angular, React, Vue.js, and more
- CSS Framework support
  - SASS, SCSS, Less, and more.

+++

## Database support
- The company's DataGrip (DataBase & SQL support) is included.
- SQL creation and execution, code completion, refactoring.
- Django ORM, SQLAlchemy support
- Supports CSV / JSON / XML output
- Many Database support:
  - Amazon Aurora, Amazon Redshift, MariaDB, MySQL, Oracle, PostgreSQL, SQL Server, SQLite3, and more.

+++

## Remote Development

- Vagrant, Docker, Docker Compose support
  - Start, Stop, Reload
  - Specify Remote Interpreters, Remote Debug
- SSH Remote
  - SSH using Vagrantfile
  - Running and debugging WSL
  - Remote connection using SSH or SSL
- Code deploy (SFTP)

+++

## Testing

- Supported: unittest, pytest, nose, doctest, tox
- Specify test target and execute
  - Failed test
  - Test under the specified class
  - Test specified functions
- View Coverage

---

## Full-stack Web Development

![Full-stack Web Development](20180917pyconjp/assets/images/fullstack-web-development.png)

Source: https://www.jetbrains.com/pycharm/features/web_development.html

+++

## Things to keep in mind when using PyCharm

+++

### Unexpected moves when you use tricky usage
- Q. What do you do if a problem arises?
- A. Divide what is the problem.
  - PyCharm's program？ Related tools？(Python, MySQL, Vagrant, Docker, SSH...)

+++

### Don't do your best if you take a bug in PyCharm
- "Invalidate Caches / Restart" ← Is something bad about something today?
- It is also fixed by Stop & Start. Clean installation is the last resort.
- Defect registered with Issue tracker or Vote
- If you find a problem register with Issue tracker or find it Vote
  - It will respond relatively quickly

+++

## Reference

- PyCharm Help ([ja](https://pleiades.io/help/pycharm/meet-pycharm.html) / [en](https://www.jetbrains.com/help/pycharm/meet-pycharm.html))
- [IntelliJ IDEAハンズオン 基本操作からプロジェクト管理までマスター](http://amzn.to/2ghcq8N)
- [Android Studio本格活用バイブル](http://amzn.to/2hbDtyJ)

---

# Thank you for your time and attention.

+++

# Any Question?
