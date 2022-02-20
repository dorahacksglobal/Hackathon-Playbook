# Welcome to the Hackathon-Playbook!
We're so glad you're here! Want to make a contribution to the Zknowledgebase?
Here's how 👇
## Prerequisites
* [homebrew](http://brew.sh/) for installing dependencies
  - `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
* [git](https://git-scm.com/) for maintaining code
  - `brew install git`
* [vscode](https://code.visualstudio.com/Download) for editing code
  - `brew install --cask visual-studio-code`
* [rbenv](https://github.com/rbenv/rbenv) for ruby versioning
  -  `brew install rbenv`
* [postgres](https://www.postgresql.org/) for database management
  - `brew install postgres && brew install postgis`
   - `brew services start postgresql`
    - stuck? run: `install pg`
* [yarn](https://yarnpkg.com) for package management
  - `brew install yarn`
## Installation
* clone and checkout the git repository
  - `git clone git@github.com:dorahacksglobal/Hackathon-Playbook.git`
  - `cd hackathon-playbook`
   - stuck? navigate directories via `ls` and `cd`
* set your GIT remote
  - `git remote add origin git@github.com:dorahacksglobal/Hackathon-Playbook.git`
## Create New Branch
- `git checkout main`
- `git pull origin main`
- `git checkout -b your-branch-name`
- `git push -u origin your-branch-name`
## Create Pull Request
* `open https://github.com/dorahacksglobal/hackathon-playbook/compare/master...your-branch-name\?expand\=1`
  - stuck? copy and paste terminal output url into your browser then create PR
* validate:
  - `base` = `main` (or branch you'd like to merge changes to)
  - `compare` = `your-branch-name`

## After peer review, merge it!
## You just contributed to a more secure future for us all ❤️

Bored? Help us keep this documentation train going!
