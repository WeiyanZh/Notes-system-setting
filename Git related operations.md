# Git-related Operations
I use VSCode with Git.  
## Issues:
1, [VSCode "please clean your repository working tree before checkout."](https://stackoverflow.com/questions/51817479/vscode-please-clean-your-repository-working-tree-before-checkout)    
Solution: **Stash --> sync the changes (or Pull) --> pop stash**  
You can also use corresponding commands in terminal: 
```
git stash
git pull
git stash pop
```
2, [VS Code Disable 'Working Tree' Git Preview Window](https://tomkadwill.com/vscode-disable-working-tree-git-preview-window)  
Solution: **File --> Preferences --> Setting --> searching for ` openDiffOnClick` --> disable it**  

3, Branch management     
Create branch dev: `git branch dev`  
Switch to branch dev: `git checkout dev` or `git switch d  ev`  
Create and switch to branch dev: `git checkout -b dev`
Checkout branchs: `git branch`  
Merge branch dev to matser: `git merge dev`  
Push local master to remote master: `git push origin master`  
Delete branch dev if you want: `git branch -d dev`  

