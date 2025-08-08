# Git From Start

Step 1: Git Installation

Windows: Download the git from below mentioned URL.
https://git-scm.com/downloads/win

Linux:Run the below command to install git in your linux (Ubuntu) system
# apt-get install git

git --version


Step 2: Git Configuration

git config --global user.name "Your Name"
git config --global user.email "you@example.com"


Step 3: Clone Repo

git init
git clone <url>


Step 4: Commit the changes

git add .
git commit -m " My First Commit "


Step 5: Connect local repo with remote and push the changes

git remote add origin <url>
git branch -M main
git push -u origin main



Kindly refer /screenshots/ for relevant screenshots.
