## MAINTENANCE 
This project is a fork of [bbatsov/ruby-style-guide](https://github.com/bbatsov/ruby-style-guide)

### Setup original probject as remote
```bash
# add github repo as remote
git remote add bbatsov https://github.com/bbatsov/ruby-style-guide.git 

# verify remotes
git remote -v
```

### Merge bbatsov/ruby-style-guide
```bash
git fetch bbatsov

# review changes 
git diff master bbatsov/master

# merge them
git checkout master
git merge bbatsov/master
```

