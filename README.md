
# Git interactive rebase
Many times, when working with Git, you may want to revise your local commit history. One of the great things about Git is that it allows you to make decisions at the last possible moment. You can decide what files go into which commits right before you commit with the staging area, you can decide that you didn’t mean to be working on something yet with git stash, and you can rewrite commits that already happened so they look like they happened in a different way. This can involve changing the order of the commits, changing messages or modifying files in a commit, squashing together or splitting apart commits, or removing commits entirely — all before you share your work with others.
One common use case for rewriting history is to clean up a series of commits before pushing them to a shared repository. This can make the commit history more readable and easier to understand for other developers who are working on the project.
In this section, you’ll see how to accomplish these tasks so that you can make your commit history look the way you want before you share it with others.

## Changing Multiple Commit Messages

