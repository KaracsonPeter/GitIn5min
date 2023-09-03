By reading this file, you will learn everything you need to know about git as a junior developer.

**Why Git?**  
I could write a story here, but please use your imagination why these features are pretty cool:  
 - You can follow, how your work evolved, like if you were looking at a photo album of your project's life
 - You can cooperate with you colleagues flexibly and work on the same thing in parallel
 - etc.

**What Git provides us:**  
You can take kinda take photos of your work.  
If you finished with a well separable part of your work, just use the `commit` command:  
```bash
# "Take photo and put it in one of your albums" command:
git commit -m "I added this change to my work because ..."
```
The second line you can see above is a terminal command. 
To execute that, you have to [install Git first](https://git-scm.com/download).  
After the installation process, you can open a terminal (windows button + write cmd & press enter)  
and type:  
```bash
git
```
This command now should be recognized by your system, and it will output all the possible parameters you can pass to git exe:
```bash
start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects
```

Seems scary, but for now (and pretty much in 97% of your time in the future) you will need to use only:
```bash
git init
git clone
git add
git status
git commit
git fetch
git pull
git push
```
OK, still scary xd  
#### 1. git init
You can define a git project (it does not require any parameter)

asdasd