## Moving
```shell
>>> cd ~/..
>>> ls #list items in directory
>>> cd ..[TAB] #autocomplete
```

## Files
```shell
>>> touch example.md #create a file
>>> mkdir example_folder #create a folder
>>> rm example.md #delete a file
>>> rm -r example_folder #delete a folder, (-r for recursively)
>>> xdg-open example.md #open a file
```

## Git
```shell
>>> git clone https://github.com/shintej/Linux-Commands.git #clone repo, also remember password is the id key
>>> git add --all #add all changes to the commit area
>>> git commit -m "commit_name"
>>> git push origin main #push local changes to main of remote repository 
>>> git pull origin main #pull remote repository changes of main to local origin
>>> git stash #send changes to a stash area which can be retrieved later
>>> git stash save "description"
>>> git stash list #lists the stashes saved
>>> git stash 
>>> git stash clear
>>> git stash drop <stash_id> #stash@{0}
```


