# Introduction to GitHub
This tutorial is intended for absolute beginners.
In this two-part tutorial we will go over the following:

* Part 1: Introduction
  * why do we have GitHub
  * Overview of GitHub
  * Creating your account
  * Exploring GitHub
  * Creating your first repository
  * Forking and Pull request
  * Overview of markdown
* Part 2: Version Control
  * Staged and Unstaged changes
  * git add, status, diff, commit
  * branches
  * git branch
  * git checkout, merge
  * git log
  * git push

#### GitHub
GitHub is a platform for hosting and maintaining your code online. It makes collaboration easier with version control. Version control system is a system which allows multiple people to work on the same project without interference. It also lets you track the changes made by different people. Google drive also employs a version control. You might have noticed that google keeps track of who makes the edits in the shared folder. Changes made can also be rolled back.
GitHub brings a web interface to the powerful git version control. Github is a hub of developers. You can EXPLORE different projects online and work on them by forking them into your account. You can ask the original owner to include your contribution by creating a git pull request.
People often link their Github profiles to their resumes as GitHub is an excellent place to host your projects. You can make use of git markdown to document your project systematically. Once you make your projects public anyone who visits your profile can access them.

#### Creating your account
- Go over to GitHub.com and fill in your username, password and email id.
![create account](https://github.com/ab303/IntroGit/blob/master/GitHub/images/CreateAccount.png)
- now you will be asked to choose a plan. Unless you are going to put your private project on github you do not need to pick the paid version.
![choose plan](https://github.com/ab303/IntroGit/blob/master/GitHub/images/ChoosePlan.png)
- this third step is optional and you may skip it.
![step 3](https://github.com/ab303/IntroGit/blob/master/GitHub/images/step3.png)

#### Exploring GitHub
By clicking on explore tab in the top bar you reach the explore section of GitHub. Here you can browse trending repositories. You can also find interesting projects by using showcases.

#### Creating your first repository
To create a repository click on start a project or new repository.
![create repo](https://github.com/ab303/IntroGit/blob/master/GitHub/images/createRepo.png)
Check the option to initialize the repository with a readme file. enter a unique name for your repository and provide a small description.
![initialize repo](https://github.com/ab303/IntroGit/blob/master/GitHub/images/InitializeRepo.png)
![repo1](https://github.com/ab303/IntroGit/blob/master/GitHub/images/repo1.png)
Click on upload files to add files to your new repository
![uploading files](https://github.com/ab303/IntroGit/blob/master/GitHub/images/uploadFiles.png)
You can drag and drop your files in the box. Add comments to your commit i.e. new upload and choose the branch master.
![repo2](https://github.com/ab303/IntroGit/blob/master/GitHub/images/repo2.png)
GitHub recognizes the language used in your project.
![final](https://github.com/ab303/IntroGit/blob/master/GitHub/images/final.png)
Editing your readme file.
![edit readme](https://github.com/ab303/IntroGit/blob/master/GitHub/images/editReadme.png)

#### Forking and Pull request.
By forking a repo, you essentially copy the repository into your own account. You can work on this repository and that will not have any affect on the original repo.
When you want your work to be included in the original repository you can create a pull request.
for more info on forking click [here](https://help.github.com/articles/fork-a-repo/)
for more info on pull request click [here](https://help.github.com/articles/about-pull-requests/)

#### Git markdown
Git markdown is syntax for styling your documents. This comes in handy when you're documenting your repositories online.
* text
* lists
* images
* headers and quotations
* code

##### text
- to make text bold just wrap the text like this `**bold**` and the result looks like this **bold**
- to make the text italic warp the text like this `*italic*` and the result looks like this *italic*
- to include links your text just mention them as is or to hide links behind text you can do so like this `[link](https://www.google.com)` the result will look like this [link](https://www.google.com)
- to include crossed out text - `~~crossed out~~` result will look like this - ~~crossed out~~

##### lists
- you can use numbered lists by using numbers 1. 2. 3.
- you can use unordered likes by using * and -
- to use sublists you should indent them 2 spaces

##### images
images can be included in the by using this format `![Alt Text](url)`. The image below has been included by `![Example image](https://github.com/ab303/IntroGit/blob/master/GitHub/images/banana.jpg)`
![Example image](https://github.com/ab303/IntroGit/blob/master/GitHub/images/banana.jpg)

##### headers and quotations
Headings in your document can be marked with `#` character. If you want subheadings use multiple `#` characters. The smallest heading size includes six hash characters (`######`)
To highlight quotes in your text begin the line with `>` character

##### code
- inline code can be included in between two `
- for multiple lines of code enclose them in  ```
