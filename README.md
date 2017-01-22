# Student directory [![Build Status](https://travis-ci.org/ScPo-CompEcon/students.svg?branch=gh-pages)](https://travis-ci.org/ScPo-CompEcon/students)

Repository for practicing doing pull requests. 

## How to do this homework

1. Fork this repository (click on **fork**; makes a copy of this repo here on your github account [*somewhere in the cloud*])
1. Go to your clone (it takes you there anyway), and clone your fork to your computer (click on **clone**)
1. Make sure you have your github username handy
1. add a `JSON` file that describes yourself:
	1. Go to wherever you cloned it this repo on your computer.
	1. navigate to the [`_data/spring2017/`](_data/) directory
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
1. add this directory to the index of files to commit: `git add _data/spring2017/`
1. commit to your local repository: `git commit -m 'added my username file'`
1. push to your repo on github: `git push origin master`
1. commit to your local repository
1. submit a pull request to *this* repository (i.e. the original one, owned by the ScPo-CompEcon organisation, at [https://github.com/ScPo-CompEcon/students](https://github.com/ScPo-CompEcon/students)). You do this by clicking on the "New pull request" (PR) button on **your** fork of that repo.
1. Submitting your PR will trigger a test program which will check that your file is in the correct format. Your submission is correct if you see a green tick next to the list of pull requests. If you see a red cross, something's wrong, and you can keep pushing corrections to your repo until it's fixed (green tick).



***Teachers: see the [meta](meta.md) file for usage instructions.***


# License

Please observe that this repo is part of the [Sciences Po CompEcon Organisation](https://github.com/ScPo-CompEcon) and therefore subject to the license detailed at the bottom of [The Syllabus repo](https://github.com/ScPo-CompEcon/Syllabus).
