git-hook
========

flake8, ctags

### How to use
#### Step 0
Install Flake8
```
pip install flake8
```

#### Step 1
Move config dir to User home dir.
```
cp -r config ~/.config
```

#### Step 2
Move hook dir to User home git-templates.
Example:
```
mkdir -p ~/.git-templates
cp hooks ~/.git-templates/
git config --global init.templatedir ~/.git-templates/
```

#### Step 3
In your repo dir:
```
git init
```
echo:
Reinitialized existing Git repository in /XX/XX
