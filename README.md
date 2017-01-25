# MACHINE LEARNING AND DATA SCIENCE CLASS NOTES

## Overview

I'm using this repo as notebooks storage for Udemy Machine Learning Course

## Set UP

### Create virtualenv

Setup the project by installing binary dependencies (see notes section below).
Then create new virtualenv by running
```
virtualenv .env
```
I'm using python 2.7 if you have different default python version (check it running `python --version`)
you might need to specify python 2.7 when creating virtualenv
```
virtualenv -p `which python2.7` .env
```

launch virtualenv mode by typing
```
source .env/bin/activate
```
in project root directory

for more information about virtualenv installation and setup see [official documentation](https://virtualenv.pypa.io)

### Install requirements

run
```
pip install -r requirements.txt
```
in project root directory

## Notes

* This software requires [GraphViz](http://www.graphviz.org/Download..php) to be installed
  * [Arch Wiki](https://wiki.archlinux.org/index.php/Graphviz) pacman -S graphviz
  * [Homebrew](http://brewformulas.org/Graphviz) brew install graphviz
* When you add any pip dependency type `pip freeze > requirements.txt` in project root dir to update requirements.txt file
