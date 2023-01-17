### What is Git?
Git is a version control software which comes pre installed with linux/mac but have to download for 
windows. Git is a memory card for a code or folder in your local computer to track the changes made and to time travel in the older version if needs come. To track any folder in your computer: go to that particular folder and do git init. Ls -la will give you a .git directory. MAke some changes and follow add/commit and push to save the chnages made. 

- git help < git command like push or what ever you want to know >
- git init:   &nbsp;  Initializes a git repository by creating initial .git directory in a new or in an existing project. Its like putting a momry in that particular folder.
- git clone: &nbsp; Copies an existing Github repo to local machine.
- git status: &nbsp; checks the working dorectory to see if up-to-date with the remote repo. 
- git add . : add all the changes to the staging area of the working directory. This is the first step in commiting changes to your local versions of the repo before pushing them to the remote GIthub version of the repo. 
- git commit -m "provide the commit message": &nbsp; Git records the changes made to yur version of the repo. 
- git push: &nbsp; pushes the local repo changes to the remote repo. To push the chnages you need username and classical token (no PW accepted now days)
- git pull:&nbsp; 
- git status: &nbsp;
- git branch: &nbsp; 
  
  
  <br />
  <br /> 

  
  ### `Git branch`
  Git branch allows you to work independent environment so that your changes don't affect other branches until you merge.

  ```  
    - git status
    - git branch <branch_name>
    - git branch -a
    - git push -u origin <branch_name>
    - git checkout <branch_name>
    - git status
    - echo "test >> test.sh
    - git status
    - git add test.sh
    - git commit -m "Test"
    - git commit -am "Description of the changes"
    - git push 
    - git chekout master
    - git checkout -b <branch_name>: Its a new way to create the branch if it does not exist. It depends on the refrence branch like if you are in main than it will create a brance refencing the main branch
    - git branch -D/d <branch_name> (-d will give warning that the branch is not fully merged so use -D)
    - git push origin --delete <branch_name>
    - git commit --ammend --no-edit
    - git checkout <commit token from git log>: to go back intime and see previous commit.
    - git pull origin master: to pull the Gthub repo master branch to the local computer to sync between them else will be trouble.
  ```
 
 
 
- git --version:&nbsp; Check the version 
- git config --global user.name "  "
- git config --user.email "your email" 
- git config --list
- git help <command> or git <command> --help
- git init: &nbsp; start tracking a project 
- rm -rf .git: if you wanna remove a git tracking for a particular project
- git status: 
- touch .gitignore
- git add -A or git add . or git add <what you want to file>
- git reset <what you want to remove from staging area>
- git commit -m "Detail description"
- git log: see commit that we have made 
- git clone <url> <where you want to clone>
- git clone https://github.com/sumandhamala/pySparkTraining.git  /Users/sumandhamala/pySpark 
- git remote -v : information abot clone 
- git branch -a
- git diff: shows the chnages made to the project or code
- git status 
- git add -A
- git status 
- git commit -m "message"
- git pull origin master or main : it pull the remote repo to sync with other developer since last time we have pull it
- git push origin master or main :   push the commits to the remore repo.
- git branch <branch_name>
- git  branch:  list all the branches 
- git checkout <branch_name>
- git push -u origin <branch_name>: (-u associates local to remote repo)
- git branch -a:to see all branches 
- git checkout master
- git pull origin master 
- git branch --merged
- git merge <name_branch>
- git push origin master
- git branch --merged
- git branch -d <branch_name>
- git push origin --delete <branch_name>
-     
- 








 
 
<br />
<p align = "center">
<img src="Git_flow.png"  alt="drawing" width="300"/>
<figcaption align = "center">  Fig.1 - Best description of the git work flow. Picture credit goes to bytebytego.com </figcaption>























# MarkDown Tips and Tricks
###  `Headers:`
 - #H1, ## H2, ## H3, H4 ###, H5 ####, ......
_____________________________________________________________________
  ### `Space and paragraph change:`
- <br />  changes the paragraph
- &nbsp; add space between the words
________________________________________________________________________
### `Text Decorations:`  
- **bold**, *italic*, 
- ~~ StrikeThrough text ~~
________________________________________________________________________
### `Links:`  
- [My github](https://github.com/sumandhamala "Add description if you want")
- [Links](#headers "link to previous place in the documents")
- [Reference link]: https://www.youtube.com/watch?v=ftOBvusMHjQ
-  [My Github][Reference link] 
________________________________________________________________________  
### `Images:`
-  ![Image descriptions](image path or drag and drop the picture and press SHIFT)
________________________________________________________________________  
### `Unordered and Ordered List:` 
- `*` for unordered list while 1., 2., for ordered list

________________________________________________________________________
### `Code Blocks:`
```python (programming language name)
def Sum (self.a, self.b):
  returns self.a + self.b
```
Addition = print(Sum(1+2))
________________________________________________________________________
### `Inline code block:`
- `Suman`. 

________________________________________________________________________
### `Tables:`
-  Tables can be created with headings and text alignment options.

    |Stocks|Price|
    |:---:|:---:|
    |TSLA|230|
    |APPL|130|

    Tables        | Are           | Cool  |
    | ------------- |:-------------:| -----:|
    | col 3 is      | right-aligned | $1600 |
    | col 2 is      | centered      |   $12 |
    | zebra stripes | are neat      |    $1 |

    Markdown | Less | Pretty
    --- | --- | ---
    *Still* | `renders` | **nicely**
    1 | 2 | 3
   
_____________________________________________________________________

### ` Blockquotes:`
> This is an example of a blockquote
>> This is sub blockquote example.
________________________________________________________________________

### `Horizontal Rules:`
- Three or more ...
- Hyphens: ---
- Asterisks: ***
- Underscores: ___
  
  _______________________________________________________________________

### `Youtubes videos Link:`
- [![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](https://www.youtube.com/watch?v=ftOBvusMHjQ)
_________________________________________________________________________
### `Comments which does not render`
- [This is a hidden comments format.]: #
- <!-- This is commented out. Like the case in HTML. -->
_________________________________________________________________________
### `Callouts`
> :bulb: **Tip:** Here is an important tip to remember! ...
> 
> :smile: **Smile emoji:** Here is the smiling emoji.  ...
> 
> :blush: **BLush emoji:** Here is the blush emoji.
> 
> :cry:  **Cry emoji:** Here is the cry emoji.
________________________________________________________________________
### `Resources:`
  1) [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#links)

2) [MarDown Notes](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)