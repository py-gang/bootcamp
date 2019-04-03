# Python Developer's Tools

## Targets

Have Python developer's workspace well prepared

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table of Contents

- [Install](#install)
  - [Core](#core)
  - [Integrated Development Environment](#integrated-development-environment)
  - [Package management](#package-management)
  - [DataBase](#database)
  - [Git preps](#git-preps)
  - [Data Science](#data-science)
    - [Jupyter Notebooks](#jupyter-notebooks)
- [When completed](#when-completed)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->


## Install

Choose what install from options below as per your OS and
specific needs you may have.

### Core

Python comes in two distinct and incompatible versions.
You may be required to use either depending on assignment.

Start with [Python 3.6+](https://www.python.org/downloads/).

You may also need [Python 2.7+](https://www.python.org/downloads/release/python-2715/)
for older projects.

**Advanced:**

[The definitive guide to setup my Python workspace](https://medium.com/@henriquebastos/the-definitive-guide-to-setup-my-python-workspace-628d68552e14)
provides for guidelines to managing multiple environments.

### Integrated Development Environment

[PyCharm](https://www.jetbrains.com/pycharm/) is a recommended IDE.
Choose between:
 - fully fledged commercial [PyCharm Pro](https://www.jetbrains.com/pycharm/download/) that offers
   [free individual licenses for students and faculty members](https://www.jetbrains.com/student/) though
 - [PyCharm Edu](https://www.jetbrains.com/pycharm-edu/download/),
   not so rich in features as Pro, yet offers more features than Community does
 - free yet feature depleted [PyCharm Community](https://www.jetbrains.com/pycharm/download/)

For editions comparison see
[Pro vs Community explained](https://blog.jetbrains.com/pycharm/2017/09/pycharm-community-edition-and-professional-edition-explained-licenses-and-more/),
[Pro vs Community comparison matrix](https://www.jetbrains.com/pycharm/features/editions_comparison_matrix.html),
[Edu vs Community](https://news.ycombinator.com/item?id=13851218).

Skip the following if you manage things with PyCharm successfully. 

Other options are:
 - [Visual Studio Code](https://code.visualstudio.com/) +
   [Python for VSC](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
   extension
 - [Enthought Canopy](https://www.enthought.com/product/canopy/)
   (focused towards Scientists and Engineers
   as it provides pre installed libraries for data analysis)
 - [Eclipse](https://www.eclipse.org/) +
   [Aptana PyDev](http://www.pydev.org/) for Eclipse
 - [Komodo Edit](https://www.activestate.com/products/komodo-edit/) FOSS
 - [Spyder](https://www.spyder-ide.org/) FOSS,
   specifically aimed at working with scientific Python libraries 
   (namely [SciPy](https://www.scipy.org/)), provides integration with 
   [pyflakes](http://pypi.org/project/pyflakes/),
   [pylint](https://www.logilab.org/857), and
   [rope](https://github.com/python-rope/rope)
 - [WingIDE](http://wingware.com/)
 - [NINJA-IDE](http://www.ninja-ide.org/)
 - [Eric](http://eric-ide.python-projects.org/)
 - [Sublime Text](http://www.sublimetext.com/)
 - [TextMate](https://macromates.com/) (MacOS)

### Package management

Package manager is a tool to manage libraries and modules.

[pip](https://pypi.org/project/pip/) is a sufficient option.

### DataBase

[PostgreSQL](https://www.postgresql.org/download/) is a recommended RDBMS.

[MySQL Community Server](https://dev.mysql.com/downloads/mysql/)
is yet another option.

### Git preps

As you will keep your code with git VCS it makes sense to have your git 
configured specifically for your environment. As a minimum set `.gitignore`
properly up to take care of your peers.

Read [Why global `.gitignore`](https://dev.to/oleksiyrudenko/please-do-not-pollute-projects-gitignore-3h8e)

Have your IDE ignore rules in your global `.gitignore`.
The recommended minimum is:
```
.DS_Store
.idea
```

You may also have Python environment specific rules added.
Check rule sets from [gitignore.io](https://www.gitignore.io/api/python)
and [github/gitignore](https://dev.to/oleksiyrudenko/please-do-not-pollute-projects-gitignore-3h8e).

### Data Science

#### Jupyter Notebooks

**Advanced topic**

Jupyter Notebooks are a powerful way to write and iterate on your Python
code for data analysis. 
[How To Use Jupyter Notebooks](https://www.codecademy.com/articles/how-to-use-jupyter-notebooks)

[Install Jupyter notebooks](https://jupyter.org/install)
at some post-beginner stage of your Python education.

## When completed

When done let others know you have passed this module.

This lets other know your progress and probably someone
will ask you for some help in this module.

Where to communicate? In a chat you came here from :)

Now you are ready to proceed to 
[Python Essentials](./python-essentials.md)
