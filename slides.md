#![](http://upload.wikimedia.org/wikipedia/commons/b/b3/GitHub.svg)

---

# Building this project

First install [landslide](https://github.com/adamzap/landslide)

    pip install landslide

Then run make

    make build

Or take the Markdown and convert it to your format(s) of choice

---

# Git + Hub = GitHub

## GitHub is Git at it's core

* Git repo hosted on a server
* HTTPS and SSH push and pull access

## And then there's the... Hub?

* Snazzy web interface on top of Git
* Additional features for maximum productivity

---

# What can't you do with GitHub?

* most merges
    - fast forward
    - three-way with conflicts
    - octopus
* rebase
* cherry-pick
* tag(?)
* client-side hooks
* plumbing and porcelain

---

# Git ∩ GitHub

* init
* clone (fork)
* commit
* create/delete branches
* merge no-conflict branches
* hooks

---

# The extra stuff

* [pull requests](https://help.github.com/articles/using-pull-requests)
* [issues](https://github.com/blog/831-issues-2-0-the-next-generation)
* [wiki](https://github.com/blog/774-git-powered-wikis-improved)
* [network graph](https://github.com/blog/39-say-hello-to-the-network-graph-visualizer)
* [server-side hooks](https://help.github.com/articles/post-receive-hooks)
* [pages](http://pages.github.com/)
* [gist](https://gist.github.com/)
* [status.github.com](https://status.github.com/)

---

# Committing

* commit often
* discrete changes
* useful commit messages
    - First line: 50 chars max; succinct
    - Second line: blank
    - Third line+: description of commit if necessary; try to wrap to 72 chars

---

# Branching

* branch often
* no extra cost
* always test before pushing to `master` on GitHub

---

# Pull Requests...

## ...are awesome!

Open a pull request when:

* you want feedback from others
* you are merging a long branch
* you are merging a short branch
* you are working on a branch that you someday want to merge, but aren't ready yet, but maybe want to have some discussion about it or at least have a record of the fact that you are going to merge someday

When merging a pull request, add the names of other reviewers to the comments.

---

# Issues

Issues should warrant code changes.

* bug/feature tracking
* can be closed though commits
* can be linked to in pull requests
* can be viewed for all projects at once

---

# Wiki

* not so great
* per project
* weirdly hidden
* let's stick to READMEs and solid code commenting

---

# Beware

* rebasing a branch on GitHub

