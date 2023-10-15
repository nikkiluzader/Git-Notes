### Your Identity

Git commit uses this information, and it’s immutably baked into the commits you start creating:

`git config --global user.name "John Doe"`
`git config --global user.email johndoe@example.com`

If you want to override this with a different name or email address for specific projects, you can run the command without the --global option when you’re in that project.

### Your default branch name

By default Git will create a branch called master when you create a new repository with git init. From Git version 2.28 onwards, you can set a different name for the initial branch.

To set main as the default branch: 

`git config --global init.defaultBranch main`

### Checking Your Settings

If you want to check your configuration settings, you can use the git config --list command to list all the settings Git can find at that point:

`git config --list`

You may see keys more than once, because Git reads the same key from different files ([path]/etc/gitconfig and ~/.gitconfig, for example). In this case, Git uses the last value for each unique key it sees.

You can also check what Git thinks a specific key’s value is by typing git config <key>:

`git config user.name`

### Setting up a remote (a remote repository)

This will vary depending on the platform (github.com, git.src.ht, etc)

Examples: [src.ht](https://man.sr.ht/tutorials/set-up-account-and-git.md)

`git config --list`

You may see keys more than once, because Git reads the same key from different files ([path]/etc/gitconfig and ~/.gitconfig, for example). In this case, Git uses the last value for each unique key it sees.

You can also check what Git thinks a specific key’s value is by typing git config <key>:

`git config user.name`
