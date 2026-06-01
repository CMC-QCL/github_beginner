# Another Beginner's Guide for GitHub

## Pre-requisite
- Git and
- GitHub account and
- Python and Visual Studio Code or 
- R and RStudio or
- Jupyter Lab

## Git Installation

### Windows

1. Download Git for Windows from https://git-scm.com/install/windows
2. Install Git
3. Configure local Git as follows  
`git config --global`

### MacOS

1. Install Git from Xcode through command line  
   `xcode-select --install`
2. or intall GitHub Desktop
3. Configure local Git as follows  
   `git config --global`

## First Push (i.e., sync)
1. Create a personal, public GitHub repo with README
2. __Clone__ the GitHub repo to your local drive
3. __Change directory__ to the downloaded repo (folder)
4. Open REAME.md (text editor, VSCode, etc.)
5. Edit REAME.md
6. Save REAME.md
7. Stage REAME.md (everything with .)   
`git add .`
8. Commit the change  
`git commit -m "my first change"`
9.  Push to the GitHub repo  
`git push`

