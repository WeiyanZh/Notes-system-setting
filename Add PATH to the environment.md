I work with Linux (Ubuntu)  

## Temporary：only valid for this terminal (this login)   
in Terminal:   
`export PATH="$PATH:$HOME/Unix/homebrew/bin"`  or   
`export PATH="$PATH:$HOME/Unix/homebrew/bin"` or  
`export PATH=$PATH:$HOME/Unix/homebrew/bin`  or    
`export PATH=$PATH:~/Unix/homebrew/bin` or   
`export PATH=~/Unix/homebrew/bin:$PATH`

## Permanent  
`gedit ~/.profile` (open env. setting file)    
add PATH (refer to [this page.](https://unix.stackexchange.com/questions/26047/how-to-correctly-add-a-path-to-path))    
`source ~/.profile` (save)  
 
## Check the full PATH:   
`echo $PATH`   

## Check the PATH of some programs (e.g. GCC):   
`whcih gcc`
