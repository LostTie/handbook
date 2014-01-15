Contribute
---------

Create a local branch based off master.

    git checkout master
    git pull
    git checkout -b <branch-name>

Stage changes

    git add --all
    
After you've staged changes (and resolved any conflicts), commit them

    git status
    git commit --verbose
    
Write a [good commit message]. Example format:

    Present-tense summary under 50 characters

    * More information about commit (under 72 characters).
    * More information about commit (under 72 characters).

    http:://project.management-system.com/ticket/123
    
Share your branch

    git push origin <branch-name>
    
Submit a [GitHub pull request].

[good commit message]: http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html
[GitHub pull request]: https://help.github.com/articles/using-pull-requests/
