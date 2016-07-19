GIT - branch-cleaner
===================================
The script is helpfull when you want to delete batch of branches. It finds all remote/local
branches by the author email and ask you for deletion.

Getting started
---------------

On Linux

1. Clone the repo. to your home folder.

2. Change the default settings:
```python
# defaults
REPOSITORY="local"
AUTHOR="example@gmail.cz"
PROJECT_FOLDER="current"
```

3. Add following code to your ~/.bash_aliases.
<code>alias git-clean='sh ~/git-branch-cleaner/git-branch-cleaner.sh'</code>
The name of alias is up to you.

4. Reload aliases in CLI.
<code>source ~/.bash_aliases</code>

5. Now when you go to project folder, the **git-clean** command execute git-branch-cleaner.

6. You can run it with some parameters overwriting default settings. Overview of options also is under **git-clean man** cmd:
  * **-a** - Author of the repositories. (email)
  * **-r** - You can set local or remote GIT repositories.
  * **-pf** - Define path to git repository. Usually root of your project. When passed value is **current**, the branch cleaner is looking for .git folder in current dir.

