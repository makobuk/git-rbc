GIT - remote-branch-cleaner
===================================
The script is helpfull when you are deleting batch of remote branches. It finds all remote
branches beginning with "brachPrefix" and ask you if you want to delete it.

branchPrefix - in our company we prefix own branches with initials (John Smith => js)


Getting started
---------------

1. Download the script to root directory of all projects

2. Change the branchPrefix in script
<code>
branchPrefix='js'
</code>

2. Run it with one parametr:
<code>
git-rbc projectDir
</code>

3. Conform branches to delete.

