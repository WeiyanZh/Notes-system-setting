# Git-related Operarions
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
