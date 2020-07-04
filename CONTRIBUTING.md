# Guidelines for Contibution

**For all the bugs and improvement, first generate an issue, and then if you wish to resolve, do generate a pull request. If you only know the bug or wish us to resolve, then only generate an issue for the same.**

**If you wish to contribute generate a pull request mentioning what you have updated.**

## Open for Contribution

1. Fork the repository and then clone it. For cloning command is:
```
$ git clone "https://github.com/<username>/shell-scripting"
```

3. Do changes and stage them:
```
$ git add <filename>
```

4. Commit you changes with a commit message:
```
$ git commit -m "<message>"
```

5. Push changes to your forked repository:
```
$ git push -u origin branchname
```
6. Create a pull request to the upstream repository.

## Synchronize forked repository with Main repository (Needed if creating a branch)

1. Create upstream as our repository:
```
$ git remote add upstream "https://github.com/kshitizsaini113/shell-scripting"
```

2. Fetch changes from main repository:
```
$ git fetch upstream
```

3. Merge changes after being fetched:
```
$ git merge upstream/master
```

5. Push changes to your forked repository:
```
$ git push -f origin master
```
