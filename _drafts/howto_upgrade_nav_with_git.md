---
layout: post
title:  "Howto upgrade Dynamics NAV code with Git"
tagline: XXX easy steps.
date:   2014-07-02 00:00:00
author: Dennis Decoene
category: Tech
tags: [NAV,Upgrade]
---
{% include JB/setup %}

Upgrading with git is quite straightforward and relatively easy to do. Mind you, a NAV upgrade is never easy. Git does lessen the burdon though.
So let's get cracking ;-) If you don't know about git, what it is or what it does I'd suggest reading the first chapters of [the Pro git e-book](http://git-scm.com/book/en/Getting-Started-About-Version-Control)

1. Step One, set it up.
-----------------------

	First you will need to install git of course. You can get the software from [the git project's website](http://git-scm.com/).
	
	Personally I like the software from Github.com much more. It is much more user friendly and modern. You can get it at [the Github for Windows site](https://windows.github.com/)
	It is still in early stages of development and nowhere near the speed of the software from the git project. Not for larger repo's like a NAV merge, consisting of 6000 files.
	I can assure you however the folks at github are working on that. I'm personally in touch with them.
	They gave me a private repo to upload a merge I was doing so they can see what is going on and how they can improve. 
	So, I have high hopes.
	
	For now, we will have to live with git's software. When the Github software is stable and fast I will write an article on how to merge with that software too.
	
	Once you installed the software, fire up "Git GUI". You will be presented with a form asking you to create, clone or open a repository. You will want to create a new local repository in a folder of your choice. Do so now, then close "Git GUI".
	
	You will need the file object splitter you can [find here](http://www.mibuso.com/dlinfo.asp?FileID=831) too. We will use it to parse the txt object files from NAV. 
	
2. Step Two, get the old base version in the repo.
--------------------------------------------------
	
	* In NAV, open a standard database of the version the customisations where based on.
	* Export all the objects to a txt file.
	* Use WinNavObjectSplitter to split the file. Split them to the folder you created the repo in.
	* Open "Git GUI" again and open the repo.Click "Stage changed".
	* Enter a commit message like "Dynamics NAV Vxx".
	* Commit this version.
	
3. Step Three, get the custom version in the repo.
--------------------------------------------------
