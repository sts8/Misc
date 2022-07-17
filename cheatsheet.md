### restore the same state as if freshly cloned (https://stackoverflow.com/a/42185640)
```
git clean -ffdxn (-n = --dry-run)
```

### Untrack every file that is now in your .gitignore (https://stackoverflow.com/a/1139797)
First commit any outstanding code changes!
```
git rm -r --cached .
git add .
git commit -m ".gitignore is now working"
```

### list all authors in repo (https://stackoverflow.com/a/9597462)
```
git shortlog --summary --numbered --email --all (--committer)
```

### git config
```
git config user.name "sts8"
git config user.email "104705788+sts8@users.noreply.github.com"
```

### Maven: force update snapshot dependencies
```
mvn clean install --update-snapshots
```
