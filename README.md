
# Using Git and GitHub in the Course


## Introduction
In this lesson, we'll look at how we'll be using Git and GitHub as part of this course.

## Objectives
You will be able to:
* Provide feedback on the curriculum using "GitHub Isues"
* Fork (copy) and clone (download) projects from GitHub to work on as part of this course


The primary tool we'll use for this course is Learn. It's a custom learning management system that allows us to track both the content and your progress through it. 

![Learn](http://curriculum-content.s3.amazonaws.com/ent-ds-deloitte/learn-screenshot.png)

### Raising Issues 
If you ever see an issue with the curriculum, feel free to let us know! We're always updating the content to keep it fresh, but because of that, at any given time there are always a few typos and other issues that get through our QA process. 

If you ever see an issue with the curriculum you'd like to share, click on the "Issues" icon on the top right of the screen in learn.

![Issues Icon](http://curriculum-content.s3.amazonaws.com/ent-ds-deloitte/learn-screenshot-issues.png)

It'll take you to a "New Issue" screen in GitHub for that lesson where you can create an issue. Just fill out the required title and the optional description and click the green "submit new issue" button.

![New Issue Screen](http://curriculum-content.s3.amazonaws.com/ent-ds-deloitte/issues-screen.png)

Please try to be as specific as possible about the issue (ideally what is there, what you'd expect to be there and the difference between the two), and remember that issues are for bugs or typos in the curriculum. It won't get you technical or educational support if you're just having problems figuring out the lesson - ask your instructor for that!

### Working on Labs and Projects
For many simple lessons, you'll just view the content using Learn. However, some of the lessons (they have a title that ends with "Lab" or "Project") will require you to download the files so you can work on them locally. It is really important to do that so (a) you can save the changes to the work you do and (b) so you can get practice working with local files like you will on real projects after this course.

For such lessons (and to test it out, lets do it for this lesson as well!), start by clicking the GitHub icon, just to the left of the Issues icon at the top right of the screen in learn.

![GitHub Icon](http://curriculum-content.s3.amazonaws.com/ent-ds-deloitte/learn-screenshot-github.png)

That will take you to the project page on GitHub for the lesson.

![GitHub Icon](http://curriculum-content.s3.amazonaws.com/ent-ds-deloitte/project-page-github.png)


#### Forking a Lesson
When you get there, click on the "Fork" button in the top right.

![The Fork Button](http://curriculum-content.s3.amazonaws.com/ent-ds-deloitte/the-fork-button.png)

When you do so, it'll either pop up a window asking you where to fork it to (your main user account is fine), or it'll just start making the fork (copy) of the website. When it's finished, you'll notice it will take you to the new copy of the project. You know it's your copy because your GitHub username will be somewhere in the path now:

![The Forked Project](http://curriculum-content.s3.amazonaws.com/ent-ds-deloitte/the-forked-project-header.png)

Congratulations! You now have your very own copy of that project on GitHub that you can do anything with. That's really important - if you skipped this step, you wouldn't be able to upload a copy of any changes you made to save them on GitHub.

#### Cloning a Lesson
The next step is to download a copy of the lesson to your computer so that you can edit the files locally. That is called "cloning" the lesson/project/repo.

To do that, start by opening Git Bash (Click on the Windows Start button and then either select or search fir "Git Bash". That will open a terminal window where you can type commands. Welcome to the terminal window - you're going to get to see a lot more of it as the course continues!

Then type (or feel free to cut and paste to avoid typos) `git clone https://github.com/learn-co-students/ent-ds-del-0-4-using-git-and-github-ds-deloitte-03192019`

*In Git Bash, to paste from the clipboard the shortcut should be `ctrl-shift-insert`

This will create a new directory called `ent-ds-del-0-4-using-git-and-github-ds-deloitte-03192019`

Enter that directory by typing `cd ent` and then hitting the "tab" key to "tab complete" the directory name. Then hit the enter key and you'll be in the project directory. To confirm that you can `ls` which will list the contentsd of the directory. You should see a few files including a  CONTRIBUTING.md, a LICENSE.md, a README.md and an index.ipynb.


## Summary

Congratulations! You've installed the Anaconda distribution of Python, you've installed Git, and you've learned how to fork (copy) and clone (download) a lesson from GitHub. 

Don't worry if you're still a little fuzzy about all of the details or even if you ran into some technical challenges you couldn't resolve. We'll take a little time in the first lesson to go over this and in pretty much every future lesson we'll spend time practicing the basics. 

However, the good news is that you *should* have most of the software that you will need installed now, so we'll be able to jump right into learning some Python in the first class!

