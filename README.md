git-pull-request
==============

A shellscript to launch Google Chrome with pullrequest page of GitHub or BitBucket

### How to install
```bash
git clone git@github.com:brunoziie/git-pull-request.git
cd git-pull-request
sudo cp gpr /usr/bin/gpr
sudo chmod +x /usr/bin/gpr
```

### Usage

_$ **gpr** \<target-branch> \<source-branch>_

> Both of arguments are optionals. If not given will use the current branch
> 

### Notes

To work properly you need to add your upstream repo.
```bash
git remote add upstream YOUR_UPSTREAM_REPO_URL
```
