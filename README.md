# Student directory [![Build Status](https://travis-ci.org/ScPo-CompEcon/Students.svg?branch=master)](https://travis-ci.org/ScPo-CompEcon/Students)

# Homework Number 1: Pull requests

## How to do this homework

1. You can download a GUI to work with git for this homework. I don't recommend Github Desktop, because it does not allow you to easily *stash* changes, which is quite important. Good alternatives are GitKraken, SourceTree and GitTower. You are perfectly fine **without any GUI** as well (i.e. on the command line)
1. Fork this repository (click on **fork** top right of this page; this makes a copy of this repo on your github account [that is, *somewhere in the cloud*])
1. Go to your fork (it takes you there anyway), and clone your fork to your computer (click on **clone or download**)
	1. Copy the shown URL
	1. In your GUI, find out how to *clone* a new repo. Alteratively, on your command line, do 
	```
	git clone git@github.com:your_user_name/Students.git  # insert your user name
	```
	this will clone the repo to your present working directory on your computer. Let's assume this is your home directory, or `~`.
1. Make sure you have your github username handy
1. add a `JSON` file that describes yourself:
	1. With your editor, navigate to where you cloned this. Example: `cd ~`.
	1. Navigate to the [`_data/spring_2018/`](_data/) directory
	1. Open your text editor, create a file like the one below (you are looking at `floswald.json`), and save as `YOUR_GITHUB_USERNAME.json` in that directory `_data/spring_2018/`:

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

		**NOTICE**: take care to write this file *exactly* as it is shown above. One missing comma, and this will not work. 

	1. save this file
1. Go back to your GUI, or type `git status` on the command line.
1. In the GUI, select `YOUR_GITHUB_USERNAME.json` to be added to the next commit, or type `git add YOUR_GITHUB_USERNAME.json` on the command line.
1. write a summary of the change. Like: "added my username". command line `git commit -m 'added my username'`
1. push your commit to your remote at github: `git push` (click push in your gui)
1. Go to fork on github at `https://github.com/YOUR_USER_NAME/Students`
1. Click on `pull request`. see ![picture](PR.png)
1. Click on *create pull request* (several times). 
1. Done.
1. Now see if what you did checks out as correct on travis: go back to the original repo at [https://github.com/ScPo-CompEcon/Students](https://github.com/ScPo-CompEcon/Students)
1. Click on the (green?) badge next to the title in the readme. Find your build in the list of pull requests. see if it completes without error. 
1. If not: **fix the error!**
1. You will be able to push corrections onto the same pull request, by just pushing further commits to the branch you pushed to before. Each new push will trigger another build on travis.


***Teachers: see the [meta](meta.md) file for usage instructions.***


# License

Please observe that this repo is part of the [Sciences Po CompEcon Organisation](https://github.com/ScPo-CompEcon) and therefore subject to the license detailed at the bottom of [The Syllabus repo](https://github.com/ScPo-CompEcon/Syllabus).
