# **Week 6 Lab Report3**
## Streamlining ssh Configuration:
### 1. Show the .ssh/config file, edited with VScode:
![1config.png](1config.png)
### 2. Show the ssh command logging me into my account using the alias I chose:
![1ssh.jpeg](1ssh.jpeg)
### 3. Show an scp command copying a file to my account using just the alias I chose:
![1scp.png](1scp.png)
## Setup Github Access from ieng6
### 1. Show where the public key I made is stored on Github and in my user account (screenshot):
ieng620202 is the public key on ieng6
![2publicgithub.png](2publicgithub.png)
![2public.png](2public.png)
### 2. Show where the private key I made is stored on my user account (but not its contents) as a screenshot:
![2pivate.png](2private.png)
### 3. Show running git commands to commit and push a change to Github while logged into my ieng6 account:
Run ssh-keygen while logged into my course-specific account
![2run.png](2run.png)
Use `vi` to edit files on Linux 
![2run2.pmg](2run2.png)
Use `git add` and `git commit` to add and commit the changes
![2run3.pmg](2run3.png)
Use `git push` to push changes to GitHub
![2run4.pmg](2run4.png)
### 4. Show a link for the resulting commit:
[Link for the resulting commit](https://github.com/lineup30min/markdown-parser/commit/bbc02531a9d6933b4d7763421f55d54cc7ab66a9)
## Copy whole directories with scp -r
### 1. Show copying my whole markdown-parse directory to my ieng6 account:
![311.pmg](311.png)
![312.pmg](312.png)
*To have more control over what gets copied, use `scp -r *.java *.md lib/ cs15lsp22aji@ieng6.ucsd.edu:markdown-parse` to copy only md and java file*
![313.pmg](313.png)
### 2. Show logging into my ieng6 account after doing above and compiling and running the tests for my repository:
![32.pmg](32.png)
### 3. Show (like in the last step of the first lab) combining scp, ;, and ssh to copy the whole directory and run the tests in one line:
![33.pmg](33.png)