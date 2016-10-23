# Working with git

`git` is an easy to use version control system (vcs) used by many OpenIndiana
projects, this page will give you a basic run-down on how to use `git` when
contributing to the OpenIndiana Docs.

## Cloning your fork

If you choose to fork the main `oi-docs` repository and work from there, you
will need to clone your repository, this can be done by typing either:


**Shell** <i class="fa fa-code fa-lg" aria-hidden="true"></i>

```bash
$ git clone git@github.com:OpenIndiana/oi-docs.git
$ cd oi-docs
```

or:

**Shell** <i class="fa fa-code fa-lg" aria-hidden="true"></i>
```bash
$ git clone https://github.com/OpenIndiana/oi-docs.git
$ cd oi-docs
```

into your terminal, replacing `OpenIndiana` with your github username.

### Adding the OpenIndiana repo as a remote

Adding the OpenIndiana oi-docs repo as a `remote` will allow you to submit
changes easily, to add the remote, simple enter either this:

**Shell** <i class="fa fa-code fa-lg" aria-hidden="true"></i>

``$ git remote add git@github.com:OpenIndiana/oi-docs.git``

or this.

**Shell** <i class="fa fa-code fa-lg" aria-hidden="true"></i>

``$ git remote add https://github.com/OpenIndiana/oi-docs.git``

Now to check if the remote was added, simply enter:

**Shell** <i class="fa fa-code fa-lg" aria-hidden="true"></i>
```bash
$ git remote -v
origin	git@github.com:AdrianKoshka/oi-docs.git (fetch)
origin	git@github.com:AdrianKoshka/oi-docs.git (push)
upstream	git@github.com:OpenIndiana/oi-docs.git (fetch)
upstream	git@github.com:OpenIndiana/oi-docs.git (push)
```

## Contributing to the docs

To make the review process of contributions easier, `branches` are used. An
explanation of `branches` can be found [here](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell).

### Creating a new branch

To create a new working branch, you simply enter:

**Shell** <i class="fa fa-code fa-lg" aria-hidden="true"></i>
 
``$ git branch name-of-branch``

to switch to the new branch:

**Shell** <i class="fa fa-code fa-lg" aria-hidden="true"></i>

``$ git checkout name-of-branch``

To switch back to the master branch, simply:

**Shell** <i class="fa fa-code fa-lg" aria-hidden="true"></i>

``$ git checkout master``
