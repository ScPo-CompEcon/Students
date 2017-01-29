# Student directory [![Build Status](https://travis-ci.org/ScPo-CompEcon/students.svg?branch=gh-pages)](https://travis-ci.org/ScPo-CompEcon/students)

# Homework Number 1: Pull requests

## How to do this homework

1. Download [https://desktop.github.com](https://desktop.github.com) for a simple interface to github. Open, **and login** with your github username. (alternatives are SourceTree and, of course, the command line)
1. Fork this repository (click on **fork** top right of this page; this makes a copy of this repo on your github account [*somewhere in the cloud*])
1. Go to your fork (it takes you there anyway), and clone your fork to your computer (click on **clone or download**)
	1. If you installed Github Desktop (recommended), click on "Open in Desktop"
	1. GitHub Desktop will ask you where you want the repo cloned to. Let's call that location on your computer `x`.
1. Make sure you have your github username handy
1. add a `JSON` file that describes yourself:
	1. Navigate to location `x`.
	1. Navigate to the [`_data/spring2017/`](_data/) directory
	1. Open your text editor, create a file like the one below (you are looking at `floswald.json`), and save as `YOUR_GITHUB_USERNAME.json` in the current directory:

		```json
		{
		  "emoji": "radio",
		  "introduction": "BBC6music is my favourite radio station",
		  "computing": "dynamic models of housing, location and labor"
		}
		```
		You should replace with your own 
		
		* `emoji` (choose from [this list](http://www.emoji-cheat-sheet.com/)), 
		* `introduction`, which should be something very brief about yourself, and 
		* `computing`, where you should state what kinds of computational problems you are (or think you will be) solving.

	1. save this file
1. Back in Github Desktop: You see it says *1 uncommitted change*. It tells you that the state of the repo changed. good.
1. write a summary of the change. Like: "added my username"
1. click on *commit to gh-pages*. `gh-pages` is the default branch on this repo, and that's where we want to add this new file. 
1. Top right in Github Desktop, click on *Pull Request*.
1. Additionally add more comments. Then click *Send Pull Request*.
1. Done.
1. You can go and look at your PR by clicking on the link that appears where you clicked.


***Teachers: see the [meta](meta.md) file for usage instructions.***


# License

Please observe that this repo is part of the [Sciences Po CompEcon Organisation](https://github.com/ScPo-CompEcon) and therefore subject to the license detailed at the bottom of [The Syllabus repo](https://github.com/ScPo-CompEcon/Syllabus).
